Created: April-14-2024

An alternative method for avoiding deadlocks is to require additional info about how resources are to be requested

**Safe State** is when the system can allocate resources to each process (up to its maximum) in some order and still avoid a deadlock

A system is in a *safe state* only if there exists a *safe sequence*

**Safe Sequence** is when in a sequence of processes $P_1, P_2, ..., P_n$ for the current allocation state, for each $P_i$ the resource requests that $P_i$ can still make, can be satisfied by the currently available resources plus the resources held by all $P_i$

**Unsafe State** is where a deadlock could occur

![[Safe Unsafe Deadlock State excal.45.excalidraw]]

# Related Notes

1. [[Operating System]]
2. [[Deadlock]]
# References

1. 