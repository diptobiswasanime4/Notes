Created: March-22-2024

Operating System has 2 modes in which a Program can execute:

1. User Mode
2. Kernel Mode (Privileged Mode)
## User Mode

If a Program is executing in the User Mode, it doesn't have access to [[Memory]], and [[Hardware]] resources of the Computer.

So if a Program crashes in the User mode, nothing happens to the system. Hence this mode can also be called as the *Safe Mode*
## Kernel Mode

If a Program is executing in the Kernel Mode, it has direct access to [[Memory]], and [[Hardware]] resources. Hence this is also called Privileged Mode.

But if a Program crashes in the Kernel Mode, the entire system crashes

![[Modes of OS excal.excalidraw]]

When a Program is executing in User mode but it needs access to Hardware resources, it makes [[System Call|System Calls]]

Temporarily the Program switches to Kernel mode to use the Hardware resources, then returns back to User mode. This is also called **Context Switching**
# Related Notes

1. [[Operating System]]
2. [[Kernel]]
# References

1. 