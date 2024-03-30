Created: March-22-2024

A priority is associated with each process, and the [[CPU]] is allocated to the process with the highest priority

[[Scheduling Algorithm - SJF|Shortest-Job-First]] is also a Priority [[Algorithm]] where the priority is the inverse of the duration of the next CPU burst

Priority Scheduling can be either preemptive or non-preemptive

Preemptive priority scheduling algorithm will preempt the CPU if the priority of the newly arrived process is higher than the priority of the currently running process.

Non-preemptive priority scheduling algorithm will simply put the new process at the head of the ready queue
## Problems

1. Indefinite blocking or starvation
2. May leave some low priority fast processes waiting indefinitely
## Solution

1. Ageing is a technique of gradually increasing the priority of the processes that wait in the system for a long time
# Related Notes

1. [[Operating System]]
2. [[CPU Scheduling]]
# References

1. 