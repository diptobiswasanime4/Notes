Created: March-22-2024

When two or more process are being executed in the OS at the same time, they could be either:

1. Independent Processes - cannot affect or cannot be affected by other processes executing in the system
2. Cooperating Processes - can affect and be affected by other processes executing in the system. In other words, processes that shares data with other processes
## Features

1. Information sharing
2. Computation speedup
3. Modularity
4. Convenience

Cooperating processes require an interprocess communication (IPC) mechanism that will allow processes to exchange data and information

There are two fundamental models of interprocess communication:

1. [[Shared Memory System]] - Processes can exchange info by reading and writing data on the shared region of the [[Memory]]
2. [[Message Passing System]] - Processes exchange messages between each other
# Related Notes

1. [[Operating System]]
2. [[Processes & Threads]]
# References

1. 