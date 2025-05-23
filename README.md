# Zomato-SQL-Case-Study

## SQL Case Study: Analyzing Zomato Data

### Overview
This repository contains a SQL case study focused on analyzing Zomato-related data using structured SQL queries. The dataset is designed to simulate a real-world food delivery application and consists of several tables, including delivery partners, food items, orders, users, restaurants, and payments. Additionally, the repository includes SQL queries to solve various analytical questions, ranging from basic queries to complex subqueries.

---

### Dataset Description
1. **Delivery_Partner**: Contains details about delivery partners, including their ID, name, vehicle type, rating, and total orders completed.
2. **Food**: Provides information about food items such as their ID, name, category, price, preparation time, and availability status.
3. **Restaurants**: Includes details of restaurants such as their ID, name, location, rating, and specialty.
4. **Users**: Stores user information, including their ID, name, email, location, total orders, and ratings.
5. **Orders**: Tracks order data, including order ID, user ID, restaurant ID, delivery partner ID, total amount, and more.
6. **Order_Details**: Contains information on specific order items, such as quantity, subtotal, and status.
7. **Payments**: Captures payment details like payment ID, order ID, user ID, payment method, amount, and payment status.

---

### Questions and Analysis
This case study explores the dataset through the following questions:

1. **Find customers who have never placed an order.**
2. **Calculate the average price of dishes in each category.**
3. **Find delivery partners who have completed more than 100 orders.**
4. **Determine the total revenue generated by each restaurant.**
5. **List customers who have rated the platform below 4.5.**
6. **Find restaurants specializing in 'Indian' cuisine with a rating above 4.5.**
7. **Identify the restaurant with the highest number of repeated customers.**
8. **Find the food item with the highest revenue.**
9. **Identify restaurants where the average food price exceeds ₹250.**
10. **Determine the favorite food item for each customer.**
11. **Find the customer with the maximum number of orders.**
12. **List orders where the total amount exceeds ₹1000.**
13. **Identify the delivery partner with the highest average rating.**

---

### Usage
Follow these steps to use this repository:

1. Clone this repository to your local machine.
2. Install a SQL database management system (e.g., MySQL, PostgreSQL).
3. Copy and execute the table creation script provided in the `create_tables.sql` file to set up the database and tables.
4. Run the SQL queries in the `queries.sql` file to answer the analytical questions.

---

### Directory Structure
```
|-- data/
    |-- delivery_partner.csv
    |-- food.csv
    |-- restaurants.csv
    |-- users.csv
    |-- orders.csv
    |-- order_details.csv
    |-- payments.csv
|-- create_tables.sql
|-- queries.sql
|-- README.md
```

---

### Notes
- Feel free to modify and extend the dataset and queries to explore additional insights.
- If you encounter any issues or have suggestions for improvement, you are encouraged to submit an issue or a pull request.

