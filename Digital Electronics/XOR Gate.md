Created: April-07-2024

Exclusive OR, also called as Ex-OR or XOR Gate along with [[XNOR Gate]] are Arithmetic Logic Gates

| A   | B   | Y   |
| --- | --- | --- |
| 0   | 0   | 0   |
| 0   | 1   | 1   |
| 1   | 0   | 1   |
| 1   | 1   | 0   |
XOR Gate is also called odd 1s detector
## Properties

$Y = A \oplus B = A. \overline B + \overline A.B = (A + B).(\overline A + \overline B)$

$A \oplus A = 0$
$A \oplus \overline A = 1$
$A \oplus 0 = A$
$A \oplus 1 = \overline A$

if $A \oplus B = C$ then,
	$B \oplus C = A$
	$A \oplus C = B$
	$A \oplus B \oplus C = 0$

$A \oplus A \oplus A... = A$ or 0

A  when n = odd
0 when n = even

## Enable & Disable

Both 0 and 1 acts as enable

0 acts as buffer, 1 acts as inverter

Because of this reason XOR Gate is also called as Controlled Inverter


# Related Notes

1. [[Digital Electronics]]
2. [[Logic Gate]]
# References

