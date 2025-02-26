# Online-Book-Store-
"Developed an **Online Book Store SQL Project** to manage and streamline book inventory, customer orders, and sales data. Designed and implemented a relational database schema, wrote complex SQL queries, and optimized database performance to ensure seamless data retrieval and efficient operations.

# Online Book Store SQL Project

This project is a database management system for an **Online Book Store**, designed to efficiently manage book inventory, customer orders, and sales data. It includes a relational database schema, SQL queries, and optimized database operations.

## Features
- **Database Schema**: Designed to store book details, customer information, orders, and sales data.
- **SQL Queries**: Includes complex queries for retrieving book details, generating sales reports, and managing inventory.
- **Optimized Performance**: Ensures fast and efficient data retrieval and storage.

## Technologies Used
- **Database**: MySQL
- **Tools**: MySQL Workbench, Git, GitHub

## Database Schema
The database consists of the following tables:
- `Books`: Stores book details (title, author, price, stock).
- `Customers`: Stores customer information (name, email, address).
- `Orders`: Manages customer orders (order ID, customer ID, book ID, quantity, order date).
- `Sales`: Tracks sales data (sale ID, book ID, customer ID, sale date, total amount).

## SQL Queries Examples
1. Retrieve all books in stock:
   ```sql
   SELECT * FROM Books WHERE stock > 0;
