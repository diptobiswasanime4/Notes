Created: May-03-2024

Criteria is RR
Mode is non-preemptive

[[Scheduling Algorithm - SJF|SJF]] and [[Scheduling Algorithm - SRTF|SRTF]] are good, but longer jobs wait longer causing Starvation

HRRN solves this issue

Response Ratio = (WT + BT) / BT = 1 + WT / BT

So low BT means high RR

High WT means high RR

So shorter jobs, and longer jobs waiting for long will be selected. This is like [[Scheduling Algorithm - Priority Scheduling|Priority Scheduling]] where the priority is HRRN

HRRN is non-preemptive

# Related Notes

1. [[Operating System]]
# References

1. 