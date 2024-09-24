# Little Lemon Customer Orders Project

This repository contains the files and scripts used for managing and querying the **Little Lemon** database. The project demonstrates how to retrieve and manipulate customer and order data using SQL and Python, as well as managing various booking and order procedures through stored procedures and views.

## Project Overview

The project involves querying a MySQL database to extract customer and order information, working with multiple tables such as `customer`, `orders`, `bookings`, `menu`, and `staff`. Additionally, the project features procedures for handling bookings, updating records, and managing transactions. The data is accessed and manipulated using both SQL scripts and a Python script for database interaction.

### Repository Contents

1. **SQL Scripts**:
    - `SQL script for Littlelemon_DB.sql`:
      - Contains the SQL commands to set up and populate the `littlelemon_db` with tables such as `customer`, `orders`, `menu`, and more.
    - `Capstone MySQL Project.sql`:
      - A detailed SQL script that includes:
        - Selecting records from various tables.
        - Creating views to summarize order details.
        - Complex queries joining multiple tables to extract customer and order information.
        - Procedures for managing and canceling bookings and orders.
        - Prepared statements and transactions to handle booking conflicts.

2. **Python Script**:
    - `MySQL-Python Integration`:
      - This Python script connects to the MySQL database using `mysql-connector-python`. It retrieves the table structure of the database and runs queries to return customer and order data.
      - The script includes:
        - A connection to the MySQL database.
        - Query execution to display customer and order details.
        - Retrieval and printing of table names and column details.

3. **ER Model**:
    - The ER model provides a visual representation of the relationships between the tables in the `littlelemon_db`, helping to understand the structure of the database.


### Prerequisites

- **MySQL Server**: Ensure MySQL is installed and running.
- **Python Packages**:
  - `mysql-connector-python`: Install using the command `pip install mysql-connector-python`.

### How to Run

1. Set up the database by running the SQL scripts.
2. Run the Python script to retrieve and display customer and order details.

### Future Work

- Further enhancement of queries to include more filters or additional customer/order attributes.
- Expand the Python script to include error handling and user interaction for custom queries.
