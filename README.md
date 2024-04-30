# sql_project

-- context of problem----------------------------------------------------------------------------------------------------------------------------------------

-- A pizza business owner may face various challenges that can be effectively addressed with the help of a data analyst skill. 
-- Some of those challenges include:

-- 1 Demand Forecasting
-- 2 Menu Optimization
-- 3 Customer Segmentation
-- 4 Supply Chain Management
-- 5 Operational Efficiency

-- By leveraging data analysis techniques, a pizza business owner can gain valuable insights into various aspects of their operations, leading to informed decision-making, improved 
-- efficiency, and ultimately, greater profitability.


-- explaining the approach to a problem -------------------------------------------------------------------------------------------------------------------------------------------

--  Here are detailed methodology and data preprocessing steps involved in this MySQL project:

-- 1) Retrieve the total number of orders placed
      
-- 2) Calculate the total revenue generated from pizza sales
         
-- 3) Identify the highest-priced pizza
         
-- 4) Identify the most common pizza size ordered
         
-- 5) List the top 5 most ordered pizza types along with their quantities
          
-- 6) Join the necessary tables to find the total quantity of each pizza category ordered
         
-- 7) Determine the distribution of orders by hour of the day
         
-- 8) Join relevant tables to find the category-wise distribution of pizzas
         
-- 9) Group the orders by date and calculate the average number of pizzas ordered per day

-- 10) Determine the top 3 most ordered pizza types based on revenue: order is correctly represented in the order details table.

-- 11) Calculate the percentage contribution of each pizza type to total revenue
         
-- 12) Analyze the cumulative revenue generated over time
         
-- 13) Determine the top 3 most ordered pizza types based on revenue for each pizza category
         
-- By following these methodologies and ensuring appropriate data preprocessing, we can effectively analyze the pizza sales data and derive valuable insights to optimize business 
-- operations and maximising revenue.

-- Below are the my query's written on the pizza sales dataset 

-- 1) Retrieve the total number of orders placed.

SELECT 
    COUNT(order_id) AS total_orders
FROM
    orders;
![image](https://github.com/ppatil98/sql_project/assets/164129841/cf56ea17-7388-4355-8a53-9ddaabaa40c3)
