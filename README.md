#Library Management System
This Java program is a basic console-based Library Management System. It allows users to manage a collection of books by adding new books, viewing available books, issuing books to users, and returning issued books.

Features
Add Book: Add a new book to the library by providing the title and author.
View Books: Display a list of all available (unissued) books in the library.
Issue Book: Issue a book by its title. The book will then be marked as unavailable until returned.
Return Book: Return a previously issued book, making it available for others.
Exit Program: Exits the library management system.
Usage
To use this program, follow these steps:

Choose 1 to add a book.
Choose 2 to view available books.
Choose 3 to issue a book by its title.
Choose 4 to return a book by its title.
Choose 5 to exit the system.
Code Structure
Book Class: Represents a single book, with properties for the title, author, and issued status.
Library Class: Manages a collection of books and provides methods to add, view, issue, and return books.
LibraryManagementSystem (Main Class): Contains the main method and handles user interactions.
Example
plaintext
Copy code
Library Management System
1. Add Book
2. View Books
3. Issue Book
4. Return Book
5. Exit
Enter your choice: 1

Enter book title: Java Basics
Enter book author: John Doe
Book added: Java Basics
Requirements
Java Development Kit (JDK) 8 or higher.
Author
This code was created as a basic example for managing a library. Feel free to enhance it by adding features such as saving data to a file or integrating a graphical user interface (GUI).