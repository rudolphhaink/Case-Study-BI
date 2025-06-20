# BI Analyst Case Study

This repository contains my submission for the **(Senior) BI Analyst Case Study** as part of the selection process for the role.

## 📄 Overview

The case study consists of two main parts:

1. **Business Analysis Presentation**  
   A concise, business-oriented analysis focused on uncovering key insights from the data to support strategic decision-making.

2. **SQL Mock Query**  
   A written SQL solution to a realistic business scenario, demonstrating my proficiency in data querying and logical structuring.

---

## 📊 Part 1: Analysis

### Selected Analysis: *Sales Performance Analysis*  

The analysis explores:
- revenue trends across different regions
- revenue trends across sales channels
- revenue trends across product types

**Tools used:** Python, Visual Studio Code, Looker Studio

**SQL Dialect:** SQLite

**Deliverable:** A 15-minute presentation slide deck intended for a leadership audience.

[Link to Looker Dashboard](https://lookerstudio.google.com/reporting/62cdb9fc-f9d1-4ceb-a3f2-bbb3cba37257)
[Link to Queries](Part_1_Analysis.sql)  
[Link to Dataset](sales.csv)

---

## 🧮 Part 2: SQL Mock Query

### Task:   
Write a query comparing online and offline sales channel performance by region for the past six
months. Your query should output total revenue, total returns, and the proportion of returned
units compared to units sold. Also, identify regions with return proportions higher than the
average.

Expected Output Schema:

+ region
+ channel (online/offline)
+ total_revenue
+ total_returns
+ return_proportion
+ above_average_return (boolean indicating if return proportion is above average)
  
**Tools used:** Python, Visual Studio Code

**SQL Dialect:** SQLite

[Link to Queries](Part_2_Mock_Query.sql)    
[Link to Dataset](sales.csv)

---

## 🗃️ Dataset Description

The dataset includes ~200k simulated sales transactions with the following fields:

- `transaction_id` – Unique transaction identifier  
- `product_type`, `customer_type`, `region`, `channel`  
- `price`, `amount`, `returned_amount`, `total_revenue`, `total_cost`, `net_revenue`  
- `date` – Transaction date (YYYY-MM-DD)

Note: The data is fictional and used for case study purposes only.

---

## 👤 Author

Rudolph Haink

