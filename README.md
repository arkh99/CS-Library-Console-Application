# CS-Library-Console-Application
This is a simple library management system implemented as a C# console application. The application allows users to view, add, check out, and return books from a library.

Key Points and Features
Console Menu Interface:

The application provides a simple console-based menu for interacting with the library.
Users can choose to view all books, add a new book, check out a book, return a book, or exit the application.
Book Management:

The Book class represents a book with properties such as Title, Author, Year, and IsCheckedOut.
Methods in the Library class handle adding books, listing all books, checking out books, and returning books.
Data Initialization:

The Helper class provides a static method GetAvailableBooks to initialize the library with a predefined list of books.
Error Handling:

The application includes error handling for various scenarios such as trying to check out a non-existent book, returning a book that is not checked out, and adding a duplicate book.
Basic User Input Handling:

The GetResponse method is used to get user input from the console, ensuring that the input is not null or whitespace.
Techniques and Concepts
Object-Oriented Programming (OOP):

Encapsulation: The Book and Library classes encapsulate the data and behaviors related to books and library operations.
Constructor Initialization: Use of constructors to initialize objects.
Collections:

Use of List<Book> to manage the collection of books in the library.
LINQ:

Use of LINQ methods like FirstOrDefault and Exists to search and manipulate the book list.
Exception Handling:

Use of try-catch blocks to handle exceptions and provide user-friendly error messages.
User Input Validation:

Validating user input to ensure that only valid data is processed by the application.
Project Structure
Program.cs: Contains the main entry point and user interaction logic.
Book.cs: Defines the Book class with properties and methods related to a book.
Helper.cs: Provides helper methods for initializing data.
Library.cs: Defines the Library class with methods for managing the library's book collection.

This project demonstrates fundamental concepts in C# programming, including object-oriented design, collections, exception handling, and user input validation in a console application.
