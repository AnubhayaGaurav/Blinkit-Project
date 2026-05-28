# Blinkit Sales Analysis Dashboard

## Project Overview

This project focuses on analyzing Blinkit sales data using SQL and Power BI to generate meaningful business insights. The dataset was cleaned, transformed, and analyzed using SQL queries, while Power BI was used to create an interactive dashboard for visualization and reporting.

---

## Objectives

* Analyze overall sales performance
* Understand customer purchasing patterns
* Evaluate outlet performance
* Track KPIs and sales trends
* Create an interactive business dashboard

---

## Tools & Technologies

* SQL Server
* Power BI
* Excel Dataset
* Power Query
* DAX

---

## Data Cleaning

Performed data cleaning to standardize the `Item_Fat_Content` column for consistency.

### SQL Query Used

```sql
UPDATE blinkit_data
SET Item_Fat_Content = 
    CASE 
        WHEN Item_Fat_Content IN ('LF', 'low fat') THEN 'Low Fat'
        WHEN Item_Fat_Content = 'reg' THEN 'Regular'
        ELSE Item_Fat_Content
    END;
```

---

## Key Performance Indicators (KPIs)

* Total Sales
* Average Sales
* Number of Orders
* Average Rating

---

## Business Analysis Performed

### Sales Analysis

* Total Sales by Fat Content
* Total Sales by Item Type
* Sales by Outlet Location
* Sales by Outlet Establishment Year
* Sales Percentage by Outlet Size

### Outlet Analysis

* Outlet Type Performance
* Fat Content Analysis by Outlet
* Item Visibility Analysis

---

## Dashboard Features

* Interactive Power BI Dashboard
* KPI Cards and Charts
* Filters and Slicers
* Sales Trend Visualization
* Outlet Performance Insights
* Category-wise Analysis

---

## Insights Generated

* Identified top-performing outlet types
* Compared Low Fat vs Regular product sales
* Analyzed outlet size contribution to total sales
* Tracked customer ratings and product visibility
* Evaluated yearly sales trends

---

## Project Files

* SQL Queries
* Power BI Dashboard (.pbix)
* Excel Dataset
* README.md

---

## Conclusion

This project demonstrates skills in SQL, data cleaning, business analysis, and dashboard development using Power BI. It highlights how raw retail data can be transformed into actionable insights through data analytics and visualization.
