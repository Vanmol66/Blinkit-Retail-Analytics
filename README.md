# Blinkit Retail Analytics Dashboard (Power BI)

## Project Overview

This project analyzes Blinkit retail sales data using Power BI to understand store performance, product characteristics, and pricing patterns.  

The goal of this dashboard is to transform raw retail data into actionable insights that help explain:

- Which product categories generate the most revenue
- Which outlets perform the best
- How store location affects sales
- Whether product price or weight influences demand

The project demonstrates how Power BI can be used to build an interactive analytics solution for retail businesses.

---

## Dashboard Structure

The Power BI report is divided into **three interconnected analytical dashboards**.

### 1. Executive Overview

This page provides a high-level summary of business performance.

Key insights include:

- Total sales generated across all outlets
- Average sales per outlet
- Sales distribution by product category
- Revenue contribution by outlet type
- Sales comparison by outlet size
- Sales trend by outlet establishment year

This page helps stakeholders quickly understand overall business performance.

---

### 2. Outlet Performance Analysis

This dashboard focuses on understanding how individual stores perform.

Key analysis includes:

- Top performing outlets
- Sales comparison across location tiers
- Relationship between outlet age and sales
- Performance of outlet types across different locations
- Sales distribution by outlet size
- Outlet percentage share by type

This section helps identify the most efficient store formats and locations.

---

### 3. Product & Pricing Intelligence

This page explores product characteristics and their relationship with sales.

Key analysis includes:

- Top selling product categories
- Distribution of product weights
- Fat content distribution by weight
- Relationship between product price and demand
- Relationship between product weight and sales

This section helps understand how product attributes influence consumer demand.

---

## Interactivity Features

All three dashboards are **fully interconnected**.

Key interactive capabilities include:

- Synced slicers across all pages
- Cross-filtering between visuals
- Dynamic filtering by item type, outlet type, and location tier

Users can apply filters on any page and explore how different variables influence sales performance across the entire report.

---

## Data Model

The analysis uses a **Star Schema data model** consisting of:

Fact Table  
- Fact_sales (contains transactional sales data)

Dimension Tables  
- Dim_product (product attributes such as type, weight, fat content, and price)  
- Dim_outlet (store attributes such as type, size, location, and establishment year)

This modeling approach improves performance and ensures consistent filtering across the dashboard.

---

## Key Insights

Several important insights emerged from the analysis:

- Supermarket Type 1 outlets generate the highest sales.
- Tier 3 locations contribute the largest share of revenue.
- Medium-sized outlets tend to outperform other store sizes.
- Fruits & Vegetables and Snack Foods dominate category sales.
- Product price and weight do not show a strong direct relationship with demand.

---

## Tools Used

- Power BI
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling
- Retail Data Analytics

---

## Repository Contents

dataset/  
Raw dataset used for the analysis.

dashboard/  
Power BI dashboard file (.pbix).

report/  
Detailed analysis report.

images/  
Screenshots of dashboard pages.

---

## Author

Retail Analytics Project using Power BI
