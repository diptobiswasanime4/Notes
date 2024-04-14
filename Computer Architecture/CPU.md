Created: April-14-2024

CPU can directly access only:

1. [[Registers]] built into the processor
2. [[Main Memory]]

Registers are accessible within one cycle of the CPU clock

Main Memory access may take many cycles of the CPU clock to complete

In the 2nd case the processor generally needs to stall, since it doesn't have the data required to complete the instruction that it is executing. This situation is intolerable because of the frequency of memory accesses

One remedy is to add fast memory between the CPU and Main Memory, also called as [[Cache]]

# Related Notes

1. [[Computer Architecture]]
2. [[Computer Organization]]
3. [[Operating System]]
# References

1. 