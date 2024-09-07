Project Overview: Student Grade Calculator
1. Introduction
The Student Grade Calculator is a Python-based application designed to assist educators and students in managing and tracking academic performance. It allows users to input grades for various subjects or assignments, calculates average grades, and provides insights through letter grades and GPA. This tool simplifies the process of monitoring academic progress and helps in making data-driven decisions about student performance.

2. Objectives
Grade Management: Input, store, and manage grades for different subjects or assignments.
Average Calculation: Compute the average grade across all subjects or assignments.
Grade Conversion: Convert numeric averages into letter grades.
GPA Calculation: Calculate the Grade Point Average (GPA) based on average grades.
Data Display: Provide a summary of overall performance and grades by subject.
3. Features
Add Grades: Users can input grades for various subjects. If grades for a subject already exist, they can be appended.
Calculate Average: The program computes the average grade based on all entered grades.
Letter Grade Conversion: Converts the average grade into a letter grade according to standard grading scales.
GPA Calculation: Computes the GPA based on the average grade using a predefined scale.
Display Information: Shows the average grade, letter grade, GPA, and a detailed list of grades by subject.
4. Technical Details
Programming Language: Python
Data Storage: Grades are stored in memory using a dictionary where each key is a subject and the value is a list of grades.
User Interface: Command-line interface (CLI) for simplicity and ease of use.
5. Design
5.1 Class Structure
GradeManager Class
Attributes:
grades: Dictionary to store subjects and their associated grades.
Methods:
add_grade(subject, grade): Adds or appends a grade for a specific subject.
calculate_average(): Computes the average grade from all subjects.
calculate_letter_grade(average): Converts the average grade to a letter grade.
calculate_gpa(average): Calculates the GPA based on the average grade.
display_info(): Displays the average grade, letter grade, GPA, and detailed grades by subject.
5.2 Main Program Logic
User Menu:
Add Grade: Allows users to input a subject and grade.
Display Information: Shows computed results and detailed grade data.
Exit: Terminates the application.
6. Usage
Add Grades:

Select the option to add a grade.
Enter the subject and grade.
The grade is stored and can be viewed later.
Display Information:

Select the option to display grades.
The application calculates and shows the average grade, letter grade, GPA, and lists grades for each subject.
Exit:

Terminates the program.
