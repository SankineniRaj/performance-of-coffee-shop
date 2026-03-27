
Coffee Shop Sales Performance Dashboard
Project Overview
This project involves the creation of an end-to-end interactive dashboard to analyze sales, footfall, and product trends for a coffee shop chain over a six-month period (January to June). The goal was to transform raw transactional data into actionable business insights regarding peak hours, top-performing locations, and product popularity.

Tools Used 
Microsoft Excel: The sole tool used for the entire pipeline (Data Cleaning, Analysis, and Visualization).

Power Query: Used for ETL (Extract, Transform, Load) processes.

Pivot Tables & Pivot Charts: Used for data aggregation and visualization.

Data Pipeline & Methodology
1. Data Cleaning (Power Query)
Raw CSV data was imported into Power Query to ensure data integrity and create necessary dimensions for analysis:

Trimming: Removed leading and trailing spaces from text columns to prevent grouping errors.

Time Transformation: Extracted the Hour from the transaction time to enable hourly trend analysis.

Custom Columns: Created day names and month names for time-series filtering.

Data Typing: Ensured currency, dates, and quantities were correctly formatted.

2. Data Modeling & Analysis
Using Pivot Tables, the cleaned data was aggregated to calculate key performance indicators (KPIs) and distributions:

Total Sales and Footfall calculations.

Average Bill and Order size per person.

Sales distribution across 9 different product categories.

Order volume by size (Large, Regular, Small).

3. Visualization & Design
The dashboard was designed with a cohesive "Coffee-themed" color palette and features:

KPI Cards: High-level summary of Sales, Footfall, and Averages.

Trend Analysis: A line chart showing the "Quantity Ordered Based on Hours," identifying a significant peak at 10:00 AM.

Geospatial Insights: Bar charts comparing footfall and sales across three locations: Astoria, Hell's Kitchen, and Lower Manhattan.

Product Performance: A "Top 5 Products" chart highlighting Barista Espresso as the leading revenue generator.

Interactivity: Added Slicers for "Month Name" and "Day Name," allowing users to filter the entire dashboard dynamically.

Key Insights
Peak Hours: Order volume surges between 8:00 AM and 10:00 AM, suggesting a heavy breakfast/morning rush.

Top Location: Hell's Kitchen leads in both footfall (50,735) and total sales ($2,36,511.17).

Product Mix: "Coffee" is the dominant category at 39%, followed by "Tea" at 28%.

Customer Behavior: Regular and Large sizes are nearly equal in popularity (31% and 30%), suggesting customers prefer standard or larger portions.
