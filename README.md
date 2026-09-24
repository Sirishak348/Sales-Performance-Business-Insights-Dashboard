# Sales Performance & Business Insights Dashboard

## 📊 Project Overview

This project is an interactive **Sales Performance & Business Insights Dashboard** built using Microsoft Excel.
The project analyzes sales data across regions, product categories, sub-categories, customer segments, and years.
The workflow covers data quality auditing, data cleaning, transformation, data modeling, DAX calculations, analysis, visualization, and business insights.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- PivotTables
- PivotCharts
- Slicers
- Data Cleaning & Transformation
- Data Modeling
- Business Analysis
- Data Visualization

---

## 📁 Project Structure

Sales_Performance_Business_Insights_Dashboard/
│
├── README.md
│
├── Dataset/
│   └── sample_-_superstore.xls
│
├── Excel/
│   └── Sales_Performance_Business_Insights_Dashboard.xlsx
│
└── Screenshots/
    ├── Charts.png
    ├── Insights.png
    ├── KPI's.png
    └── Slicers.png

🎯 Project Objective

The objective of this project is to analyze sales performance and profitability using Excel and build an interactive dashboard that helps understand:
Regional sales performance
Category performance
Sub-category performance
Monthly sales trends
Customer segment performance
Overall profitability
Order volume
Negative-profit transactions

🔄 Project Workflow

Raw Dataset
     ↓
Data Quality Audit
     ↓
Power Query
     ↓
Data Cleaning & Transformation
     ↓
Power Pivot Data Model
     ↓
DAX Measures
     ↓
PivotTables & PivotCharts
     ↓
Interactive Dashboard
     ↓
Business Insights

🧹 Data Quality & Preparation

A data-quality audit was performed before analysis.
The audit included:
Total row count
Missing Order IDs
Missing Order Dates
Missing Sales values
Missing Profit values
Negative-profit records
Duplicate Row IDs
Earliest Order Date
Latest Order Date
The dataset contained:
10,194 records
0 missing Order IDs
0 missing Order Dates
0 missing Sales values
0 missing Profit values
0 duplicate Row IDs
1,901 negative-profit records
Negative-profit records were retained because they represent valid business outcomes rather than data errors.

🔧 Power Query

Power Query was used for data cleaning and transformation.
The following transformations were performed:
Validated column data types
Converted dates to Date type
Converted numeric fields to appropriate numeric types
Treated Postal Code as an identifier
Checked column quality
Created Order Year
Created Order Month
Created Month Number
Created Profit Margin
Created a separate Product lookup table
Removed duplicate Product IDs from the Product table
The original raw data was preserved separately.

🧩 Data Model

Power Pivot was used to create the Data Model.
The main tables used were:
CleanSales
Product
The relationship created was:
Product (1) ───────── (*) CleanSales
Relationship key:
Product[Product ID]
        ↓
CleanSales[Product ID]
This relationship allows product attributes such as Category and Sub-Category to be used with sales measures.

🧮 DAX Measures

The project uses DAX measures for KPI and business analysis.
Key measures include:
Total Sales
Total Profit
Total Orders
Total Quantity
Profit Margin %
Additional analytical measures were also created during the Power Pivot practice and analysis workflow.
Examples of DAX functions used include:
SUM
AVERAGE
DISTINCTCOUNT
DIVIDE
CALCULATE
ALL

📊 Dashboard KPIs

The dashboard contains the following KPI metrics:
KPI
Value
Total Sales
$2.33M
Total Profit
$292K
Total Orders
5,111
Total Quantity
38,654
Profit Margin
12.56%

📈 Dashboard Visualizations

The dashboard contains four major analytical visuals.
1. Sales by Region
Shows sales performance across:
Central
East
South
West
2. Sales by Category
Shows sales across:
Furniture
Office Supplies
Technology
3. Sales by Sub-Category
Provides a detailed view of sales across individual product sub-categories.
4. Monthly Sales Trend
Shows monthly sales performance across the available years in the dataset.
🎛️ Interactive Slicers
The dashboard includes four interactive slicers:
Region
Category
Segment
Order Year
The slicers are connected to the relevant PivotTables and PivotCharts, allowing users to interactively filter the dashboard.

💡 Key Business Insights

1. Regional Performance
The West region generates the highest sales among the four regions.
2. Category Performance
Technology generates the highest sales among the three product categories.
3. Overall Profitability
Overall sales are approximately $2.33M, with approximately $292K profit.
4. Order Volume
The dataset contains 5,111 unique orders.
5. Product-Level Analysis
Sub-category analysis helps identify which product groups contribute most to overall sales.
6. Profitability Risk
1,901 records have negative profit, indicating transactions where sales resulted in losses.
7. Overall Margin
The overall profit margin is approximately 12.56%, based on total profit relative to total sales.

📌 Key Excel Skills Demonstrated

This project demonstrates practical experience with:
Excel Tables
Data Cleaning
Data Quality Auditing
Power Query
Power Pivot
Data Modeling
Relationships
DAX
PivotTables
PivotCharts
Slicers
Data Visualization
KPI Development
Trend Analysis
Business Insights

📂 Dataset

The project uses the Sample Superstore dataset.
The original dataset is included in the Dataset folder for transparency and reproducibility.
The original dataset has been preserved separately from the cleaned analytical data.

🚀 Project Outcome

This project demonstrates an end-to-end Excel Data Analyst workflow:
Raw Data
   ↓
Data Quality Check
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Data Modeling
   ↓
DAX Analysis
   ↓
Visualization
   ↓
Interactive Dashboard
   ↓
Business Insights

The final dashboard provides an interactive view of sales performance, profitability, orders, product categories, regions, and monthly trends.

👩‍💻 Author:K.Sirisha
Data Analyst Portfolio Project
Built using Microsoft Excel, Power Query, Power Pivot, DAX, PivotTables, PivotCharts, and Slicers.