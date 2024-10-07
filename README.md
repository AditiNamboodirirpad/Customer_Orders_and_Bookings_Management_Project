# Restaurant Customer Orders Project

This repository contains the files and scripts used for managing and querying the **Little Lemon** database. The project demonstrates how to retrieve and manipulate customer and order data using SQL and Python, as well as managing various booking and order procedures through stored procedures and views. Additionally, it includes interactive Tableau dashboards for data visualization.

You can view the dashboard here: [Customer Orders and Restaurant Management](https://public.tableau.com/app/profile/aditi1877/viz/CustomerOrdersandRestaurantManagement/CustomerDashboard)

## Project Overview

The project involves querying a MySQL database to extract customer and order information, working with multiple tables such as `customer`, `orders`, `bookings`, `menu`, and `staff`. The project features procedures for handling bookings, updating records, and managing transactions. The data is accessed and manipulated using both SQL scripts and a Python script for database interaction. Furthermore, Tableau dashboards are included to visualize key insights from the data.

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

    
4. **Tableau Dashboards**:
    - The Tableau workbook contains various dashboards that provide insights into customer behavior, order trends, and product performance:
      - **Customer Dashboard**:
        1. **Customer Segmentation by Country**: Visualizes the distribution of customers by country using a map.
        2. **Top 5 Customers by Sales**: Highlights the top five customers who generated the highest sales.
        3. **Top 5 Customers by Profit**: Displays the top five customers contributing the most profit.

      - **Profit and Sales Analysis Dashboard**:
        1. **Profit Over the Years**: Analyzes profit trends over multiple years, showing peak and lowest profit periods.
        2. **Profit Over Months**: Highlights the highest and lowest profit months across the dataset.
        3. **Sales for Each Order Date**: Provides detailed sales figures on specific order dates.
        4. **Order Value Over the Months**: Compares order values to identify peak sales months.

      - **Spatial Dashboard**:
        1. **Profit by Country**: Analyzes the geographical distribution of profit, identifying regions with the highest earnings.
        2. **Sales by Country**: Visualizes the total sales across different countries.
        3. **Average Order Value by Region**: Shows the average order value by geographical region to identify high-value areas.

      - **Product Dashboard**:
        1. **Top 10 Food Combos**: Lists the top food combinations in terms of sales, profit, and quantity sold.
        2. **Profit of Cuisine by Year**: Highlights the yearly profit trends for different cuisines, showing which cuisine was the most profitable.
        3. **Sales of Cuisine by Region**: Analyzes the regional distribution of cuisine sales.



### Prerequisites

- **MySQL Server**: Ensure MySQL is installed and running.
- **Python Packages**:
  - `mysql-connector-python`: Install using the command `pip install mysql-connector-python`.
- **Tableau Desktop**: To view and interact with the Tableau dashboards.

### How to Run

1. Set up the database by running the SQL scripts.
2. Run the Python notebook to retrieve and display customer and order details.
3. Open the Tableau workbook to explore the interactive dashboards.

### Future Work

- Further enhancement of SQL queries to include more filters or additional customer/order attributes.
- Expansion of the Python script to include advanced error handling and more user-friendly features.
- Additional Tableau visualizations for deeper insights into customer and order behavior.

---
