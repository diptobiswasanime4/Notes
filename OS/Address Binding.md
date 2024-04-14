Created: April-15-2024

In *Source Program* addresses are symbolic

*[[Compiler]]* typically binds these symbolic addresses to relocatable addresses

*[[Linker-Loader|Linkage Editor or Loader]]* binds the relocatable addresses to absolute addresses

Each binding is a mapping from one address space to another.

1. Compile Time - If we know at compile time where the process will reside in memory then absolute code can be generated
2. Load Time - If it is not known at compile time where the process will reside in memory, then the compiler must generate relocatable code
3. Execution Time - If the process can be moved during its execution from one memory segment to another, then binding must be delayed until [[Runtime]]

# Related Notes

1. [[Operating System]]
# References

1. 