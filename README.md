# Superstore Sales Analytics Dashboard

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-2A6B29?style=for-the-badge)
![Power Pivot & DAX](https://img.shields.io/badge/Power_Pivot_%26_DAX-F2C811?style=for-the-badge)

An end-to-end interactive Excel sales analytics dashboard designed to analyze retail performance, track regional metrics, evaluate product profitability, and study customer buying behavior across 9,800+ transactions.

---

## Project Overview

This capstone project transforms raw multi-year retail sales records into actionable executive business intelligence. Using Excel's advanced data modeling features (Power Query, Power Pivot, and DAX measures), the project automates KPI reporting and enables seamless cross-filtering across dimensions such as time, geography, category, and customer segments.

### Key High-Level Metrics
* **Total Revenue**: $2,252,607
* **Total Orders**: 4,916
* **Average Order Value (AOV)**: $458
* **Total Customers**: 793
* **Average Sales Per Customer**: $2,841
* **Geographic Coverage**: 4 Regions | 49 States

---

## Dashboard Architecture & Views

The workbook is structured into 5 cohesive views connected by custom dynamic navigation tabs:

### 1. Executive Overview
* **Yearly Sales Trend**: Tracks yearly sales momentum from 2015 through 2018, highlighting steady post-2016 growth up to $721K.
* **Regional & Shipping Breakdown**: Visualizes sales split across Standard Class, Second Class, First Class, and Same Day shipping.
* **Top Sub-Categories**: Donut breakdown highlighting high-volume drivers.

### 2. Regional Analysis
* **State & City Leaders**: Identifies California ($446K) and New York ($306K) as the primary revenue generators.
* **City Insights**: Focuses on top revenue centers: New York City ($252K), Los Angeles ($173K), and Seattle ($116K).
* **Regional Share**: West (32%) and East (29%) contribute over 60% of aggregate sales.

### 3. Product Analysis
* **Category Contribution**: Technology leads at 37%, followed by Furniture (32%) and Office Supplies (31%).
* **Sub-Category Spectrum**: Phones generate the highest revenue (~$330K), while Fasteners generate the lowest (~$3K).
* **Top Revenue Product**: *Canon imageCLASS Advanced Copier* alone drove over $61,600 in sales.

### 4. Customer Insights
* **Segment Breakdown**: Consumer segment represents 51% of total sales (400 customers), Corporate accounts for 30% (236 customers), and Home Office delivers 19% (146 customers).
* **High-Value Clients**: Identifies top individual spenders including Sean Miller ($25K+) and Tamara Chand ($19K+).

---

## Technical Stack & Data Workflow

1. **Data Cleaning & Transformation (Power Query)**:
   * Removed duplicates, handled missing values, and corrected data types.
   * Standardized date formatting and derived calendar fields for time-intelligence reporting.
2. **Data Modeling (Power Pivot)**:
   * Structured transactional fact data and relational lookup dimensions into a Star/Snowflake schema.
3. **Analytical Calculations (DAX Measures)**:
   * Developed 9+ DAX measures to calculate dynamic metrics: Total Sales, Order Volume, AOV, Sales per Customer, and Segment Proportions.
4. **Data Visualization (Excel UI)**:
   * Designed a cohesive dark theme with high-contrast KPI cards.
   * Integrated multi-select timeline slicers (Year, Region, Sub-Category) for instant interactive exploration.

---

## Key Business Insights & Recommendations

* **Capitalize on West & East Hubs**: West and East regions account for 61% of total sales. Targeted marketing and inventory allocation should prioritize California and New York distribution hubs.
* **Scale High-Ticket Technology Products**: While Technology represents only a portion of the catalog, it produces 37% of revenue. Bundling accessories with enterprise-grade copiers and phones can further expand margin.
* **Targeted Retention for Top 10% Spenders**: A concentrated group of VIP customers generates disproportionate revenue. Establishing dedicated account managers or loyalty programs for corporate and high-volume consumer buyers will minimize churn risk.

---

## How to Run This Project

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/your-username/superstore-sales-analytics-excel.git](https://github.com/your-username/superstore-sales-analytics-excel.git)
