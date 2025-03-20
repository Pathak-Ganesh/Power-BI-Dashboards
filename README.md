# Global Sales Dashboard
## Project Objectives

-Analyze Global Sales Performance – Track total sales and quantity sold across different regions, segments, and years.
-Monitor Delivery Efficiency 
–Measure average delivery days to assess operational efficiency.
-Identify High and Low-Performing Products 
–Evaluate profit and loss against individual products.
-Understand Sales by Market Segments – Compare sales distribution among Consumer, Corporate, and Home Office segments.
-Track Return Orders – Analyze return order trends to identify potential product or logistics issues.
-Visualize Sales Distribution – Use geo-mapping to display sales performance across countries.

## Questions
1. Total Sales & Quantity Sold – What are the total sales and quantity sold over the years?
2. Sales by Segment – Which customer segment (Consumer, Corporate, Home Office) contributes the most to sales?
3. Top & Bottom Products – Which products generate the highest profit and which lead to losses?
4. Sales by Region & Country – How are sales distributed across different regions and countries?
5. Average Delivery Time – What is the average number of days taken for product delivery?
6. Return Orders – How many return orders were recorded, and what could be the potential reasons?
7. Yearly Sales Trend – How have sales evolved over different years?



## Process to Create the Global Sales Power BI Dashboard
Step 1: Data Collection & Preparation
Gather Data Sources:
Extract sales data from ERP, CRM, or transactional databases (Excel, SQL, CSV).
Include datasets with order details, customer segments, product categories, delivery details, and returns.
Data Cleaning & Transformation:
Remove duplicates, handle missing values, and correct inconsistencies.
Standardize date formats and currency conversions if required.
Create calculated fields (e.g., total profit, return rate, average delivery days).
Step 2: Data Modeling in Power BI
Import Data into Power BI:
Load cleaned datasets into Power BI using Power Query.
Create Data Relationships:
Define relationships between tables (e.g., Sales → Product → Region → Customer Segment).
Use proper cardinality (one-to-many, many-to-one).
DAX Measures & Calculations:
Total Sales: SUM(Sales[Amount])
Total Quantity Sold: SUM(Sales[Quantity])
Average Delivery Days: AVERAGE(Delivery[Days])
Return Order Count: COUNT(Returns[Order ID])
Profit & Loss: SUM(Sales[Profit])
Step 3: Dashboard Design & Visualization
Set Up Dashboard Layout:
Use a header with the title "Global Sales Dashboard."
Add a year filter for selecting sales data by year.
Visual Components:
KPI Cards: Display Total Sales, Total Quantity, Return Orders, and Average Delivery Days.
Pie Chart: Show Sales by Segment (Consumer, Corporate, Home Office).
Map Visualization: Display Sales by Country using geospatial data.
Bar Charts:
Profit Against Products: Show top-performing products.
Loss Against Products: Highlight underperforming products.
Donut Chart: Visualize Sales by Region to compare revenue distribution.
Interactivity & Filters:
Add year slicers to allow users to filter data dynamically.
Enable tooltips for detailed insights on hovering over visuals.

## Dashboard
![Global Sales](https://github.com/user-attachments/assets/280c9369-9488-42e4-af4e-c5cb40db0949)

