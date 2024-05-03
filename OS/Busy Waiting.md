Created: May-03-2024

When we have 2 process $P_1$ and $P_2$

Let's assume $P_1$ is in [[Critical Section]] but is preempted

$P_2$ will try to enter CS, but will be stuck in the entry loop. After $P_1$ is preempted it can enter

*Without Busy Waiting* there is no entry loop. Rather $P_2$ will get into sleep mode as it comes in the entry of the CS. After the completion of $P_1$ it can enter

![[busy waiting excal.excalidraw]]

# Related Notes

1. [[Operating System]]
# References

1. 