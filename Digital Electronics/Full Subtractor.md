Created: April-09-2024

Full Subtractor keeps track of Borrow and does Full Subtraction.

| A   | B   | C   | D   | $B_o$ |
| --- | --- | --- | --- | ----- |
| 0   | 0   | 0   | 0   | 0     |
| 0   | 0   | 1   | 1   | 1     |
| 0   | 1   | 0   | 1   | 1     |
| 0   | 1   | 1   | 0   | 1     |
| 1   | 0   | 0   | 1   | 0     |
| 1   | 0   | 1   | 0   | 0     |
| 1   | 1   | 0   | 0   | 0     |
| 1   | 1   | 1   | 1   | 1     |
From [[Karnaugh Map (K' Map)|K' Map]] we have,

D = A $\oplus$ B $\oplus$ C
$Bo$ = B.C + $\overline A$.C + $\overline A$.B

# Related Notes

1. [[Digital Electronics]]
# References

1. 