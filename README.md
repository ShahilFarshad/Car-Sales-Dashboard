# Car-Sales-Dashboard 
## Project Overview
This project focuses on the design and development of a dynamic and interactive Car Sales Dashboard using Power BI for a car dealership company. The dashboard provides real-time insights into sales performance by visualizing key performance indicators (KPIs) and trends. It enables management to monitor progress, evaluate growth, and make data-driven business decisions.
## Dataset used
<a href = "https://github.com/ShahilFarshad/Car-Sales-Dashboard/blob/main/Car%20Sales.xlsx"> Car Sales Dataset </a>
## Dashboard file 
<a href = "https://github.com/ShahilFarshad/Car-Sales-Dashboard/blob/main/Car%20Sales%20dashboard.pbix"> Dashboard file in Power BI </a>
## Problem Statement 1: KPI’s Requirement
1.	Sales Overview:
- Year-to-Date (YTD) Total Sales
- Month-to-Date (MTD) Total Sales
- Year-over-Year (YOY) Growth in Total Sales
- Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales
2.	Average Price Analysis:
- YTD Average Price
-	MTD Average Price
-	YOY Growth in Average Price
-	Difference between YTD Average Price and PTYD Average Price
3.	Cars Sold Metrics:
-	YTD Cars Sold
-	MTD Cars Sold
-	YOY Growth in Cars Sold
-	Difference between YTD Cars Sold and PTYD Cars Sold
- Dashboard Interaction <a href="https://github.com/ShahilFarshad/Car-Sales-Dashboard/blob/main/Car%20sales%20Dashboard%20Overview.png"> View Dashboard </a>
## Process
- Data Collection and Import into Power BI – Gather the sales dataset and load it into Power BI from sources such as Excel, CSV, or a database.

- Data Cleaning and Transformation (Power Query) – Clean the data by correcting data types, removing duplicates or null values, renaming columns, and preparing the dataset for analysis.

- Date Table Creation for Time Intelligence – Create a dedicated date table to support accurate YTD, MTD, and YOY calculations.

- Data Modeling and Relationship Building – Establish proper relationships between fact and dimension tables to ensure accurate filtering and calculations.

- KPI and Core Measure Creation Using DAX – Develop key measures such as Total Sales, Cars Sold, and Average Price using DAX formulas.

- ime Intelligence Calculations (YTD, MTD, YOY, PTYD) – Implement advanced DAX measures to calculate year-to-date, month-to-date, and year-over-year performance metrics.

- Sales and Performance Metrics Development – Build additional calculations for growth percentages, differences, and contribution analysis.

- Visual Creation (Charts, Cards, Tables, and Maps) – Design KPI cards, line charts, donut charts, map visuals, and tables to represent insights clearly.

- Slicers and Interactive Filters Setup – Add slicers for body style, dealer region, transmission, engine type, and other filters to enable interactivity.

-  Dashboard Layout and Design Formatting – Apply consistent themes, colors, alignment, and page navigation to create a professional dashboard layout.

- Testing, Validation, and Interaction Check – Verify calculations, test slicer interactions, and ensure all visuals respond correctly to filters.

- Final Review and Deployment – Perform a final quality check and publish the dashboard to Power BI Service for sharing and business use.

## Dashboard
<img width="1286" height="722" alt="Car sales Dashboard Overview" src="https://github.com/user-attachments/assets/1ee0fd85-0402-4129-a986-3b6d9afac647" />
## Problem Statement 2: Charts Requirement

1.	YTD Sales Weekly Trend: Display a line chart illustrating the weekly trend of YTD sales. The X-axis should represent weeks, and the Y-axis should show the total sales amount.
2.	YTD Total Sales by Body Style: Visualize the distribution of YTD total sales across different car body styles using a Pie chart.
3.	YTD Total Sales by Color: Present the contribution of various car colors to the YTD total sales through a pie chart.
4.	YTD Cars Sold by Dealer Region: Showcase the YTD sales data based on different dealer regions using a map chart to visualize the sales distribution geographically.
5.	Company-Wise Sales Trend in Grid Form: Provide a tabular grid that displays the sales trend for each company. The grid should showcase the company name along with their YTD sales figures.
6.	Details Grid Showing All Car Sales Information: Create a detailed grid that presents all relevant information for each car sale, including car model, body style, colour, sales amount, dealer region, date, etc



