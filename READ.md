# 🍕 PIZZA SALES PERFORMANCE & REVENUE ANALYSIS (SQL)




## 📌 PROJECT OVERVIEW


This project analyzes a year's worth of sales data from a pizza restaurant to uncover operational insights, revenue drivers, and customer purchasing patterns. Using relational database queries (SQL), the analysis covers key business metrics ranging from baseline sales figures to complex cumulative revenue trends and category-level rankings.





---







## 🎯 BUSINESS PROBLEMS & OBJECTIVES

The goal of this analysis is to address core business questions across three levels of complexity:

**BASIC** Track overall order volume, total revenue, top-selling pizza types, and common order sizes.

  
**INTERMEDIATE:** Evaluate hourly demand trends, daily ordering averages, category distributions, and top revenue generators.

  
**ADVANCED:** Analyze percentage contributions to total revenue, track cumulative revenue growth over time, and rank top pizzas within each menu category.





---





## 🗄️ Database Schema & Data Model


The analysis is built on four relational tables:


`orders`: Contains columns like `order_id`, `order_date`, and `order_time`.

  
 `order_details`: Links orders to specific pizzas with `order_details_id`, `order_id`, `pizza_id`, and `quantity`.

 
 `pizzas`: Stores pricing and sizing data `pizza_id`, `pizza_type_id`, `size`, `price`.

  
 `pizza_types`: Stores menu metadata (`pizza_type_id`, `name`, `category`, `ingredients`).




---





## 💡 Key Findings & Insights


* **Peak Demand:** Sales peak during lunch (11:00 AM – 1:00 PM) and dinner hours (5:00 PM – 7:00 PM), suggesting optimal times for kitchen staffing.


**Revenue Drivers:** 'Classic' and 'Supreme' categories contribute heavily to overall earnings, with 'Large' size pizzas dominating order volume.


**Menu Ranking:** The top-performing pizza types consistently lead revenue across individual categories, providing a clear signal for inventory prioritization.










































