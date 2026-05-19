# Keys and Relationships

## Primary Keys
- student_id in students table
- course_id in courses table
- enrollment_id in enrollments table

## Foreign Keys
- student_id in enrollments references students(student_id)
- course_id in enrollments references courses(course_id)

## Relationships
- One student can enroll in many courses
- One course can contain many students
- Enrollments table creates many-to-many relationship
