# Student Management System

A menu-driven Python program that manages student records using a list of dictionaries. Each record stores a student's ID, Name, Age, Course, and Marks.

## Features

1.Add Student — enter a new student's details and add them to the records.

2.View All Students — display every stored student record.

3.Search Student — look up a student by ID or Name (case-insensitive).

4.Update Student — edit an existing student's details by ID; leaving a field blank keeps its current value.

5.Delete Student — remove a student record by ID.

6.Exit — end the program

## How to Run
You'll see a numbered menu (1–6). Enter the number for the action you want, and follow the prompts.

## Design

The program stores all records in a single list of dictionaries (`students`), where each dictionary represents one student. Each menu option is handled by its own function:

- `add_student()`
- `view_students()`
- `search_student()`
- `update_student()`
- `delete_student()`

The `main()` function runs a loop that displays the menu and calls the matching function based on user input, continuing until the user chooses to exit.

## Author

Written and tested by Mehpreet.
