Created: June-13-2024

Referential refers to Foreign Key

Integrity means Correctness

Constraints means Conditions

Hence it is also called Foreign Key Integrity Constraints (FKIC)

## Referenced Relations

1. **Insertion** doesn't cause any FKIC
2. **Deletion** may cause violation to FKIC. 3 Solutions are there
	1. On delete no action (no Deletion)
	2. On delete Cascade (on Deletion, we delete all related records)
	3. On delete set Null (on Deletion, related fields become Null)
3. **Updation** may cause violation
	1. On update no action
	2. On update Cascade (on Updation, we update all related records)
	3. On update set Null

# Related Notes

1. [[Database Management System]]
# References

1. 