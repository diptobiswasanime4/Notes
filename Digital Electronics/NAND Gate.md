Created: April-07-2024

NAND Gate along with [[NOR Gate]] are Universal Gates.

NAND Gate along with [[NOR Gate]] doesn't follow associative law.

NAND Gate is also called as Bubbled OR Gate
## Enable & Disable

0 is disable, Y = 1

1 is enable
## Unused Input

Same as AND Gate

- In [[Transistor-Transistor-Logic (TTL)|TTL logic]] if any input is open or floating, it will act as 1
- In [[Emitter-Coupled Logic (ECL)|ECL logic]] if any input is open or floating, it will act as 0

There are 3 ways to deal with unused input:

1. Connect with 1, or $V_{cc}$ = high voltage
2. Connect with one of the used inputs
3. For TTL, open input = 1 (for ECL, open input = 0, hence Y = 0, because 0 is disable for AND Gate)
# Related Notes

1. [[Digital Electronics]]
2. [[Logic Gate]]
# References

1. 