# Normalization Notes

The database design follows normalization principles.

## 1NF
All columns contain atomic values.

## 2NF
Partial dependency is removed by separating students, courses, and enrollments tables.

## 3NF
Transitive dependency is reduced using separate tables and foreign keys.

## Redundancy Reduction
Repeated student and course data is avoided using enrollments table.
