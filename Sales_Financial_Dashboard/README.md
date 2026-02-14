# Sales & Financial Performance Dashboard | Power BI

---

## Project Overview

This project presents a **Sales & Financial Performance Dashboard** developed in Power BI, combining financial indicators, commercial efficiency metrics, and sales team performance analysis.

The objective is to transform transactional sales data into **strategic business insights**, supporting revenue optimization and performance management decisions.

The dashboard is structured into two analytical layers:

- Financial Performance
- Sales Team Performance

---

## Business Problem

How can we evaluate:

- Overall revenue performance?
- Sales team efficiency and ranking?
- Conversion effectiveness?
- Revenue distribution by country and transfer method?
- The relationship between employee rating and revenue generation?

This dashboard answers these questions through **KPI structuring, data modeling, and advanced DAX calculations**.

---

## Data Modeling & Architecture

A **star schema model** was implemented:

### Fact Table
- Orders

### Dimension Tables
- Customers
- Employees

### Key Relationships
- Orders[CustomerID] → Customers[CustomerID]
- Orders[SalesPersonID] → Employees[EmployeeID]

Data transformation and cleaning were performed using **Power Query (ETL process)**.

---

## Financial Analysis Page

This page focuses on macro-level financial performance.

### Key KPIs
- Revenue: **$352.4M**
- Average Order Value (AOV): **$108.8**
- Ordered Items: **7,899**

### Visual Analysis

**Revenue Trend Over Time**  
Time series analysis identifying revenue fluctuations and monthly seasonality patterns.

**Revenue by Country**  
Egypt and Saudi Arabia represent the highest revenue concentration, indicating regional dependency risk.

**Revenue by Transfer Method**  
Hawala is the most used transfer method (~42%), followed by MasterCard and Debit Card, reflecting customer payment behavior patterns.

**Geographic Revenue Distribution**  
Map visualization showing strong concentration in Middle Eastern countries.

---

## Sales Performance Page

This page evaluates individual sales representative performance.

### Key KPIs
- Revenue by Sales Representative
- Average Conversion Rate: **0.932**
- Sales Ranking

### Visual Analysis

**Revenue Ranking**  
Michael leads revenue generation, followed by Joseph and Jennifer.

**Conversion Rate by Sales Representative**  
Conversion rates remain consistently above 0.90, indicating strong commercial efficiency and standardized sales processes.

**Job Rating vs Revenue (Scatter Plot)**  
Indicates a moderate positive correlation between employee performance rating and revenue generation.

**Performance Table**  
Consolidated view combining Revenue, Ranking, and Conversion Rate for comparative analysis.

---

## Key Business Insights

- Revenue is geographically concentrated, representing potential exposure risk.
- Sales team conversion rates are consistently high, indicating operational efficiency.
- Top-performing representatives significantly outperform the average revenue benchmark.
- Payment distribution shows reliance on alternative transfer systems (Hawala).
- Higher job ratings tend to correlate with stronger revenue performance.

---

## Tools & Technologies

- Power BI
- Power Query (ETL)
- DAX
- Data Modeling (Star Schema)
- KPI Structuring
- Business Intelligence Design
