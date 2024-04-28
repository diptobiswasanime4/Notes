Created: April-28-2024

Processes can have some attributes or properties.

## Process ID

This is a unique number given to a process. This is similar to Port number.

![[Process id.excalidraw]]
## Program Counter

Program counter keeps track of the next instruction to be executed.

![[Program counter.excalidraw]]

Let's assume $P_1$ has PC = 10

After sometime $P_1$ is removed form [[CPU]] and $P_2$ is executed

After sometime $P_1$ is brought back, it will start executing from instruction 10 like a Bookmark
## Process State

Every process will have some state in its lifetime

Example - Ready, Running, Finish
## Priority

Processes will have a priority, but not compulsory
## General Purpose Register

CPU has Registers RA, RB, RC

If they have some values associated with process $P_1$ then those values must be saved if $P_1$ is temporarily removed from the CPU for another process $P_2$

All the values of the [[Registers]] are stored inside a [[Data Structure]] called [[Process Control Block]] (PCB) associated with a Process. Operating System manages PCB

Storing Register values in PCB and getting new Register values from PCB is called [[Context Switching]]

![[Context Switch.excalidraw]]
## List of Open Files

Every process opens some files and this info must be maintained
## List of Open Devices

Every process may open some devices and this info must be maintained
## Protection

This is required for security
## [[Process Control Block]] (PCB)

Every process will be managed by storing all info in [[Process Control Block]] (PCB)

Looking at PCB we should know everything about a process. Operating System will maintain a [[Linked List]] of PCBs

OS will look into PCB and decide which process to give [[CPU]]. Hence PCB is also called Context, and PCB helps in [[Context Switching]]

![[PCB Linked List excal.excalidraw]]

Forcefully taking off CPU is called **pre-emption**

![[OS preemption.excalidraw]]

# Related Notes

1. [[Operating System]]
2. [[Process]]
# References

1. 