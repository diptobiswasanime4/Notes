Created: March-22-2024

The objective of [[Multiprogramming & Multitasking|multiprogramming]] is to have some process running at all times, to maximize [[CPU]] utilization.

The objective of time sharing is to switch CPU among processes so frequently that users feel like they're interacting with the Program real-time

To meet these objectives, we have the Process Scheduler that selects an available process from a set of several available processes for program execution
## Scheduling Queues

- As processes enter the system, they are put into a **job queue** which consists of all processes in the system
- Processes that are residing in the [[Main Memory]] and are ready and waiting to be executed are kept in the **ready queue**
# Related Notes

1. [[Operating System]]
2. [[Multiprogramming & Multitasking]]
3. [[Processes & Threads]]
# References

1. 