Student, Teacher and Course Management System

Project Overview

This is a simple MySQL database project that manages information about students, teachers, and courses.

The project demonstrates basic SQL concepts such as creating tables, inserting records, and retrieving data using SELECT queries.

Tables

Student Table

The student table stores student information.

Columns:

studentId – Unique student ID
name – Student name
marks – Student marks

Sample students:

Rahul – 56 marks
Cattt – 59 marks
Meoww – 58 marks
Teacher Table

The teacher table stores teacher information.

Columns:

teacherId – Unique teacher ID
name – Teacher name
subject – Subject taught by the teacher

Sample teachers:

Asha – Math
Ravi – Science
Course Table

The course table stores information about available courses.

Columns:

courseId – Unique course ID
courseName – Name of the course
fee – Course fee

Sample courses:

Java – 5000
SQL – 3000

SQL Operations

The project uses INSERT statements to add student, teacher, and course records.

SELECT statements are used to display the stored information.

Example:

SELECT * FROM student;

SELECT * FROM teacher;

SELECT * FROM course;

Technologies Used

MySQL
SQL
OneCompiler

Project Objective

The main objective of this project is to practice basic SQL commands and understand how data can be stored in multiple tables.

This project is suitable for beginners learning MySQL and DBMS concepts.

Future Improvements

The project can be improved by adding:

Primary keys
Foreign keys
Student-course enrollment
Teacher-course relationships
Student attendance
Student results
Course registration
More SQL queries and JOIN operations

Conclusion

This project provides a basic example of managing student, teacher, and course information using MySQL. It is a beginner-friendly project for practicing database creation, data insertion, and data retrieval.
