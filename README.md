# Pizza Sales Analysis (SQL and Excel Dashboard)

## Overview
This project analyzes pizza sales data to identify key trends, customer preferences, and product performance.  
The analysis is supported with various charts to provide actionable insights for decision-making.

---

## Problem Statement
We aim to visualize various aspects of pizza sales data to gain insights and understand key trends.  
The following chart requirements have been identified:

### Charts Requirement

1. *Daily Trend for Total Orders*  
   - Create a bar chart that displays the daily trend of total orders over a specific time period.  
   - Helps identify patterns or fluctuations in order volumes on a daily basis.
2. *Hourly Trend for Total Orders*  
   - Create a line chart that illustrates the hourly trend of total orders throughout the day.  
   - Allows us to identify peak hours or periods of high order activity.

3. *Percentage of Sales by Pizza Category*  
   - Create a pie chart showing the distribution of sales across different pizza categories.  
   - Provides an overview of various categories and their contribution to total sales.

4. *Percentage of Sales by Pizza Size*  
   - Generate a pie chart representing the percentage of sales attributed to different pizza sizes.  
   - Helps understand customer preferences for pizza sizes and their impact on sales.

5. *Total Pizzas Sold by Pizza Category*  
   - Create a funnel chart that shows the total number of pizzas sold by category.  
   - Allows comparison of sales performance across different pizza categories.

6. *Top 5 Best Sellers by Total Pizzas Sold*  
   - Create a bar chart highlighting the top 5 best-selling pizzas based on total pizzas sold.  
   - Identifies the most popular pizza options.

7. *Bottom 5 Worst Sellers by Total Pizzas Sold*  
   - Create a bar chart highlighting the bottom 5 worst-selling pizzas based on total pizzas sold.  
   - Helps identify underperforming or less popular pizza options.

## Dataset
The dataset contains detailed information about pizza sales, including:

- *Orders*: Order ID, date, and time of purchase  
- *Order Details*: Pizza ID, quantity, and order linkage  
- *Pizzas*: Pizza ID, pizza type, size, and price  
- *Pizza Types*: Pizza type ID, category, and name  

The data was provided in CSV format and then imported into SQL for analysis.

## Tools & Technologies
- *SQL*:  
  - Used to query and analyze the pizza sales dataset.  
  - Wrote queries to calculate KPIs such as total orders, revenue, category-wise sales, and best/worst sellers.  
  - Verified and validated results generated in Excel.  

- *Excel*:  
  - Created pivot tables and charts for visualization.  
  - Designed an interactive dashboard to show trends (daily, hourly, category, size).  
  - Compared outputs with SQL queries to ensure accuracy.

    ## Methodology

1. *Data Import*
   - Loaded the pizza sales dataset into SQL for querying.  
   - Connected the same dataset to Excel for dashboard creation.  

2. *Data Cleaning and Preparation*
   - Verified data consistency (order IDs, pizza IDs, categories, sizes).  
   - Checked for missing values or duplicates in orders and sales records.  

3. *SQL Analysis*
   - Wrote SQL queries to calculate:  
     - Total revenue, total orders, and total pizzas sold  
     - Daily and hourly sales trends  
     - Percentage contribution by pizza size and category  
     - Top 5 best sellers and bottom 5 worst sellers  

4. *Excel Dashboard*
   - Imported query results into Excel.  
   - Built pivot tables and charts for each requirement.  
   - Designed an interactive dashboard using slicers and KPIs.  

5. *Validation*
   - Cross-checked results between SQL queries and Excel calculations.  

## Key Insights

The interactive Excel dashboard allows users to filter sales data by month (using slicers) and dynamically view results.  
Some of the insights that can be derived include:

- *Sales Trends*  
  - Daily and hourly order patterns help identify peak times.  
  - Seasonal/monthly variations can be explored using slicers.  

- *Category & Size Contribution*  
  - Classic pizzas consistently contribute the highest share of total sales.  
  - Large pizzas dominate sales across most months, followed by Medium sizes.  

- *Product Performance*  
  - Best-selling pizzas can be identified for any given month.  
  - Underperforming pizzas are highlighted, supporting decisions on menu optimization.  

- *Revenue Analysis*  
  - Total revenue, total orders, and total pizzas sold update dynamically.
  - Average order value can be compared across different months.

 ## Deliverables

This repository includes the following project components:

- *SQL Output Report* (pizza_sales_report.docx)  
  - Word document containing the SQL outputs generated from the dataset.  
  - Includes results for revenue, order trends, category/size analysis, and product performance.  

- *Excel Dataset* (pizza_sales_data.xlsx)  
  - The original dataset used for analysis.  
  - Imported into both SQL (for querying) and Excel (for dashboard creation).  

- *Excel Dashboard* ()  
  - Interactive dashboard built using pivot tables, charts, and slicers.  
  - Provides dynamic insights by filtering sales across different months and categories.  

- *Screenshots* (pizza_dashboard.png)  
  - Preview images of the Excel dashboard for quick reference.
