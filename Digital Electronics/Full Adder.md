Created: April-09-2024

Full Adder is Sum.

Carry = 1, then, 1 + 1 = 11

But this is only sum for single digit numbers. For multi-digit Sum you can refer [[4 Bit Parallel Adder]]

Full Adder usually has 3 inputs, A, B and $C_i$ (the carry from the previous step)

Like [[Half Adder]] Full Adder has 2 outputs Sum S and Carry $C_o$

| A   | B   | $C_i$ | S   | $C_o$ |
| --- | --- | ----- | --- | ----- |
| 0   | 0   | 0     | 0   | 0     |
| 0   | 0   | 1     | 1   | 0     |
| 0   | 1   | 0     | 1   | 0     |
| 0   | 1   | 1     | 0   | 1     |
| 1   | 0   | 0     | 1   | 0     |
| 1   | 0   | 1     | 0   | 1     |
| 1   | 1   | 0     | 0   | 1     |
| 1   | 1   | 1     | 1   | 1     |
We have,

S = A $\oplus$ B $\oplus$ $C_i$
$C_o$ = A.B + B.$C_i$ + A.$C_i$ = A.B + $C_i$(A $\oplus$ B)

# Related Notes

1. [[Digital Electronics]]
# References

1. 