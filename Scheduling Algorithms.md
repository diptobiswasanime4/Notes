Created: May-01-2024

Few parameters to be considered for Scheduling Algorithms.

1. Time
	1. Point of time
	2. Period of time

Time can be classified into:

1. Arrival time - Time at which a process enters the ready queue (point of time)
2. Burst time - Amount of CPU time required by a process to finish its execution (period of time)
3. Completion time - Time at which a process completes (point of time)
4. Turn around time - Total time a process is in the system (period of time)
5. Waiting time - Time process is waiting for [[CPU]] (period of time)
6. Response time - Time taken from arrival time to scheduling a process for the 1st time (period of time)

![[CPU Scheduling Time.excalidraw]]

TAT = CT - AT

$\implies$ TAT = BT + WT

In case of non-preemptive Algorithms, WT = RT
## Popular Scheduling Algorithms

1. [[Scheduling Algorithm - FCFS]]
2. [[Scheduling Algorithm - SJF]]
3. [[Scheduling Algorithm - SRTF]]

## CPU Scheduling

Picking up a process from a ready state and giving it to CPU is called CPU Scheduling

STS with the help of Dispatcher will do the Scheduling


# Related Notes

1. [[Operating System]]
# References

1. 