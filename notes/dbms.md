# DBMS Notes

## Keys
- A primary key uniquely identifies each row in a table and cannot be NULL.
- A foreign key is a column that refers to the primary key of another table.
- A candidate key is any column set that could be chosen as the primary key.

## Normalisation
- 1NF: every column holds a single (atomic) value.
- 2NF: 1NF and no non-key column depends on only part of a composite key.
- 3NF: 2NF and no transitive dependency between non-key columns.
- A foreign key can be NULL if the relationship is optional.
