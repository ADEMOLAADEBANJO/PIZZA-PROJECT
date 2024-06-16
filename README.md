PIZZA PROJECT
Project Overview:
This SQL project focuses on a database schema created to manage and analyze data for a pizza store. The database features four main tables: order_details, pizzas, orders, and pizza_types. Each table is essential for storing various aspects of business operations, ranging from individual orders to the different types of pizzas available. 
Below is a detailed description of each table and its columns:
1. order_details:
   - order_details_id: A unique identifier for each entry in the order details.
   - order_id: References the ID from the orders table, linking the order detail to a specific order.
   - pizza_id: References the ID from the pizzas table, identifying which pizza was ordered.
   - quantity: The number of pizzas ordered of the specified type.

2. pizzas:
   - pizza_id: A unique identifier for each type of pizza available.
   - pizza_type_id: Links to the pizza_types table, specifying the type of pizza.
   - size: The size of the pizza (e.g., small, medium, large).
   - price: The cost of the pizza.

3. orders:
   - order_id: A unique identifier for each order placed.
   - date: The date on which the order was placed.
   - time: The time at which the order was placed.

4. pizza_types:
   - pizza_type_id: A unique identifier for each type of pizza.
   - name: The name of the pizza type (e.g., Margherita, Pepperoni).
   - category: Categorizes the pizza (e.g., Vegetarian, Non-Vegetarian).
   - ingredients: Lists the ingredients used in the pizza.

Insights Sought from this Project
1. Sales Analysis:  By querying the order_details and pizzas tables, managers can identify the best-selling pizzas, assess revenue generated from different pizza sizes, and evaluate the effectiveness of current pricing strategies
2. Inventory Management: Analyzing the pizza_types and their ingredients enables efficient inventory management. This ensures that ingredients are stocked based on demand, reducing waste and optimizing supply levels.
3. Customer Preferences:  Data from the orders and pizzas tables allow managers to track customer preferences over time. This helps in adjusting the menu to highlight popular choices and experimenting with new or seasonal offerings to meet customer demands.

Business Questions to be Answered
Sales Analysis
1.	What is the total number of orders placed?
2.	What is the total revenue generated from pizza sales?
3.	What is the most common pizza size ordered?
4.	Group the orders by date and calculate the average number of pizzas ordered per day.
5.	What are the top 3 most ordered pizza types based on revenue
Inventory Management and Resource Allocation
1.	What is the distribution of orders by hour of the day (at which time the orders are maximum?
2.	Which ingredients are most frequently used and should be stocked more regularly?
3.	Can we identify any seasonal trends in pizza demand?

Customer Preferences
1.	 What are the top 5 most ordered pizza types along with their quantities.
2.	What is the total quantity of each pizza category ordered (to understand the category which customers prefer the most).
3.	What is the category-wise distribution of pizzas
4.	What are the peak hours and days for orders?
