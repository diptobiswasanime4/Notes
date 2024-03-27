Created: March-27-2024

DBMS languages can be classified into 4 types:

1. [[Data Definition Language (DDL)]]
2. [[Storage Definition Language (SDL)]]
3. [[View Definition Language (VDL)]]
4. [[Data Manipulation Language (DML)]]

In DBMS, where no strict separation of levels is maintained, [[Data Definition Language (DDL)]] is used to define Internal and Conceptual Schemas.

In DBMS, where separation of levels is clear, [[Data Definition Language (DDL)]] is used to specify Conceptual Schema, and [[Storage Definition Language (SDL)]] is used to specify Internal Schema.

For a true [[Three-Schema Architecture]], [[View Definition Language (VDL)]] is used to specify user views and their mappings to the Conceptual Schema.

[[Data Manipulation Language (DML)]] is used for manipulation of [[Data]] in the Database. Example - [[SQL]]
## Types of Data Manipulation Languages (DML)

1. High-level (non-procedural DML)
	1. Used to specify complex Database operations in a concise manner
	2. Also called set-at-a-time DML, because it can retrieve multiple-records in a single DML statement
2. Low-level (procedural DML)
	1. Embedded in a General purpose [[Programming Language]]
	2. Also called record-at-a-time DML
# Related Notes

1. [[Database Management System]]
2. [[Three-Schema Architecture]]
# References

1. 