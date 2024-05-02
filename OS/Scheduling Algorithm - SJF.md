Created: March-22-2024

When [[CPU]] is available, it is assigned to the process that has the smallest next CPU burst

SJF can be both preemptive and non-preemptive

Hence a more appropriate term for this [[Algorithm]] could be Shortest-Next-CPU-Burst Algorithm

We use some prediction methods, although exact BT cannot be calculated, but can be guessed.
## Advantages

SJF tells us what best is possible, hence SJF is used as a benchmark for other Scheduling Algorithm
## Problems

1. It is very difficult, sometimes impossible to find out the length of the next CPU burst
2. SJF cannot be implemented at the level of short-term CPU scheduling, although it is optimal

![[SJF excal.excalidraw]]

For SJF, TAT and WT is minimum except for [[Convoy Effect]]

[[Throughput in OS|Throughput]] is high compared to other Algos

So SJF is best but useless because it cannot be practically used

# Related Notes

1. [[Operating System]]
2. [[CPU Scheduling]]
# References

1. 