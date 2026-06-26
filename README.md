#  AtliQ Hardware – Sales & Market Performance Analysis (Excel Project)

## Project Overview

AtliQ Hardware is a global manufacturing company specializing in computer hardware products such as mice, PCs, keyboards, and accessories.

The company operates through multiple channels:

* **Retailers & E-Commerce:** Amazon, Flipkart, Croma, Best Buy
* **Direct-to-Consumer (D2C):** AtliQ E-Store & AtliQ Exclusive
* **Distributors:** Used in restricted markets like China & South Korea

This project focuses on analyzing **customer performance** and **market performance vs targets** using **Microsoft Excel**.

---

##  Business Problem (STAR Method)

###  Situation

Between 2019 and 2021, AtliQ experienced rapid sales growth. However, the business struggled to:

* Identify top-performing customers
* Track market performance vs targets
* Analyze growth trends across regions
* Monitor distributor-driven markets

---

### Task

The objective was to create **interactive Excel reports** to:

* Analyze customer-wise net sales
* Track Year-over-Year (YoY) growth
* Compare actual sales vs target
* Highlight underperforming markets

---

###  Action

####  Data Cleaning & Transformation

* Used **Power Query in Excel**
* Removed duplicates and handled missing values
* Standardized raw CSV data

####  Data Modeling

* Built a **Star Schema using Power Pivot**

  * Fact Table: `fact_sales`
  * Dimension Tables: `dim_customer`, `dim_market`, `dim_date`

####  Calculations

* Created measures using **Excel Data Model (DAX)**:

  * Net Sales
  * Growth %
  * Target Difference

####  Dashboard Design

* Created 2 reports:

  1. Customer Net Sales Performance
  2. Market Performance vs Target

* Applied **conditional formatting**:

  * Dark color → High sales
  * Light color → Low sales
  * Red → Below target

---

###  Result & Business Insights

####  Revenue Growth

* Sales increased from **$87.5M (2019)** → **$196.7M (2020)** → **$598.9M (2021)**
* Overall growth: **304.5%**

---

#### Top Customers

* Amazon → Highest revenue contributor
* AtliQ Exclusive & AtliQ E-Store → Strong D2C growth


####  Target Gap

* Company missed target by **-$54.9M (-8.4%)**
* Indicates aggressive planning

---

#### Market Insights

* USA, India, and South Korea underperformed vs targets
* High sales but still below expectations

---

#### Distributor Impact

* China & South Korea (distributor-based markets) showed gaps
* Indicates execution challenges in indirect sales channels

---

##  Dashboard Features

###  Customer Report

* Year-wise sales analysis
* Growth % calculation
* Top customer identification

###  Market Report

* Country-wise performance
* Target vs actual comparison
* Underperformance highlighting

---

## Tools & Technologies

* Microsoft Excel
* Power Query
* Power Pivot
* DAX (Excel Data Model)
* Conditional Formatting

---

##  Key Learnings

* Built end-to-end reports in Excel
* Applied star schema using Power Pivot
* Created KPIs using DAX
* Improved data storytelling using visuals
* Transformed raw data into business insights

---
