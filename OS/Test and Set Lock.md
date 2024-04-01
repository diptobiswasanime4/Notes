Created: March-22-2024

- It is a hardware solution to the [[Critical-Section Problem]]
- There is a shared lock variable which can take either of the two values, 0 or 1
- Before entering the critical section, a process inquires about the lock
- If it is locked, it keeps on waiting till it becomes free
- If it is not locked, it takes the lock and executes the critical section

Example - Bathroom, only one person can enter at a time, another person inquires then enters.
# Related Notes

1. [[Operating System]]
# References

1. 