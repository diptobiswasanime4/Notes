Created: April-09-2024

Half adder is when only half of the addition is done.

Carry = 1, but 1 + 1 = 10

This is done for Electronic simplicity.

We have to use [[Full Adder]] to get the correct result

- HA is used to add single-bit number
- Doesn't take carry

Half adder usually has 2 inputs A and B, and 2 outputs Sum S, and Carry $C_o$

| A   | B   | S   | $C_o$ |
| --- | --- | --- | ----- |
| 0   | 0   | 0   | 0     |
| 0   | 1   | 1   | 0     |
| 1   | 0   | 1   | 0     |
| 1   | 1   | 0   | 1     |
We have,

S = A $\oplus$ B
$C_o$ = A.B

![[Half Adder excal.excalidraw]]
# Related Notes

1. [[Digital Electronics]]
# References

1. 