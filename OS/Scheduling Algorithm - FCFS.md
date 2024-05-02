Created: March-22-2024

**Criteria** is *arrival time*
**Mode** is *non-preemptive*

First Come First Serve (FCFS) is the simplest [[CPU Scheduling]] [[Algorithm]]

It means the process that requests the [[CPU]] first, should be allocated the CPU first.
## Advantage

Implementation of FCFS can easily be managed through FIFO (First-In-First-Out) queue
## Disadvantage

If processes with higher burst time arrive before processes with lower burst time, then smaller processes have to wait for a long time for bigger processes to release the CPU. This is also called **Convoy Effect**

FCFS is a non-preemptive scheduling algorithm

Convoy effect causes Starvation.
# Related Notes

1. [[Operating System]]
2. [[Scheduling Algorithms]]
# References

1. 