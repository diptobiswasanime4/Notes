Created: June-13-2024

**Relational Schema** is the definition of the DB. Informally the Headings

**Arity** is the number of fields of the DB table

**Cardinality** is the number of records of the DB table

**Candidate Key** is the minimal set of attributes that can differentiate the records uniquely (similar to [[Primary Key]] in [[SQL]]). Candidate Keys can be multiple fields but they cannot be same to same in 2 rows

**Primary Key** is any one Candidate Key whose value is not Null (Null is unknown or non-existent value). So Primary Key is a type of Candidate Key.

Atmost 1 Primary Key should be present for an RDBMS table

**Alternative Keys** are all Candidate Keys of the Relational Schema except Primary Key. So Alt Keys are also Candidate Keys

A Candidate Key with 1 attribute is called **Simple Candidate Key**. E.g. Employee_ID

A Candidate Key with atleast 2 attributes is called **Composite Candidate Key**. E.g. Acc No + IFSC Code

**Prime attribute** is an attribute that belongs to some CK of a Relational Schema. Nothing in common with PK

**Non-prime attribute** is an attribute that doesn't belong to CK

# Related Notes

1. [[Database Management System]]
# References

1. 