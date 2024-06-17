Created: June-11-2024

Users directly interact with the Disk through flat files.

It is good for small DB. If DB is huge then FFS fails.
## Limitations

1. Too Complex to manage application programs
2. More IO Cost to manage Data
3. [[Degree of Concurrency]] (Parallel users) is very low, usually 1
4. Too complex to maintain different levels of access control
5. Complex to remove redundant data

# Related Notes

1. [[Database Management System]]
# References

1. 