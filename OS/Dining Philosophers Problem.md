Created: March-22-2024

## Problem

- A number of Philosophers are seated across a round-table, they can either think or eat
- When they're thinking they're in their own world, and cannot interact with anybody
- Each philosopher has a plate of food and a fork, but they're philosophers, so they take two forks to eat
- No two adjacent philosophers can eat at the same time
## Solution Using Semaphores

A simple solution is to represent each fork with a [[Semaphores|semaphore]]

A philosopher grabs a fork by executing a wait () operation on the semaphore

Philosopher releases the forks by executing the signal () operation on the appropriate semaphores

So we will have the shared data as

	semaphore fork[5];

Here all elements of fork are initialized to 1
## Remedies to avoid Deadlocks

- Allow at most 4 philosophers to be sitting simultaneously at the table
- Allow a philosopher to pick up forks only when both forks are available
- Odd philosopher should pick left fork first then the right, Even philosopher should pick up right fork first then the left
## Solution Using Monitors

- Deadlock-free solution
- This solution imposes the restriction that a philosopher may pick up his chopsticks only if both are available
- To achieve this, we need to distinguish among 3 states in which we may find a philosopher. Hence we introduce the following [[Data Structure]]

		enum { thinking, hungry, eating } state [5];

- Philosopher i can set the variable state i as eating only when his two neighbors are not eating
- We also need a condition, where Philosopher i can delay himself when has doesn't have available forks
# Related Notes

1. [[Operating System]]
# References

1. 