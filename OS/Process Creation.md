Created: March-29-2024

A process may create several new processes, via a create-process [[System Call]] during the course of execution.

The creating-process is called a parent process, and the new processes are called the children of that process. Each of the new processes can create more processes, forming a tree of processes.

When a parent process creates a child process, 2 possibilities emerge:

1. The parent continues to execute concurrently with children
2. Parent waits until some or all of its children are terminated (so sad!)

There are also 2 possibilities in terms of the address space of the new process:

1. Child process is a duplicate of the parent process
2. Child process has a new program loaded into it
# Related Notes

1. [[Operating System]]
2. [[Process Control Block]]
# References

1. 