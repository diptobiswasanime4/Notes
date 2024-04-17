Created: April-17-2024

- In CRC the sender and receiver agrees upon a common divisor
- Data will be divided by the divisor and the remainder is the CRC
- CRC should be passed with the Data

In case the CRC is a polynomial $\large x^n + x^{n-1} + ... + x^2 + x + 1$

if we have $\large x^n$ we put 1, else we put 0

If there is non-zero remainder that means there are errors in transmission

If length of the polynomial is L, length of CRC bits is L-1

# Related Notes

1. [[Computer Network]]
2. [[Error Detection]]
# References

1. 