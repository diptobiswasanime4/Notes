Created: June-13-2024

1. Candidate Key
	1. Simple CK
	2. Composite CK
2. Primary Key
3. Alt Key
4. Super Key

**Candidate Key** is the minimal set of attributes that can differentiate the records uniquely (similar to [[Primary Key]] in [[SQL]]). Candidate Keys can be multiple fields but they cannot be same to same in 2 rows

**Primary Key** is any one Candidate Key whose value is not Null (Null is unknown or non-existent value). So Primary Key is a type of Candidate Key.

Atmost 1 Primary Key should be present for an RDBMS table

**Alternative Keys** are all Candidate Keys of the Relational Schema except Primary Key. So Alt Keys are also Candidate Keys. Alt Keys can be Nulls

A Candidate Key with 1 attribute is called **Simple Candidate Key**. E.g. Employee_ID

A Candidate Key with atleast 2 attributes is called **Composite Candidate Key**. E.g. Acc No + IFSC Code

**Prime attribute** is an attribute that belongs to some CK of a Relational Schema. Nothing in common with PK

**Non-prime attribute** is an attribute that doesn't belong to CK

**Super Key** is set of attributes that can differentiate records uniquely. SK is not minimal, unlike CK which is minimal. If ABC is an SK, AB can also be an SK (Superset of CK is an SK, CK is nothing but minimal SK)

**Foreign Key** is the PK of another table being referred to in the current table. FK is used to create relationships among tables. FK is defined over a relation. FKs can also be within the same table

![[Types of Keys excal.excalidraw]]

# Related Notes

1. [[Database Management System]]
# References

1. 