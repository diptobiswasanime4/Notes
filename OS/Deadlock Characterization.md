Created: April-14-2024

[[Deadlock]] occurs only if the following 4 necessary conditions hold simultaneously in a system:

1. Mutual exclusion
2. Hold and wait
3. No preemption
4. Circular wait
## Mutual Exclusion

At least one resource must be held in a *non-shareable mode*

If another process requests for that resource, the requesting process must be delayed until the resource has been released.
## Hold and Wait

A process must be holding at least one resource and waiting to acquire additional resources that are currently being held by other processes
## No pre-emption

Resources cannot be pre-empted that is a resource can be released only voluntarily by the process holding it, after that the process has completed its task
## Circular Wait

A set { $P_0, P_1, ... , P_n$ } of waiting processes must exist such that $P_0$ is waiting for a resource held by $P_1$, $P_1$ is waiting for a resource held by $P_2$, ... , $P_{n-1}$ is waiting for a resource held by $P_n$

All 4 conditions are not independent of each other, but all must hold for a Deadlock to occur.

# Related Notes

1. [[Operating System]]
# References

1. 