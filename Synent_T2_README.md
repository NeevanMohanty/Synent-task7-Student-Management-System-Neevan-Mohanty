# Synent-task7-Student-Management-System-Neevan-Mohanty
# Student Management System

## Project Description

The Student Management System is a command-line application developed using Python that helps manage student records efficiently. The system allows users to add, view, update, and delete student information while storing data permanently in a JSON file.

This project demonstrates the use of file handling, data storage, functions, and CRUD (Create, Read, Update, Delete) operations in Python.

## Features

* Add new student records
* View all student records
* Update existing student information
* Delete student records
* Store data permanently using JSON
* Menu-driven command-line interface
* Structured and organized data management

## Technologies Used

* Python 3.x
* JSON File Storage
* Command Line Interface (CLI)
* File Handling

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/student-management-system.git
```

### 2. Navigate to the Project Directory

```bash
cd student-management-system
```

### 3. Run the Python File

```bash
python student_management.py
```

## Example Output

```text
===== STUDENT MANAGEMENT SYSTEM =====

1. Add Student
2. View Students
3. Update Student
4. Delete Student
5. Exit

Enter your choice: 1

Enter Student ID: 2424
Enter Name: Michael
Enter Age: 20
Enter Course: BCA

Student added successfully!
```

### Viewing Student Records

```text
----- Student Records -----

ID     : 2424
Name   : Michael
Age    : 20
Course : BCA

----------------------------
```

## Concepts Used

* Functions
* Lists
* Dictionaries
* JSON Handling
* File Operations
* While Loops
* Conditional Statements (if-elif-else)
* CRUD Operations
* User Input Handling

## Program Workflow

```text
Start
  |
  v
Load Student Data
  |
  v
Display Menu
  |
  v
User Chooses Option
  |
  |-- Add Student
  |-- View Students
  |-- Update Student
  |-- Delete Student
  |-- Exit
  |
  v
Save Changes
  |
  v
Repeat Until Exit
  |
  v
End
```

## Data Storage Format

Student records are stored in a JSON file.

Example:

```json
[
    {
        "ID": "101",
        "Name": "John",
        "Age": "20",
        "Course": "BCA"
    },
    {
        "ID": "102",
        "Name": "Alice",
        "Age": "21",
        "Course": "B.Tech"
    }
]
```

## Purpose of the Project

This project was developed to:

* Learn file handling and data persistence
* Understand CRUD operations
* Practice working with JSON files
* Build a structured management system
* Improve problem-solving and programming skills

## Future Improvements

* Search students by ID or name
* Validate duplicate student IDs
* Export records to CSV format
* Add student grades and attendance tracking
* Implement password-protected access
* Create a graphical user interface (GUI) version
* Integrate a database such as SQLite or MySQL
