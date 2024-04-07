Created: April-07-2024

## Enable & Disable

0 is disable for AND Gate, because when B = 0, Y = 0, irrespective of the value of A

1 is enable for AND Gate, because when B = 1, Y = $A$ or $\overline A$ depending on the value of A
## Unused Input

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