# Python for Data Science - Weekly Assignments

This repository contains weekly assignments for the Python for Data Science course. Each branch corresponds to a specific week's assignment, focusing on key Python and data science concepts.

<br>
<be>

## Table of Contents

<br>


- [Week_1](https://github.com/VictorSnorri/PythonForDataScience/tree/Assignment_1): Python - Basics
- [Week_2](https://github.com/VictorSnorri/PythonForDatascience/tree/Assignment_2): Python - Object-Oriented Programming
- [Week_3](https://github.com/VictorSnorri/PythonForDatascience/tree/Assignment_3): Pyhton - Registration Class
- [Week_4](https://github.com/VictorSnorri/PythonForDatascience/tree/Assignment_4): Python - Basic Libraries and File Management
- [Week_5](https://github.com/VictorSnorri/PythonForDatascience/tree/Assignment_5):
  
<br>
<br>


  
## Week 1) - Python - Basics
  
### Python - Syntax and Variables
- **Exercise 1: Print a Greeting**
- **Exercise 2: Basic Arithmetic**
- **Exercise 3: String Manipulation**

###  Python - Lists and Dictionaries

- **Exercise 4: Lists**
- **Exercise 5: Dictionaries**

###  Python - Tuples and Sets

- **Exercise 6: Tuples**
- **Exercise 7: Sets**

###  Python - Control Flow

- **Exercise 8: Conditional Statements**
- **Exercise 9: For Loop**
- **Exercise 10: While Loop**
- **Exercise 11: Match Statement (Python 3.10+)**

### Python - Functions

- **Exercise 12: Define a Function**
- **Exercise 13: Function with Return Value**
- **Exercise 14: Function with Default Parameters**

### Python - Combining All We Learned

- **Exercise 15: List Comprehension**
- **Exercise 16: Nested Data Structures**
- **Exercise 17: Simple Calculator**

# Week 2) - Python - Functions and Data Filtering

### Exercises

- **Exercise 1:** FizzBuzz
- **Exercise 2:** Basic Data Filtering
- **Exercise 3:** Simple To-Do List
- **Exercise 4:** Temperature Converter

<be>
<be>
  
# week 3) - Python - Object-Oriented Programming

### Exercise 1: Course Class
**Description:** Create a `Course` class where each course has a name, a description, and a list of enrolled students.

**Methods:**
- `add_student(student)`: Adds a student to the course.
- `remove_student(student)`: Removes a student from the course.
- `show_all()`: Displays all students in the course.

### Exercise 2: Student Class
**Description:** Create a `Student` class where each student has a name, ID number, address, and a list of enrolled courses.

**Methods:**
- `enroll(course)`: Enrolls the student in a course.
- `drop(course)`: Drops the student from a course.
- `show_courses()`: Shows all registered courses.

<be>
<be>


### Exercise 3: Registration Class
**Description:** Create a `Registration` class that manages courses and students. 

**Methods:**
- `add_student(student)`: Adds a student to the registration system.
- `add_course(course)`: Adds a course to the registration system.
- `enroll_student_in_course(student, course)`: Enrolls a student in a course.
- `drop_course(student, course)`: Drops a student from a course.
- `show_enrolled_courses()`: Shows all courses in the registration system.
- `show_students()`: Shows all students in the registration system.

### Exercise 4: Adding Grades and GPA Calculation
**Description:** Extend the `Student` class to manage grades for each course and calculate the GPA.

**Methods:**
- `add_grade(course, grade)`: Adds a grade for a student in a specific course.
- `GPA()`: Calculates the student's GPA based on enrolled courses and grades.


<br>
<br>
<be>


### Exercise 4: Adding Grades and GPA Calculation
**Description:** Extend the `Student` class to manage grades for each course and calculate the GPA.

**Methods:**
- `add_grade(course, grade)`: Adds a grade for a student in a specific course.
- `GPA()`: Calculates the student's GPA based on enrolled courses and grades.


<br>
<br>
<be>

# Week 4) - Python - Basic Libraries and File Management

### Exercise 1: Counting Files in a Directory
- **Description:** Count the total number of files in a specified directory.
- **Steps:**
  - `Access the directory`: Navigate to the target directory.
  - `Count files`: Count the number of files within the directory.
  - `Display total`: Output the total file count.

### Exercise 2: Filtering Files by Naming Convention
- **Description:** Count the number of files that follow a specific naming convention:
  - **Naming Convention:** `{DATE}_{TIME}_SN{SATELLITE_NUMBER}_QUICKVIEW_VISUAL_{VERSION}_{UNIQUE_REGION}.txt`
  - **Components:** DATE (YYYYMMDD), TIME (HHMMSS), SATELLITE_NUMBER, VERSION, UNIQUE_REGION.
- **Steps:**
  - `Define convention`: Set the naming convention using wildcards.
  - `Filter files`: Select files that match the naming pattern.
  - `Count and display`: Count and output the total matching files.

### Exercise 3: Counting Annotations by Year and Month
- **Description:** Extract and count the number of annotation files per year and month. Identify which month has the highest count of annotations.
- **Steps:**
  - `Parse year and month`: Extract year and month from filenames.
  - `Count annotations`: Tally annotations for each year and month.
  - `Identify peak month`: Display counts and highlight the month with the most annotations.

### Exercise 4: Creating Subfolders by Month
- **Description:** Create a new folder structure based on months and move annotations into corresponding folders based on their date.
- **Steps:**
  - `Create parent folder`: Make a new folder for organizing annotations.
  - `Add monthly subfolders`: Create subfolders for each unique month.
  - `Organize files`: Move files into the respective monthly subfolders.

### Exercise 5: Sorting Annotations by Date
- **Description:** Print all annotation files in descending order based on date (most recent to oldest).
- **Steps:**
  - `Extract dates`: Parse dates from file names.
  - `Sort files`: Order files by date in descending sequence.
  - `Display sorted list`: Output files from the most recent to the oldest.

### Exercise 6: Satellite Analysis
- **Description:** Analyze satellite information:
  - Count the number of unique satellites.
  - Count the number of annotations per satellite.
  - Identify which satellite was used in the most recent annotation file.
- **Steps:**
  - `Extract satellite numbers`: Parse satellite identifiers from file names.
  - `Count occurrences`: Track the number of annotations for each satellite.
  - `Identify recent satellite`: Display the satellite from the most recent file.

### Exercise 7: Unique Region Count
- **Description:** Count the number of unique regions based on file names and display the total.
- **Steps:**
  - `Extract regions`: Pull unique region identifiers from file names.
  - `Count unique regions`: Tally and output the total number of unique regions.


<br>
<br>
<be>



