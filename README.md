# Flask Book Collection App

This is a simple Flask web application for managing a collection of books.

## Requirements

- Python 3.12
- Flask
- Flask-SQLAlchemy
- SQLite

## Installation

1. Clone this repository.
2. Install the required packages using pip:

    ```bash
    pip install flask flask_sqlalchemy
    ```

3. Run the Flask application:

    ```bash
    python main.py
    ```

## Usage

- Navigate to [http://localhost:5000/](http://localhost:5000/) in your web browser to view the list of books.
- You can add, edit, and delete books using the provided functionality.

## Code Overview

- `main.py`: Contains the main Flask application code.
- `templates/`: Contains HTML templates for the application views.
- `books-collection.db`: SQLite database file for storing book data.

## Features

- **View all books**: Displays a list of all books in the collection.
- **Add a book**: Allows users to add a new book to the collection.
- **Edit a book**: Enables users to edit the details of an existing book.
- **Delete a book**: Allows users to remove a book from the collection.

