1. INTRODUCTION:
          The Library Management System is a simple console-based application developed using Python programming language. This project is designed for students and internship learning purposes. It helps in managing library books, issuing books to students, returning books, and calculating fines for late returns. The system stores all records in a JSON file, which allows data to be saved permanently.
2. OBJECTIVE OF THE PROJECT:
          The main objectives of this project are:
                • To understand basic Python programming concepts
                • To learn file handling using JSON
                • To implement a real-world library system
                • To perform date and time calculations
                • To develop a menu-driven application
3. TOOLS AND TECHNOLOGIES USED:
          • Programming Language: Python
          • Data Storage: JSON File
          • Modules Used: json, datetime
4. SYSTEM DESCRIPTION:
          The Library Management System allows the librarian to manage books in the library. It provides options to add, remove, issue, return books and display all book records.
5. WORKING OF THE SYSTEM:
          5.1 Add Book:
                The user enters the Book ID, Book Title, and Author Name. The book is added to the system if it does not already exist.
          5.2 Remove Book:
                The user enters the Book ID of the book to be removed. If the book exists, it is deleted from the system.
          5.3 Issue Book:
                The user enters the Book ID and Student Name. The book is issued for 7 days. Issue date and due date are generated automatically.
          5.4 Return Book:
                The system checks the due date when the book is returned. If the book is returned late, a fine of ■5 per day is calculated.
          5.5 Display Books:
                Displays all books with Book ID, Title, Author, and Status.
6. DATA STORAGE:
          All data is stored in a file named library_data.json. This ensures permanent storage of records.
7. ADVANTAGES:
          • Easy to use
          • Beginner-friendly
          • Real-world application
          • No database required
8. LIMITATIONS:
          • Console-based system
          • No graphical interface
          • Single user access
9. CONCLUSION:
          This Library Management System is a basic internship-level project. It helps students learn Python programming, file handling, and date management concepts.
