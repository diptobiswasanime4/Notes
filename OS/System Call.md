Created: March-22-2024

System call, also called Monitor call is an [[Interrupt]] emitted by [[Software]], not [[Hardware]]

System calls provide an interface to the services made available by the Operating System

It is essential to have an understanding about the 2 [[Modes of Operating System]] before delving deep into system calls.

System call is the Programmatic way in which a computer program requests a service from the [[Kernel]] of the OS

System calls are generally available as routines written in C and C++
### Sequence of System Calls for Copying Contents of a File

1. Acquire Input Filename
2. Write prompt to screen
3. Accept Input
4. Accept Output Filename
5. Write prompt to screen
6. Open Input File
7. If File doesn't exist, ABORT
8. Create Output File
9. If File exists, ABORT
10. Read from Input File
11. Write to Output File
12. Loop lines 11-12, until Read fails
13. Close Output File
14. Write Completion message on screen
15. Terminate Normally

# Related Notes

1. [[Operating System]]
# References

1. 