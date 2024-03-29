Created: March-22-2024

[[Interprocess Communication]] using shared memory requires communicating processes to establish a region of shared memory

Typically a shared-memory region resides in the address space of the process creating it. Other processes that wish to communicate using this shared-memory segment must attach it to their address space.

Normally the Operating System tries to prevent one process from accessing another processes' memory, hence shared memory requires multiple processes to agree to remove this restriction.
# Related Notes

1. [[Operating System]]
# References

1. 