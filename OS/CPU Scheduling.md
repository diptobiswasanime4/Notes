Created: March-22-2024

CPU scheduling is switching [[CPU]] resources among processes by the Operating System, which makes the [[Computer]] more productive
## CPU Scheduler

CPU Scheduler is the authority who selects the process to be executed by the CPU
## Dispatcher

Dispatcher is the module that gives control of the CPU to the process selected by the CPU Scheduler.

Time taken for the dispatcher to stop one process and start another process is known as **dispatch latency**
## When CPU-scheduling Decisions Take Place

1. Process switches from *running state* to *waiting state*
2. Process switches from *running state* to *ready state*
3. Process switches from *waiting state* to *ready state*
4. When a process terminates

For situations 1 and 4, there is no choice in terms of scheduling.

When scheduling takes place under circumstances 1 and 4, the scheduling is non-preemptive or cooperative, otherwise it is preemptive
# Related Notes

1. [[Operating System]]
2. [[Multiprogramming & Multitasking]]
3. [[Processes & Threads]]
4. [[Process Scheduling]]
# References

1. 