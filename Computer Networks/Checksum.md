Created: April-17-2024

Checksum checks sum

1. Break original message into k number of blocks with n bits in each block
2. Sum all k blocks
3. Add carry to the sum, if any
4. Do [[1's & 2's Complement|1's complement]] to the sum. This is the checksum
5. Send the checksum along with the data
## Features

1. Checksum detects all errors involving odd number of bits
2. Detects most errors involving even number of bits
3. If one or more bits of a segment are damaged and the corresponding bit or bits of opposite value in a second segment are also damaged, the sum of those columns will not change and the receiver will not detect errors


# Related Notes

1. [[Computer Network]]
2. [[Error Detection]]
# References

1. 