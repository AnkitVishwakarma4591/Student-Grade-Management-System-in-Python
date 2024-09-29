# Student Management System
## Description
This is a Python-based Student Management System designed to store and display student information,
including subjects, marks, and grades. The program allows you to input student details,
including the name, student ID, number of subjects, and individual subjects with their respective marks.
The system then calculates the grades for each subject based on predefined criteria.

## Features
🔸Collect and store student information (name, student ID).
🔸Accept a dynamic number of subjects and their respective marks.
🔸Calculate grades based on marks (using a grading scale: A, B, C, D).
🔸Display a summary of the student's subjects, marks, and grades.

## You will be prompted to enter:
🔹Student name.
🔹Student ID.
🔹Number of subjects.
🔹Subject names and marks for each subject.

# Usage
## Grading Criteria
🔸Grade A: Marks >= 90
🔸Grade B: 75 <= Marks < 90
🔸Grade C: 60 <= Marks < 75
🔸Grade D: Marks < 60

# Code Explanation
🔹Function StudentDetails(name, st_id, n): This function takes the student's name, student ID,
   and number of subjects as input and creates a dictionary to store student information.
🔹Input Loop for Subjects and Marks: The function then collects the names and marks of the subjects.
🔹Grade Calculation Loop: The script assigns grades based on the marks obtained.
🔹Output: The student information, along with subjects, marks, and grades, is printed to the console.
