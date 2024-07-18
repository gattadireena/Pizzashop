Pizza Sales Analysis Project Using MySQL

Overview

This project involves analyzing pizza sales data using MySQL. The database contains information about orders, pizzas, and their types. 
By executing various SQL queries, the project aims to derive meaningful insights from the data, such as total orders, revenue, popular pizzas, 
and sales distribution patterns.

Database Schema

The database `pizzashop` contains the following four tables:

1. order_details
   - `order_details_id`: INT
   - `order_id`: INT
   - `pizza_id`: TEXT
   - `quantity`: INT

2. orders
   - `order_id`: INT
   - `order_date`: DATE
   - `order_time`: TIME

3. pizzas
   - `pizza_id`: TEXT
   - `pizza_type_id`: TEXT
   - `size`: TEXT
   - `price`: DOUBLE

4. pizza_types
   - `pizza_type_id`: VARCHAR(255)
   - `name`: VARCHAR(255)
   - `category`: VARCHAR(255)
   - `ingredients`: TEXT
  
