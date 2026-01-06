#  Power BI Sales & Profit Analysis Dashboard

An end-to-end Power BI data analytics project focused on analysing sales performance, profitability, product trends, promotions, customers, and time-based comparisons using industry-standard data modelling and advanced DAX techniques.

---

## 1. Project Overview

This project demonstrates a complete business intelligence workflow using Power BI — from data modelling and transformation to interactive dashboard design and advanced analytical comparisons.

The dashboard enables:
- Executive-level KPI monitoring
- Period-over-period comparison using dual date filters
- Identification of top and bottom performing products
- Detailed drill-down into transactional data

The solution follows Star Schema modelling and showcases real-world Power BI practices used in enterprise BI teams.

---

## 2. Business Questions Answered

- Top 5 and Bottom 5 products by Sales, Profit, and Quantity Sold
- How do sales and profit trends change over time?
- What is the relationship between Net Sales and Profit?
- Compare Sales / Profit / Quantity Sold between any two selected time periods
- What is the average discount across promotion categories?
- Total number of orders
- View order-level transactional details using filters
- Sales distribution across cities

---

## 3. Data Sources

- Fact Table
  - Transaction-level sales data
  - Measures: Net Sales, Profit, Units Sold, Discounts

- Dimension Tables
  - Dim Product
  - Dim Customers
  - Dim Promotion
  - Date Table 1 (Active)
  - Date Table 2 (Inactive)

Data is imported and transformed using Power Query.

---

## 4. Data Transformation (Power Query)

Key transformation steps:
- Promoted headers
- Standardised data types
- Renamed columns for consistency
- Removed unnecessary columns
- Cleaned primary and foreign keys
- Maintained separation between Fact and Dimension tables

Fact and Dimension tables were not merged, following best practices.

---

## 5. Data Modeling

The model is built using a Star Schema, optimised for performance and reliable DAX calculations.

### Relationships
- One-to-Many relationships from Dimension tables to the Fact table
- Single-direction filter flow
- One active date relationship
- One inactive date relationship for comparison analysis

---

## 6. DAX & Analytical Concepts

### Key DAX Functions Used
- CALCULATE
- ALL
- USERELATIONSHIP
- Filter context manipulation
- Active vs Inactive relationships

### Advanced Use Case
- Two independent date slicers
- Period comparison using inactive relationships
- Measures dynamically respond to selected date contexts

---

## 7. Dashboard Pages & Analysis

### Overview
- KPI Cards:
  - Total Sales
  - Total Profit
  - Total Quantity Sold
  - Number of Orders
- Sales by City (Map)
- Profit vs Net Sales (Scatter Plot)
- Sales Trend Over Time

![Dashboard Image 2](https://github.com/user-attachments/assets/5aa65a5c-441d-4d33-9161-a68ca23847ab)


---

### Comparison: Sales / Profit / Quantity
- Dual date slicers
- Side-by-side comparison of:
  - Sales
  - Profit
  - Quantity Sold
- Implemented using USERELATIONSHIP and advanced DAX


![Dashboard Image 2](https://github.com/user-attachments/assets/4ac579cf-e0cd-41bc-9f26-c7e6b05546a3)


---

### Top / Bottom 5 Products
- Top 5 and Bottom 5 Products by:
  - Sales
  - Profit
  - Units Sold
- Enables quick identification of high and low performers


![Dashboard Image 2](https://github.com/user-attachments/assets/78d65a05-77c8-4ce1-a5f4-bd3491926c11)


---

### Transaction Detail Table
- Order-level data including:
  - Customer
  - Product
  - Promotion
  - Date
  - Sales, Profit, Discounts, Quantity
- Fully interactive with slicers


![Dashboard Image 2](https://github.com/user-attachments/assets/a140b051-507a-4e69-9c63-6506505dee3f)

---

## 8. Interactivity & UX Features

- Controlled slicer interactions using Edit Interactions
- Independent filters for comparative analysis
- Clean, executive-friendly layout
- Consistent color coding for insights

---

## 9. Methodologies & Best Practices

- Star Schema modeling
- Separation of Fact and Dimension logic
- Avoidance of circular dependencies
- Use of relationships instead of Power Query merges
- Centralized Measures Table
- Scalable and reusable DAX patterns

---


## 10. How to Use

1. Open the PBIX file in Power BI Desktop
2. Use slicers to filter by:
   - Date
   - Product
   - Customer
   - Promotion
3. Explore comparison and ranking visuals
4. Publish to Power BI Service for sharing

---
