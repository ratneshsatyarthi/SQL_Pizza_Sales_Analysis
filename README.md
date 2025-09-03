# SQL_Pizza_Sales_Analysis

**Pizza Sales Data Analysis SQL Project**

**Project Overview**

This project involves a comprehensive sales performance analysis for a pizza sales dataset using SQL queries. The primary aim is to gain insights into sales trends, revenue distribution, and top-performing products to support strategic decision-making and optimize sales strategies.

**Business Objective**

To analyze pizza sales data to:

- Understand sales trends hourly, daily, and monthly.
- Identify peak sales periods and seasonal variations.
- Calculate key sales metrics such as total sales revenue, average order value, and total orders.
- Measure sales performance of individual products, including best-selling pizzas, popular sizes, and revenue contribution by category.

**Database and Tables**

The project uses PostgreSQL (version 8.11) and consists of the following tables:

- Pizzas: Contains pizza details (pizza ID, code, name, category, ingredients).
- PizzaType: Details on pizza variants (type ID, type code, pizza ID, size, price).
- Orders: Records of orders (order ID, date, and time).
- OrderDetails: Contains order line items (detail ID, order ID, pizza type code, quantity, pizza type ID).

**Key SQL Queries and Analysis Areas**

**Orders Trend**

- Total number of orders placed.
- Distribution of orders by month, day, and hour.
- Quantity of pizzas ordered by size and category.
- Peak times for pizza sales.
- Average pizzas ordered per day.

**Sales Trend**

- Total revenue generated from pizza sales.
- Revenue breakdown by pizza size and type.
- Total revenue by hour, day, and month.
- Dates and months with maximum sales.
- Top-selling pizza types based on revenue.

Product Popularity

- Most and least expensive pizzas.
- Total quantity ordered by pizza type and size.
- Percentage revenue contribution by pizza category.
- Identification of pizzas priced above or below average.

**Notable Insights**

- Sales share is fairly distributed among categories, with Classic category leading at 27%.
- Thai Chicken Pizza has the highest sales revenue; Classic Deluxe Pizza is the most ordered.
- The Greek Pizza is the most expensive (Rs 719); Pepperoni Pizza is the least expensive (Rs 195).
- July generated the highest monthly revenue; December 31 saw the highest daily sales.
- Busy order hours identified as 12:00 PM to 1:00 PM and 5:00 PM to 6:00 PM.
- Large-sized pizzas are most popular, followed by medium and small.

**Recommendations**

- Promote Veg category pizzas with discounts to increase sales.
- Mix ingredients from top-selling with less popular pizzas to enhance flavor.
- Reduce discounts during June-July; increase offers in off-peak months.
- Boost promotional campaigns on special days like Dec 31.
- Set sales targets to raise average pizzas ordered per day from 138 to 160.
- Increase manpower during peak order hours.
- Expand variety for small and medium pizzas to attract more customers.
- Optimize pizza pricing to reduce the gap between highest and lowest prices.

**DDL & DML Examples**

- Creation of database and tables.
- Insert sample data into pizzas, pizza types, orders, and order details.
- Queries for aggregation, calculation, and trend analysis.


