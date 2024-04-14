Created: April-15-2024

When Program runs, apart from its own modules, it also need to use certain System Libraries as well

**Static Linking** is when System language libraries are treated like any other object module and are combined by the loader into the binary program image

One **disadvantage** is that each program on a system must include a copy of its language library in the executable image. It wastes both disk space and [[Main Memory]] space

**Dynamic Linking** checks to see whether the needed routine is already loaded in the memory. If not, the routine is loaded into [[Memory]]

Dynamic Linking is similar to [[Dynamic Loading]]. Only difference is that Dynamic Linking is postponed till execution time

# Related Notes

1. [[Operating System]]
# References

1. 