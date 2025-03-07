# What is Power BI?
Power BI is a business Intelligence and data visualisation tool that converts data from various data sources into interactive dashboard and analysis reports.

# Project Objective
The objective of this project is to analyze and visualize sales data to gain actionable insights into profit trends, customer behavior, and product performance. This interactive Power BI dashboard provides a comprehensive overview of sales metrics across different time periods, categories, and geographical locations.

# Key Questions & KPIs

## Key Questions:

- What are the monthly profit trends?
- Which sub-categories contribute the most to the profit?
- How is the sales amount distributed across states and customers?
- Which payment modes are most frequently used across different categories?
- What are the key sales metrics (Total Amount, Total Profit, Total Quantity, Average Order Value)?

## Key Performance Indicators (KPIs):

- Total Amount
- Total Profit
- Total Quantity
- Average Order Value (AOV)

## Dashboard

- <a href = "https://github.com/AkashKumar-47/Data-analytics/blob/main/Ecommerce%20Saled%20Dashboard.png">Image</a>

# Process of the Project
1.	Data Collection:
o	Two datasets were used:
	Details (order_id, amount, profit, quantity, category, sub_category, payment_mode, AOV)
	Orders (order_id, order_date, customer_name, state, city)
2.	Data Cleaning & Transformation:
o	Ensured proper data types for each field (e.g., date, numeric values).
o	Established relationships between the "Details" and "Orders" datasets using the common field "order_id."
o	Created calculated measures for KPIs such as Total Profit, Total Quantity, Total Amount, and AOV.
3.	Dashboard Creation:
o	Built interactive visualizations using Power BI:
1.	Profit by Month (Stacked Column Chart)
2.	Profit by Sub-Category (Stacked Bar Chart)
3.	Sum of Amount by State and Customer Name (Stacked Bar Chart)
4.	Sum of Quantity by Category and Payment Mode (Donut Chart)
5.	Key Metrics (Cards for Total Amount, Total Profit, Total Quantity, and AOV)
o	Added interactive slicers for Quarter and State to filter the data dynamically.

