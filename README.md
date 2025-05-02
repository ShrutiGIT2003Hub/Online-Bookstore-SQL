This project focuses on developing a relational database system for an Online Bookstore using PostgreSQL. The aim is to efficiently store, manage, and analyze data related to books, customers, and their orders. The system helps track inventory, customer details, and order transactions.

The database consists of three main tables:

Books1: Stores information about each book such as title, author, genre, published year, price, and stock.

Customers: Contains customer data like name, email, phone number, city, and country.

Orders: Records transactions including customer ID, book ID, order date, quantity ordered, and total amount.

The project uses SQL queries to perform both basic operations and advanced analytics. Basic queries help retrieve books by genre, find customers from specific regions, calculate stock levels, and fetch orders in a date range. Advanced queries provide insights such as total books sold by genre or author, highest-spending customers, most ordered books, and stock remaining after fulfilling orders.

Key Highlights:
Joined multiple tables using foreign key relationships.

Used SUM, COUNT, AVG, DISTINCT, ORDER BY, GROUP BY, and HAVING for aggregation and filtering.

Loaded data using CSV files for practical data handling.

Designed queries to assist with business decisions like inventory tracking and customer analysis.

Technologies Used:
PostgreSQL for database and query processing.

pgAdmin (optional) for user-friendly database interaction.

This project demonstrates real-world application of SQL in e-commerce-style inventory and order management, providing a strong foundation in data handling and analytical thinking.
