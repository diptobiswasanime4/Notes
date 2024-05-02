Created: March-22-2024

CPU scheduling is switching [[CPU]] resources among processes by the Operating System, which makes the [[Computer]] more productive
## CPU Scheduler

CPU Scheduler is the authority who selects the process to be executed by the CPU
## Dispatcher

Dispatcher is the module that gives control of the CPU to the process selected by the CPU Scheduler.

Time taken for the dispatcher to stop one process and start another process is known as **dispatch latency**

![[ready to run scheduler excal.excalidraw]]
## When CPU-scheduling Decisions Take Place

1. Running $\longrightarrow$ Waiting, Process switches from *running state* to *waiting state*
2. Running $\longrightarrow$ Ready, Process switches from *running state* to *ready state*
3. Waiting $\longrightarrow$ Ready, Process switches from *waiting state* to *ready state*
4. Running $\longrightarrow$ Termination, When a process terminates
5. New $\longrightarrow$ Ready (maybe eligible for immediate scheduling)

For situations 1 and 4, there is no choice in terms of scheduling.

When scheduling takes place under circumstances 1 and 4, the scheduling is non-preemptive or cooperative, otherwise it is preemptive
# Related Notes

1. [[Operating System]]
2. [[Multiprogramming & Multitasking]]
3. [[Processes & Threads]]
4. [[Process Scheduling]]
# References

1. 