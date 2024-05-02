Created: May-02-2024

Computer Scientists have invented Burst Time Prediction Techniques

Prediction Techniques can be classified into:

1. Static
	1. Process size
	2. Process type
2. Dynamic
	1. Simple averaging
	2. Exponential averaging
## Process Size

Based on past experience we can guess BT. 

If previously 20 MB file takes 20 units of time to process, 21 MB file will take similar time.

This is inaccurate
## Process Type

We classify processes into various types and we give BT for each type

We can classify OS, Games, Apps, etc. and assign sometime for them.

This is also inaccurate because such predictions are also dependent on human behavior
## Simple Averaging

We have n processes $P_1, P_2, ..., P_n$ having BTs as $T_1, T_2, ... ,T_n$

We can guess $T_{n+1} =$ $\large \sum$ $T/n$

This is also inaccurate because each process can be independent
## Exponential Averaging

$\large \tau _{n+1}$ = $\large \alpha .t_n + (1 - \alpha).\tau _n$ 

$\large \tau _{n + 1}$ = Predicted time of process (n + 1)
$\large \tau _n$ = Predicted time of process n
$t_n$ = actual time of process n
$\alpha$ = smoothening factor, $\large 0 <= \alpha <= 1$ 

# Related Notes

1. [[Operating System]]
# References

1. 