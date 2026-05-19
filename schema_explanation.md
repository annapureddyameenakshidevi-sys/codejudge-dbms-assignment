# Schema Explanation

## Students Table
Stores student details such as student ID, student name, and email.

## Courses Table
Stores course details and course names.

## Enrollments Table
Connects students and courses using foreign keys.

student_id references students table.
course_id references courses table.
