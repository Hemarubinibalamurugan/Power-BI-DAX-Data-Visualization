# 📊 Project Title: Power BI Data Cleaning, DAX & Dashboard Development

This project demonstrates the complete Power BI workflow, from data cleaning and transformation to data modeling, DAX calculations, and interactive dashboard creation for business analysis.

## 📑 Table of Contents

- Project Overview
- Data Sources & Architecture
- Data Transformation (ETL)
- Data Model & DAX
- Dashboard Features
- Key Insights
- How To Use


## 🎯 Project Overview

- Business Problem: Raw business data contains missing values, duplicate records, and inconsistent formatting, making accurate reporting and analysis difficult.

- Objective: Clean and transform the data using Power Query, build a relational data model, create DAX measures, and develop an interactive dashboard for business insights.

- Target Audience: Data Analysts, Business Analysts, Power BI Learners, and Reporting Teams.


## 🗃️ Data Sources & Architecture

- Source Systems:
  
  - List of Orders.csv
  - Order Details.csv
  - Sales Target.csv

- Data Volume:
  
  - List of Orders – First 500 rows
  - Order Details – Transaction-level sales data
  - Sales Target – Monthly target data

- Storage Mode: Import Mode


## ⚙️ Data Transformation (ETL)

- Tool Used: Power Query Editor

- Key Cleanups:
  
  - Imported CSV datasets
  - Changed data types
  - Removed duplicate records
  - Checked missing values
  - Created Location, Profit Margin, and Profit Status columns
  - Merged tables using Order ID
  - Applied sorting, filtering, and grouping
  - Loaded the cleaned data into Power BI

- Custom Functions: No custom M code was used.

---

## 🧠 Data Model & DAX

- Model Type: Basic Relational Model

- Fact Tables:
  
  - Order Details
  - Orders Data

- Dimension Tables:
  
  - List of Orders
  - Sales Target

- Key Measures:

Total Sales
Total Target
Total Orders
Average Profit
YTD Sales
Sales Count
Target Count
Minimum Target
Maximum Target
Average Target

---

## 🖥️ Dashboard Features

- Sales Analysis:
  
  - Sales Target Achievement by Category
  - Max Profit Margin by Sub-Category
  - Monthly Sales Trend
  - Profit vs Quantity Analysis

- KPI Dashboard:
  
  - Total Orders
  - Average Profit
  - YTD Sales
  - Total Sales
  - Total Target
  - Minimum Target
  - Maximum Target
  - Average Target

- Business Insights:
  
  - Sales Performance Matrix
  - Geographic Sales Analysis (Map)
  - Sales Distribution (Treemap)
  - Order Count by State (Funnel Chart)

- Design Theme: A clean and interactive dashboard with KPI cards, charts, slicers, and consistent formatting for better user experience.


## 💡 Key Insights

- Trend A: Sales performance varies across different product categories and months.

- Trend B: Certain product sub-categories generate higher profit margins than others.

- Recommendation: Perform proper data cleaning and transformation before analysis to improve reporting accuracy and support better business decisions.


## 🚀 How To Use

1. Prerequisites: Install the latest version of Power BI Desktop.

2. File Formats: Open the ".pbix" file and ensure the required CSV datasets are available.

3. Data Refresh: Update the data source path if required and click Refresh to load the latest data.
