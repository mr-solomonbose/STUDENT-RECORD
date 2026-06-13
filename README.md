STUDENT RECORD MANAGEMENT SYSTEM
A Modular Console-Based Student Record System in C using Singly Linked List

Overview
The Student Record Management System is a complete menu-driven console application developed in C. It uses a singly linked list for dynamic storage of student records and provides file persistence through a binary file student.dat.
The program is built as a modular project with separate source files for each major operation. When compiled, it produces an executable named student. It supports full CRUD operations along with advanced features like auto roll number generation, sorting, reversing, and initialization of the database.

Features

* Add Student (A): Dynamically add new records with auto-generated unique roll numbers (smallest positive available).
* Delete Student (D): Delete by Roll Number or by Name (handles duplicate names by showing all matches).
* Show Records (S): Display all student records in a clean tabular format.
* Modify Student (M): Search by Roll No / Name / Percentage and modify Name or Percentage.
* Sort Records (T): Sort the list by Name or by Percentage.
* Initialize (I): Delete all records from the linked list.
* Reverse List (R): Reverse the order of the entire linked list.
* Save (W): Save the current list to student.dat.
* Exit (E): Option to save before exiting or exit without saving.
* Data Persistence: Automatically loads records from student.dat on startup.


Technologies Used

* C Programming Language
* Singly Linked List (Dynamic Memory Allocation)
* File Handling (fopen, fread, fwrite, fclose)
* Modular Programming (Multiple .c files + header)
* Standard C Libraries (stdio.h, stdlib.h, string.h)


Key Concepts Implemented

Dynamic memory management using malloc() and free()
Singly Linked List operations (insertion, deletion, traversal, reversal, sorting)
Automatic unique Roll Number generation
File I/O for data persistence (binary format)
Menu-driven interface with sub-menus
Handling duplicate names during search/delete/modify
Modular code organization


Project Structure
textSTUDENT-RECORD/
├── main.c         # Main program with menu loop
├── add.c          # Student addition logic
├── delete.c       # Delete functionality
├── delall.c       # Delete all records (Initialize)
├── modify.c       # Modify student records
├── load.c         # Load from student.dat
├── exit.c         # Exit and save handling
├── header.h       # Common structures and function declarations
├── makefile       # Build automation
├── student.dat    # Database file (generated)
└── README.md

The Application Supports the Following Operations

* Add Student Record
* Delete Student Record (by Roll No or Name)
* Display All Records (Tabular Format)
* Modify Student Record (by Roll No / Name / Percentage)
* Sort Records (by Name or Percentage)
* Reverse the List
* Initialize / Clear all records
* Save records to file
* Load records from file on startup
* Save & Exit / Exit without saving


Learning Outcomes
This project helped in understanding:

* Implementation of Singly Linked Lists from scratch
* Dynamic memory allocation and deallocation
* File handling for binary data persistence
* Modular programming and code organization
* Menu-driven application design with sub-menus
* Searching, sorting, and reversing linked lists
* Handling real-world edge cases (duplicate names, auto ID generation)


Future Enhancements

* Password-based authentication
* Search and filter options
* Grade/GPA calculation
* Export to CSV or PDF report
* Student attendance module
