📊 Global Superstore Sales Analysis Dashboard
📌 Project Overview

The Global Superstore Sales Analysis Dashboard is a data visualization and business intelligence project developed using Microsoft Power BI. The project analyzes sales, profit, quantity, customers, products, categories, regions, and shipping information from the Global Superstore dataset.

The dashboard helps users understand sales performance, identify profitable products and regions, analyze customer segments, and make data-driven business decisions through interactive visualizations.

🎯 Objectives

The main objectives of this project are:

Analyze overall sales and profit performance.
Identify the most profitable product categories and sub-categories.
Analyze sales across different countries, regions, and markets.
Understand customer segment performance.
Analyze shipping modes and order priorities.
Identify high-performing and low-performing products.
Study the relationship between sales, discounts, and profit.
Provide an interactive dashboard for business decision-making.
🛠️ Technologies Used
Microsoft Power BI – Dashboard development and data visualization
CSV – Dataset storage
Power Query – Data cleaning and transformation
DAX – Calculations and measures
Data Visualization – Charts, cards, maps, tables, and slicers
📂 Dataset

The project uses the Global Superstore dataset.

The dataset contains 1,000 records and 24 columns in the provided CSV file.

Important Columns
Column	Description
Row ID	Unique row identifier
Order ID	Unique order identifier
Order Date	Date when the order was placed
Ship Date	Date when the order was shipped
Ship Mode	Shipping method
Customer ID	Unique customer identifier
Customer Name	Customer name
Segment	Customer segment
City	Customer city
State	Customer state
Country	Customer country
Region	Sales region
Market	Market category
Product ID	Unique product identifier
Category	Product category
Sub-Category	Product sub-category
Product Name	Product name
Sales	Sales amount
Quantity	Quantity ordered
Discount	Discount percentage
Profit	Profit generated
Shipping Cost	Cost of shipping
Order Priority	Priority of the order
📊 Dashboard Features

The Power BI dashboard provides interactive analysis of:

1. Sales Analysis
Total Sales
Sales by category
Sales by region
Sales by market
Sales by country
Sales trends over time
2. Profit Analysis
Total Profit
Profit by category
Profit by sub-category
Profit by region
Identification of profitable and loss-making products
3. Customer Analysis
Customer segments
Consumer performance
Corporate performance
Home Office performance
Customer-wise sales analysis
4. Product Analysis
Product categories
Product sub-categories
Top-selling products
Product-wise profit
Quantity sold
5. Shipping Analysis
Ship Mode performance
Shipping cost
Order priority
Order and shipping date analysis
6. Interactive Filters

Users can filter the dashboard based on:

Category
Sub-Category
Region
Country
Market
Segment
Ship Mode
Order Priority
Order Date
📈 Key KPIs

The dashboard can be used to monitor important business KPIs such as:

Total Sales
Total Profit
Total Quantity
Total Orders
Average Sales
Average Discount
Total Shipping Cost
Profit Margin
Example DAX Measures
Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Quantity = SUM(Sales[Quantity])

Total Shipping Cost = SUM(Sales[Shipping Cost])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

🔄 Data Processing Workflow

The project follows the following workflow:

Global Superstore CSV
        ↓
Data Import
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
DAX Measures
        ↓
Data Visualization
        ↓
Interactive Power BI Dashboard
        ↓
Business Insights

📁 Project Structure
Global-Superstore-Sales-Analysis/
│
├── Global_Superstore(CSV).csv
│
├── sales.pbix
│
└── README.md

Files Description

Global_Superstore(CSV).csv
Contains the sales, customer, product, shipping, and profit data used for analysis.

sales.pbix
Power BI project file containing the data model, calculations, visualizations, filters, and dashboard.

README.md
Documentation describing the project, dataset, technologies, and dashboard functionality.

💡 Business Insights

The dashboard can help businesses:

Identify high-performing sales regions.
Determine the most profitable categories.
Find products generating losses.
Understand customer purchasing patterns.
Evaluate the effect of discounts on profitability.
Analyze shipping costs and shipping methods.
Compare sales performance between different markets.
Improve inventory and sales planning.
Support data-driven business decisions.
🚀 How to Run the Project
Step 1: Install Power BI

Install Microsoft Power BI Desktop on your computer.

Step 2: Open the Project

Open:

sales.pbix


using Power BI Desktop.

Step 3: Load the Dataset

If the dataset path is not available, update the data source to:

Global_Superstore(CSV).csv

Step 4: Refresh Data

In Power BI:

Home → Refresh

Step 5: Explore Dashboard

Use the available charts, KPI cards, slicers, maps, and tables to interact with the dashboard.

🔮 Future Enhancements

The project can be further improved by adding:

Sales forecasting
Profit forecasting
Customer segmentation
Advanced DAX calculations
Drill-through reports
Tooltip pages
Decomposition Tree analysis
What-if analysis
Machine Learning-based sales prediction
Automated report publishing
Real-time data integration
👩‍💻 Project Type

Business Intelligence & Data Visualization

📌 Conclusion

The Global Superstore Sales Analysis Dashboard provides an interactive and user-friendly way to analyze sales and business performance. By combining data cleaning, DAX calculations, and Power BI visualizations, the project transforms raw sales data into meaningful business insights.

The dashboard can assist managers and decision-makers in understanding sales trends, profitability, customer behavior, product performance, and regional performance, ultimately supporting better and more informed business decisions.

This version is suitable for a GitHub repository, college project submission, or Power BI project documentation.