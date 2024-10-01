# Pizzas Sales Python

## Project Overview
This data analysis project is a recreation of a project i did using [SQL](https://github.com/StephenTheAnalyst/Pizzas-sales-SQL). I loved how the dataset made me use joins, window functions and Subquery in SQL, so i was wondering how it would have gone if i was asked to use python, so yeah, here it goes 🙂

## Data Overview
### I worked with four different tables. Which are:

 1. [pizzas](https://github.com/StephenTheAnalyst/PizzasSalesPython/blob/main/pizzas.csv) : This table contains the **'pizza_id'**, **'pizza_type_id'**, **'size'**, **'price'** columns.
 2. [pizza_types](https://github.com/StephenTheAnalyst/PizzasSalesPython/blob/main/pizza_types.csv) : This table contains the **'pizza_type_id'**, **'name'**, **'category'**, **'ingredients'** columns.
 3. [orders](https://github.com/StephenTheAnalyst/PizzasSalesPython/blob/main/orders.csv) : This table contains the **'order_id'**, **'date'**, **'time'** columns.
 4. [order_details](https://github.com/StephenTheAnalyst/PizzasSalesPython/blob/main/order_details.csv) : This table contains the **'order_details_id'**, **'order_id'**, **'pizza_id'**, **'quantity'** columns.

## Data Source

The dataset used for this data analysis project was downloaded from [kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales?select=pizza_types.csv). Kaggle allows users to find datasets they want to use in building AI models, publish datasets, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges.

## Tools

- Google Colab (Python)

## Exploratory Data Analysis

### I worked on the exact same questions i worked on when i was doing the project using SQL.

 1. Retrieve the total number of orders placed.
 2. Calculate the total revenue generated from pizza sales.
 3. Identify the highest-priced pizza.
 4. Identify the most common pizza size ordered.
 5. List the top 5 most ordered pizza types along with their quantities.
 6. Join the necessary tables to find the total quantity of each pizza category ordered.
 7. Determine the distribution of orders by hour of the day.
 8. Join relevant tables to find the category-wise distribution of pizzas.
 9. Group the orders by date and calculate the average number of pizzas ordered per day.
 10. Determine the top 3 most ordered pizza types based on revenue.
 11. Calculate the percentage contribution of each pizza type to total revenue.
 12. Analyze the cumulative revenue generated over time.
 13. Determine the top 3 most ordered pizza types based on revenue for each pizza category.
