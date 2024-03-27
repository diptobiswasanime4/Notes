Created: March-27-2024

Three-Schema Architecture separates the user applications from the physical storage.

The 3 levels are:

1. Internal level
2. Conceptual level
3. External Schema
## Internal Level

1. Describes the physical storage structure of the database
2. Describes complete details of data storage and access path, using low-level [[Data Model]]
## Conceptual Level

1. Hides details of Physical storage structure
2. Describes Entities, Data Types, Relationships, Constraints, etc.
## External Level

1. Describes the part of Database user is interested in, and hides rest of the database from the user group
2. Has a view for each user group
## Mapping

**Mapping** is the process of transforming requests and results across the 3 levels of Three Schema Architecture.

![[Three Schema Architecture excal.excalidraw]]
# Related Notes

1. [[Database Management System]]
# References

1. 