### Zomato Sales & User Performance Analysis 

Designed a **Zomato-themed Power BI dashboard** to analyze sales performance, user behavior, and restaurant insights. The dashboard transforms raw data into interactive visual reports, helping stakeholders monitor business performance, identify trends, and support data-driven decision-making.

---

## Dashboard Previews

### 1. Home Page
![Home](Screenshots/Home%20Page.png)

### 2. Overview  
![Overview](Screenshots/Overview.png)

### 3. User Performance  
![User Performance](Screenshots/User%20Performance.png)

### 4. City Analysis
![City Analysis](Screenshots/City%20Analysis.png)

### 5. Restaurant Analysis  
![Restaurant Analysis](Screenshots/Restaurant%20Analysis.png)

### 6. Insights  
 ![Insights](Screenshots/Insights.png)
 
---

## Project Overview

This project is a **Power BI dashboard** built using the **Zomato Restaurant Dataset** to analyze sales performance, customer behavior, restaurant performance, cuisine trends, and city-wise business growth.

The dashboard was developed using **Power BI, Power Query, DAX, and Excel**. It combines business data into interactive reports, making it easier to explore sales trends, customer activity, restaurant performance, and city-wise comparisons.

The dashboard includes six interactive report pages with KPIs, charts, filters, and navigation buttons that allow users to explore the data from different perspectives.

The project focuses on:

- Sales and order performance
- Customer behavior and demographics
- Restaurant performance and ratings
- City-wise business analysis
- Cuisine trends and food preferences
- Interactive reporting for business insights
  
---

## Business Problem Statement

Zomato collects data from restaurants, customers, and orders across different cities. Analyzing this information manually can make it difficult to understand business performance and identify useful trends.

This dashboard was built to help answer business questions such as:

- Which cities generate the highest sales and order volume?
- Which restaurants perform better based on sales and customer ratings?
- Which cuisines and food categories are most popular?
- How do customer demographics influence sales?
- How can interactive reports help monitor KPIs and support better business decisions?

  ---

## Core Objective

The goal of this project is to help Zomato make data-driven business decisions by converting large volumes of restaurant data into actionable insights. Using Power BI, Power Query, and DAX, the project analyzes restaurant performance, customer ratings, cuisines, pricing, and service availability to identify trends, evaluate business performance, and support strategic decision-making through an interactive dashboard.

---

## Dataset

The project uses multiple related tables containing order, user, restaurant, and city data. The dataset includes information such as:

- Order ID
- User ID
- City
- Restaurant Name
- Cuisine
- Order Date
- Item Count
- Total Amount
- Delivery Time
- Rating

---

## Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX (Data Analysis Expressions)**
* **Microsoft Excel (for data pre-cleaning)**
* **Custom Visuals**

  ---

## Data Cleaning & Preparation

I used **Power Query** and **DAX** to clean and prepare the dataset before building the dashboard.

### Data Cleaning
- Removed duplicate records.
- Handled missing and null values where needed.
- Corrected data types for accurate calculations.
- Renamed columns to make the dataset easier to understand.
- Standardized values to keep the data consistent.
  
### Data Transformation
- Created calculated columns and DAX measures for KPIs.
- Built relationships between tables for better analysis.
- Prepared the data model to support interactive reports and filters.
  
### Result
After cleaning and preparing the data, I was able to build an interactive Power BI dashboard with accurate KPIs, dynamic filters, and visualizations for sales, users, cities, and restaurant performance.

  ---

 ### DAX Measures Used

I used DAX measures to calculate the main KPIs displayed in the dashboard.

```DAX
Total Sales =
SUM(orders[Value])

Total Orders =
COUNTROWS(orders)

Total Users =
DISTINCTCOUNT(orders[user_id])

Average Order Value =
DIVIDE([Total Sales], [Total Orders])

Average Rating =
AVERAGE(restaurant[rating])
```

### Measures Used

- **Total Sales** – Calculates the total sales amount.
- **Total Orders** – Counts the total number of orders.
- **Total Users** – Counts the number of unique users.
- **Average Order Value** – Calculates the average value of each order.
- **Average Rating** – Calculates the average restaurant rating.

  ---
  
  ## Dashboard Features

he dashboard contains **6 interactive report pages**, each focusing on a different part of Zomato's business performance.

### 1.Home Page

- Interactive landing page
- Navigation buttons
- Dashboard branding

### 2. Overview
Shows the overall business performance with key KPIs and sales trends.

**Includes**
- Total Sales
- Total Users
- Total Orders
- Total Rating Count
- City-wise Sales Analysis
- Yearly Sales Trend
- Food Category Sales
- Quantity vs. Amount Toggle
- Top N City Analysis

### 3. User Performance
Analyzes customer behavior and user-related metrics.

**Includes**
- Total Users
- Gained & Lost Customers
- Current Year vs Previous Year Sales
- User Age Distribution
- Sales by Gender
- Sales by Marital Status
- Sales by Occupation

### 4. City Performance
Compares business performance across different cities.

**Includes**
- Total Cities
- Total Users
- Current Year vs Previous Year Sales
- City-wise Sales
- City-wise User Count
- City-wise Rating Count
- Detailed City Performance Table

### 5. Restaurant Analysis
Provides insights into restaurant performance and food preferences.

**Includes**
- Restaurant Count
- Average Rating
- Current Year vs Previous Year Sales
- Restaurant Count by City
- Food Type Distribution
- Top Cuisine Categories
- Restaurant Rating Analysis
- Cuisine-wise Revenue

### 6. Insights
Summarizes the main findings from the dashboard and provides business recommendations based on the analysis.

**Includes**
- Sales Performance Summary
- User Behavior Insights
- City-wise Performance
- Restaurant Performance
- Business Recommendation

  ---
  
## Interactive Features

 Interactive Navigation Menu
* Dynamic Search
* Dropdown Slicers
* Gender Toggle
* Quantity vs Amount Toggle
* Top N Analysis (Top 5, Top 10, Top 20, Top 50 & Top 100)
* Cross-filtering Between Visuals
* KPI Cards
* Bookmarks
* Navigation Buttons

---

  ## Filters & Slicers

The dashboard includes interactive filters to help users explore the data from different perspectives:

* Year Slicer
* City Slicer
* Restaurant Slicer
* Cuisine Slicer
* Food Type Slicer
* Dynamic Cross-filtering

  ---

  ## Key Insights

- Tirupati generated the highest sales among all cities.
- Vegetarian restaurants contributed slightly higher sales than non-vegetarian restaurants.
- Customers aged 21–25 generated the highest order volume.
- Bikaner recorded the highest restaurant and user count.
- North Indian and Chinese cuisines generated the highest revenue.
  
  ---

## Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX
- Dashboard Design
- KPI Development
- Interactive Reporting
- Data Storytelling
- Business Analysis

  ---
  
## What I Learned

- How to clean and model complex datasets using Power Query.
- Writing DAX functions for business logic.
- Designing interactive, user-friendly dashboards.
- Real-world storytelling with data.
- Publishing and sharing Power BI reports publicly.

  ---

  ## Project Structure

```text
PowerBI_Zomato_Dashboard/
│
├──  Zomato_Dashboard.pbix          # Main Power BI dashboard
├── 📄README.md                     # Project documentation
├── 📁 Screenshots/                  # Dashboard screenshots
│   ├── Home_page.png
│   ├── overview.png
│   ├── user_performance.png
│   ├── city_analysis.png
│   ├── restaurant_analysis.png
│   └── insights.png
│
└── 📄 Zomato_Dataset.xlsx           # Dataset used for analysis
```

---

### Author
**Sakshi Gadewar**
Aspiring Data Analyst | Power BI | Excel

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/sakshi-gadewar-604175343)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?logo=github)](https://github.com/sakshi-gadewar)

## ⭐ If you found this project helpful, consider giving it a star!
