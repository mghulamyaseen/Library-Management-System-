Library Management System

1. BLUF

This is a simple Library Management System made in C++. It is used to add and delete books, register students, issue and return books, and search for books by title or ID.

2. Dependencies

- C++ Compiler (GCC or MinGW)
- Any C++ IDE (Code::Blocks or VS Code)
- Header files: "iostream", "string", "vector", "cctype"

3. Installation

1. Download or clone the project from GitHub.
2. Open the project folder.
3. Compile the program:

g++ -std=c++11 main.cpp -o library

4. Run the program:

./library

For Windows, run "library.exe".

4. Minimal Working Example

When the program runs, the following menu appears:

===== LIBRARY MANAGEMENT SYSTEM =====

1. Add Book
2. Delete Book
3. Display All Books
4. Register Student
5. Display All Students
6. Issue Book
7. Return Book
8. Search Book
0. Exit

Enter your choice:

Example:

Enter your choice: 1
Enter Book Title: C++ Programming
Enter Book Author: Bjarne Stroustrup

Book added successfully!
Book ID: 1001
