# DATA345_Books_Database
Book Ratings Management System

This project is a Python-based system for managing books, users, and ratings with database integration. It provides functionality to add, retrieve, and manage data using SQL for books, users, and their ratings, along with a set of automated tests to ensure reliability.

Features:

Book Management

 - Add and retrieve book information.

 - Query books based on specific criteria.

User Management

 - Add and manage user profiles.

 - Retrieve user information and activity.

Ratings System

 - Allow users to rate books.

 - Retrieve and analyze ratings for books and users.

Database Integration

 - Uses connect.py for establishing connections with the database.

 - Query files (book_queries.py, users_queries.py, ratings_queries.py) handle all database operations.

Testing

 - Automated tests (test_book.py, test_user.py, test_rating.py) ensure the correctness of data handling and queries against the gold testfiles.

Technologies Used

 - Python 3

 - PostgreSQL

 - Pytest for automated testing
