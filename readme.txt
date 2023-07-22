# Bookstore Database Manager

This is a Python-based graphical user interface (GUI) application for managing a bookstore database. The app allows users to perform various operations on the collection of books, such as viewing all books, searching, adding new entries, updating existing book details, and deleting selected books.

## Requirements

- Python 3.x
- Tkinter (included in Python standard library)

## How to Use

1. Make sure you have Python 3.x installed on your system.

2. Clone or download this repository to your local machine.

3. Run the `bookstore_app.py` script to start the application.

4. The main window will open, displaying a list of books (if any) in the database.

5. Use the provided entry fields and buttons to perform different operations:
   - View all books
   - Search for specific books
   - Add a new book entry
   - Update details of a selected book
   - Delete a book from the database

6. To view or modify book details, click on a book entry in the list to select it.

7. When done, close the application using the "Close" button.

## Dependencies

This app uses the standard Python library for GUI (Tkinter) and a backend module (`backend.py`) that handles the interaction with the database. No additional dependencies are required.

## Backend Module

The `backend.py` module provides the necessary functions to interact with the database. Functions include view(), search(), insert(), delete(), and update().

## Contributing

If you want to contribute to this project, feel free to submit a pull request. Any improvements or bug fixes are highly appreciated.

