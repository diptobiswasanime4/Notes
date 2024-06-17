Created: June-11-2024

**Database** is collection of related data

**DBMS** is [[Software]] used to manage and access database files in efficient way

Before DBMS there was flat files on [[Operating System|OS]]. Users directly interact with the Disk through flat files.

[[Flat File System]] is good for small DB. If DB is huge then FFS fails.

## Advantages

1. Supports Data independency. Users can manage data using SQL without having to know the Storage information
2. Because of indexing IO cost will be less
3. [[Degree of Concurrency]] (Parallel users) is very high
4. Because of the presence of [[Views (Virtual Table)]], we can have different levels of access control
5. Easy to remove redundant data (because of [[Normalization]])

## Limitations of Flat File System

1. Too Complex to manage application programs
2. More IO Cost to manage Data
3. [[Degree of Concurrency]] (Parallel users) is very low, usually 1
4. Too complex to maintain different levels of access control
5. Complex to remove redundant data

## Integrity Constraints



# Related Notes

1. [[Database Management System]]
# References

1. 