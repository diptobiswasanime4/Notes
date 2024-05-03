Created: May-03-2024

Let's say we have two processes $P_1$ and $P_2$

```cpp
{
	// Code 1
	count++;
	// Code 2
}
```

```cpp
{
	// Code 1
	count--;
	// Code 2
}
```

Similar Code in Assembly language for $P_1$
	
	MOV count, R0
	Increment R0
	MOV R0, count

for $P_2$
	
	MOV count, R0
	Decrement R0
	MOV R0, count

In case of preemption there will be data inconsistencies in this case,

for example

$P_1 \longrightarrow$ 1
$P_2 \longrightarrow$ 1, 2, 3
$P_1 \longrightarrow$ 2, 3

In this case, count = 6

What we expect in case of no preemption is count will be incremented to 6 by $P_1$ then decremented to 5 by $P_2$ hence count = 5

And different values will be loaded onto the [[Process Control Block|PCB]] even if the Register is same

So this is like a race, where the **race condition** is the order of execution of instructions

Hence it is race condition that causes *data inconsistency*
## Conditions for Race Condition

1. Shared memory
2. Preemption
## Critical Section

The part of the code where shared resources are accessed is called Critical section

The real problem happens when both process are entering Critical section and getting preempted

So we must avoid this

# Related Notes

1. [[Operating System]]
2. [[Registers]]
# References

1. 