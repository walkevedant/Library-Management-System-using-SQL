# Library-Management-System-using-SQL
Description:
The Library Management System is a database system designed to manage the details of books, library branches, members, and borrowing records in an audio-visual library. The system allows librarians to efficiently track and organize the library's collection and handle member borrowing activities.

Tables:

book_details: This table stores the details of books, including the book ID, ISBN, title, author, book location, and branch ID where the book is located.

library_details: This table contains information about library branches, including the library ID, branch name, and address.

member_details: This table holds the details of library members, including their ID, name, username, and password.

records: This table maintains the borrowing records of books, including the book ID, member ID, library ID, issuing date, return date, and fine due. It also includes foreign key constraints to link the records with the book, member, and library details.

authors: This table stores information about authors, including their name, author ID, number of books written, and publisher ID. It is linked to the book_details table through a foreign key relationship based on the author's name.

Publishers: This table contains details of book publishers, including the publisher ID and name.

Functionality:

The system allows users to retrieve the location of a book based on its title.
Users can search for books written by a specific author.
Librarians can find the issuing date of a book by providing its book ID.
The system provides information about the library branch where a book is located based on the book's ID.
Users can check the count of available books for a specific ISBN number.
Librarians can find the fine due for a member by using their member ID.
The Library Management System aims to streamline library operations, improve book tracking, and enhance member services. It provides a centralized database to store and retrieve information related to books, library branches, members, and borrowing records, enabling efficient management of the library's resources.
