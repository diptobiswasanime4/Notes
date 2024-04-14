Created: April-14-2024

- In a [[Multiprogramming & Multitasking|Multiprogramming]] environment several processes may compete for a finite number of resources
- A process requests for resources, if the resources are not available the process enters a Waiting State
- Sometimes, a waiting process is never again able to change state, because the resources it has requested are help by other waiting processes

This situation is called a **Deadlock**
## System Model

A system consists of a finite number of resources to be distributed among a number of competing processes

The resources are also partitioned into several types, each consisting of some number of identical instances
## Utilization

Under normal mode of operation, a process may utilize a resource only in the following sequence:

1. Request
2. Use
3. Release

# Related Notes

1. [[Operating System]]
# References

1. 