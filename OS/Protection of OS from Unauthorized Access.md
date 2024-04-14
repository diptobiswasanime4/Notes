Created: April-14-2024

1. The Operating System must be protected from access by user processes
2. Also, user processes must be protected from one another
3. Protection must be provided by the [[Hardware]]

To do this we have to ensure that each process has a separate memory space

We need the ability to determine the range of legal addresses that the process may access and to ensure that the process can access only these legal processes

For this purpose we use two [[Registers]]:

1. BASE - Holds the smallest legal physical memory space
2. LIMIT - Specifies the size of the range

![[BASE LIMIT Registers.excalidraw]]

The Base and Limit Registers can be loaded only by the OS using a privileged instruction, that can be executed only in the Kernel Mode. This allows OS to change the value of the Registers but prevents user programs from doing the same

![[Base Limit check excal.excalidraw]]

# Related Notes

1. [[Operating System]]
# References

1. 