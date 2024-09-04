## Exercise 1:
Create a table called `Students` with the following fields:
- `student_id` (integer, primary key)
- `first_name` (string, 50 characters)
- `last_name` (string, 50 characters)
- `dob` (date)
- `email` (string, 100 characters, should be unique)
- `enrollment_date` (date)

## Exercise 2:
Create a table called `Courses` with the following fields:
- `course_id` (integer, primary key)
- `course_name` (string, 100 characters)
- `credits` (integer)
- `department` (string, 50 characters)

## Exercise 3:
Create a table called `Enrollments` to store which students are enrolled in which courses. The fields should be:
- `enrollment_id` (integer, primary key)
- `student_id` (integer, foreign key referencing `Students`)
- `course_id` (integer, foreign key referencing `Courses`)
- `enrollment_date` (date)
- `grade` (string, 2 characters)

## Exercise 4:
Create a table called `Instructors` with the following fields:
- `instructor_id` (integer, primary key)
- `first_name` (string, 50 characters)
- `last_name` (string, 50 characters)
- `email` (string, 100 characters, should be unique)
- `hire_date` (date)

## Exercise 5:
Create a table called `Departments` with the following fields:
- `department_id` (integer, primary key)
- `department_name` (string, 100 characters)
- `head_of_department` (integer, foreign key referencing `Instructors`)
- `budget` (decimal with two decimal places)
