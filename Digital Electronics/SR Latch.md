Created: April-09-2024

S stands for Set, means output = 1

R stands for Reset, means output = 0

This is also a real-world usecase of Logic [[Enable & Disable]]
## NOR SR Latch

| S   | R   | $Q$    | $\overline Q$   |
| --- | --- | ------ | --------------- |
| 0   | 0   | Memory | with case 2 & 3 |
| 0   | 1   | 0      | 1               |
| 1   | 0   | 1      | 0               |
| 1   | 1   | Not    | used            |

## NAND SR Latch

| S   | R   | $Q$    | $\overline Q$   |
| --- | --- | ------ | --------------- |
| 0   | 0   | Not    | used            |
| 0   | 1   | 1      | 0               |
| 1   | 0   | 0      | 1               |
| 1   | 1   | Memory | with case 2 & 3 |

# Related Notes

1. [[Digital Electronics]]
2. [[Latch]]
# References

1. 