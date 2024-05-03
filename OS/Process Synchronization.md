Created: March-22-2024

Let's say we have 2 processes $P_1$ and $P_2$ they can:

1. Cooperate and Complete a task
2. Compete for resources

If the processes are in two different Computers Networking Software will help

If the processes are in the same Computer Operating System will help. This is called **Inter-process Communication**

Cooperating process is a process that can affect or be affected by other processes executing in the system.

Cooperating process can either:

1. Directly share a logical address space
2. Be allowed to share data only through files or messages

Concurrent access to shared data may result in data inconsistency!

A situation where several processes access and manipulate the same data concurrently and the outcome of the execution depends on the particular order in which the access takes place is called a **race condition**
## Requirements of Synchronization Mechanism

1. Primary
	1. Mutual exclusion
	2. Progress
2. Secondary
	1. Bounded waiting
	2. Portability or Architectural neutrality

# Related Notes

1. [[Operating System]]
2. [[Producer Consumer Problem]]
3. [[Buffer]]
# References

1. 