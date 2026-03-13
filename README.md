# Student Management System (DBMS Project)

This project implements a **Student Management System** using MySQL.

## Database Name
student_management

## Tables
- Student
- Faculty
- Course
- Enrollment

## Features
- Database creation
- Table relationships using foreign keys
- Data insertion
- SQL queries using JOIN

## Example Query

```sql
SELECT s.name, c.course_name
FROM student s
JOIN enrollment e ON s.student_id = e.student_id
JOIN course c ON e.course_id = c.course_id;
