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

# Process of the Project
## 1.	Data Collection:
- Two datasets were used:
  - <a href = "https://github.com/AkashKumar-47/Data-analytics/blob/main/Details.xlsx">Details</a>
  - <a href = "https://github.com/AkashKumar-47/Data-analytics/blob/main/Orders.xlsx">Orders</a>
## 2.	Data Cleaning & Transformation:
- Ensured proper data types for each field (e.g., date, numeric values).
- Established relationships between the "Details" and "Orders" datasets using the common field "order_id."
- Created calculated measures for KPIs such as Total Profit, Total Quantity, Total Amount, and AOV.
## 3.	Dashboard Creation:
- Built interactive visualizations using Power BI:
  - Profit by Month (Stacked Column Chart)
  - Profit by Sub-Category (Stacked Bar Chart)
  - Sum of Amount by State and Customer Name (Stacked Bar Chart)
  - Sum of Quantity by Category and Payment Mode (Donut Chart)
  - Key Metrics (Cards for Total Amount, Total Profit, Total Quantity, and AOV)
- Added interactive slicers for Quarter and State to filter the data dynamically.

## Project Insights
1.  **Profit Trends:** Certain months exhibit significantly higher profits, indicating seasonal trends.
2.	**Sub-Category Contribution:** Specific sub-categories drive the majority of profits, highlighting key revenue drivers.
3.	**State & Customer Analysis:** A few states and high-value customers contribute disproportionately to the total revenue.
4.	**Payment Mode Preferences:** Customers exhibit clear preferences for specific payment methods across different categories.
5.	**Overall Performance Metrics:** The dashboard provides a snapshot of essential metrics (Total Amount, Profit, Quantity, and AOV).

## Dashboard Image

![Ecommerce Saled Dashboard](https://github.com/user-attachments/assets/0e960364-4a3a-489c-8748-a2e633c20960)

## Final Conclusion
- The Power BI dashboard delivers a robust analysis of sales performance across multiple dimensions. It enables stakeholders to identify key profit drivers, customer behaviors, and regional trends, facilitating data-driven decision-making.
- This interactive tool can be expanded with additional datasets or enhanced KPIs to provide deeper insights into future business operations.
