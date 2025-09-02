Library Management System (C++)

This is a console-based Library Management System written in C++ using Turbo C++ style headers such as <conio.h> and binary file handling. It helps manage books and students, including issuing and depositing books, modifying records, and viewing reports.

Features

Book Management

Add new books

View all books or a specific book

Modify book details

Delete book records

Student Management

Add new students

View all students or a specific student

Modify student details

Delete student records

Book Issue and Deposit

Issue a book to a student (only one at a time)

Deposit a book with fine calculation (₹1 per day after 15 days)

File Structure

The system uses binary file handling to store records:

book.dat stores book records

student.dat stores student records
Temporary files like temp.dat are used during deletion.

Tech Stack

Language: C++
Compiler: Turbo C++ (Borland) or any compiler supporting <conio.h>
File Handling: Binary file operations using fstream

How to Run

Copy the code into a file named library.cpp.

Compile the program in Turbo C++ or a compatible IDE.

Run the program and use the Main Menu options:

MAIN MENU
1. Book Issue
2. Book Deposit
3. Administrator Menu
4. Exit

Administrator Menu
1. Create Student Record
2. Display All Student Records
3. Display Specific Student Record
4. Modify Student Record
5. Delete Student Record
6. Create Book
7. Display All Books
8. Display Specific Book
9. Modify Book Record
10. Delete Book Record
11. Back to Main Menu
