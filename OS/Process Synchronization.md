Created: March-22-2024

Cooperating process is a process that can affect or be affected by other processes executing in the system.

Cooperating process can either:

1. Directly share a logical address space
2. Be allowed to share data only through files or messages

Concurrent access to shared data may result in data inconsistency!

A situation where several processes access and manipulate the same data concurrently and the outcome of the execution depends on the particular order in which the access takes place is called a **race condition**
# Related Notes

1. [[Operating System]]
2. [[Producer Consumer Problem]]
3. [[Buffer]]
# References

1. 