# UPI Transactions Analysis – Power BI Project

## Project Overview
This project focuses on analyzing UPI transaction data using Power BI to understand transaction patterns, balance trends, and amount behavior across different dimensions such as time, city, bank, device type, gender, and transaction attributes.

The dashboard is designed to be interactive, scalable, and easy to analyze for business and operational insights.

---

## Objectives
- Analyze monthly trends of transaction **Amount** and **Remaining Balance**
- Enable interactive exploration of UPI transactions using filters and slicers
- Compare balance and amount behavior using different visual representations
- Provide a structured matrix view for detailed month-wise and city-wise analysis

---

## Dataset Understanding and Data Profiling
- Performed data profiling to understand data distribution, null values, and column relevance
- Identified key analytical fields such as:
  - Transaction Date and Month
  - Amount
  - Remaining Balance
  - City
  - Bank Name (Sent and Received)
  - Payment Method and Transaction Type
  - Device Type, Gender, and Age Groups
- Ensured data consistency and readiness for reporting

---

## 1. Balance and Amount Analysis
- Used **Line Charts** to analyze monthly trends of Remaining Balance
- Used **Stacked Column Charts** to analyze transaction Amount distribution
- Enabled comparison of balance and amount across months for the year 2024
- Focused on identifying peak and low transaction periods

---

## 2. Interactive Report Navigation
Implemented **Selection Pane** and **Bookmarks** to switch between different report views:

- Line Chart view for Balance  
- Column Chart view for Balance  
- Line Chart view for Amount  
- Column Chart view for Amount  

This allows users to dynamically choose how they want to analyze the data without cluttering the report.

---

## 3. Slicers and Filtering
- Used multiple slicers to filter the data by:
  - Bank Name Sent
  - Bank Name Received
  - City
  - Device Type
  - Gender
  - Age Groups
  - Merchant Name
  - Payment Method
  - Purpose
  - Transaction Type
- Synced slicers across report pages to maintain consistent filtering and user experience

---

## 4. Matrix Analysis
- Created a matrix visual to display:
  - Month-wise transaction data
  - City-level breakdown
  - Amount and Remaining Balance side by side
- Applied conditional formatting to highlight variations and trends
- Enabled easy comparison across cities and months in a tabular format

---

## Visual Formatting and Design
- Applied consistent formatting across all visuals
- Improved readability using:
  - Proper alignment
  - Data labels
  - Color differentiation for balance and amount
- Ensured clean layout and logical placement of slicers and visuals

---

## Key Insights Enabled
- Month-over-month balance movement analysis
- Identification of high transaction months
- Comparison of transaction behavior across cities
- Analysis of balance fluctuations based on transaction volume

---

## Tools and Technologies Used
- Power BI Desktop
- Data Modeling and basic DAX aggregations
- Power BI visuals:
  - Line Chart
  - Stacked Column Chart
  - Matrix
  - Slicers
- Bookmarks and Selection Pane

---

