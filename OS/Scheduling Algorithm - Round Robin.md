Created: May-03-2024

In this Algo a process will run for a fixed time called *Time Quantum* and will move to ready state and another process will start running, and so on, and so on.

So this is a preemptive Algorithm

![[Round robin Flow Chart.excalidraw]]

When TQ increases Context Switching decreases and Average Response time increases

When TQ decreases Context Switching increases and Average Response time decreases

This not a rule, this is a general trend.

When TQ = $\infty$ Round-Robin becomes [[Scheduling Algorithm - FCFS|FCFS]]

TQ shouldn't be tool high because RT increases

TQ shouldn't be too low because Context Switching Overhead increases.

TQ is decided experimentally.

Since RR is not based on Burst time, it's used in many OS, because it's practical

# Related Notes

1. [[Operating System]]
# References

1. 