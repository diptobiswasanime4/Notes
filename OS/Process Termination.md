Created: March-22-2024

A process terminates when it finishes execution of its final statement and asks the OS to delete it by using the exit [[System Call]]

At this point, the process will return a status value to its parent process via the wait () System call

All resources of the process, including physical and virtual memory, open files, I/O buffers are deallocated by the OS
## Process Termination in Different Circumstances

1. A process can cause the termination of another process via an appropriate [[System Call]]. The parent may terminate the process. There are some reasons for it:
	1. Child has exceeded its usage of some of the resources it has been allocated
	2. Task assigned to the child process is no longer required
	3. Parent is terminating, and the OS won't allow an orphan process
# Related Notes

1. [[Operating System]]
# References

1. 