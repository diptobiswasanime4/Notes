Created: March-22-2024

[[Interrupt|Interrupts]] cause the OS to change a [[CPU]] from it's current task and to run a [[Kernel]] routine, and such operations happen frequently on general-purpose-systems

When an [[Interrupt]] occurs, the system needs to save the current context (current state) of the process running on the [[CPU]] so that it can restore the context when processing is done, essentially suspending the earlier process, then resuming it. This task is known as Context Switching

The context is represented in the [[Process Control Block]] of the process

# Related Notes

1. [[Operating System]]
# References

1. 