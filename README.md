Introduction
The Library Management System (LMS) is a software application designed to manage the operations of a library. It allows users to add, display, search, issue, and return books efficiently. This report outlines the features, functionalities, and implementation details of the LMS developed in C++.

Features
The Library Management System includes the following features:

Add Book: Users can add new books to the library by providing the book title and author.
Display Books: Users can view a list of all available books in the library.
Search Book: Users can search for a specific book by its title.
Issue Book: Users can issue a book by providing the book title, author, and date of issuance.
Return Book: Users can return a book and check if it was returned on time to avoid fines.
Exit: Users can exit the application.
Implementation
The LMS is implemented in C++ and consists of the following components:

1. Data Structures
An array of strings is used to store the titles of the books.
An integer variable bookCount is used to keep track of the number of books in the library.
2. Functions
The system is organized into several functions, each responsible for a specific task:

addBook: This function allows the user to add a new book to the library. It checks if the library is full before adding the book.

displayBooks: This function displays all the books currently available in the library. If no books are available, it informs the user.

searchBook: This function allows the user to search for a book by its title. It informs the user if the book is found or not.

issueBook: This function allows the user to issue a book. It prompts the user for the book title, author, and date of issuance. It also provides a reminder to return the book on time.

returnBook: This function allows the user to return a book. It checks if the book being returned matches the one issued and calculates if the return is on time or if a fine is applicable.

3. User Interface
The user interface is text-based and provides a menu-driven approach for users to interact with the system. The menu options are displayed in a loop until the user chooses to exit.

4. Error Handling
The system includes basic error handling for invalid menu choices and checks for the library's capacity when adding books.
