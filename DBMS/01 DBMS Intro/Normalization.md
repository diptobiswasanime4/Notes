Created: June-14-2024

1. Introduction to DB anomalies
2. Functional Dependency
3. Attribute Closure, Membership test
4. Finding Candidate Keys
5. Lossless join and Dependency Preserving
6. Normal forms
	1. 1NF
	2. 2NF
	3. 3NF
	4. BCNF
7. Finding highest NF & Relational Schema
8. Decomposition into higher NFS
9. MVD & 4NF
10. Canonical Cover of FD Set

**Normalization** is used to eliminate/ reduce redundancy in DB tables

If 2 or more independent relations are stored in single relation, then it forms redundancy

Normalization is splitting tables to eliminate redundancy. Problems happen due to redundancy are called DB anomalies

1. Insertion Anomaly
2. Deletion Anomaly
3. Updation Anomaly - Updating 1 row isn't enough

If there is 0% redundancy is DB tables, then there will be no anomalies

### How to avoid anomalies?

Decompose relation R into sub relations R1, R2, ... Rn

This is called Normalized DB

# Related Notes

1. [[Database Management System]]
# References

1. 