# Library Management System

## Introduction
The Library Management System is a Python-based application that provides a user-friendly interface for managing a library's operations. It utilizes the SQLite database for storing and retrieving information about books, borrowers, and library transactions. The graphical user interface (GUI) is developed using the Tkinter library.

## Features
- **Book Management:** Add, update, and delete books in the library.
- **Borrower Management:** Manage borrower information, including adding, updating, and deleting borrower records.
- **Book Borrowing:** Allow borrowers to borrow books from the library and keep track of the due dates.
- **Book Return:** Enable borrowers to return books, updating the availability status and due dates accordingly.
- **Search Functionality:** Search for books by title, author, or ISBN.
- **Fine Calculation:** Calculate and manage fines for late book returns.
- **Email Notifications (Optional):** Send email notifications to borrowers for overdue books and outstanding fines. *Note: To use this feature, please update the email and API key in the code.*

## Prerequisites
To run the Library Management System, you need to have the following software installed on your system:
- Python 3 (https://www.python.org/downloads/)
- Tkinter library (Usually comes bundled with Python)
- SQLite (https://www.sqlite.org/download.html)

## Installation
1. Clone the repository or download the source code from GitHub.
2. Open a terminal or command prompt and navigate to the project directory.
3. Create a virtual environment (optional but recommended) using the following command:
   ```bash
   python3 -m venv env
