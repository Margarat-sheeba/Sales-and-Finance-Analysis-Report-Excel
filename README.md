# Sales-and-Finance-Analysis-Report-Excel

## Project Description

This project analyzes **customer sales growth** and **market performance** using Microsoft Excel.
It focuses on net sales trends, target achievement, and profitability metrics (COGS, Gross Margin) across multiple years and markets.

---

## Table of Contents

* [Project Description](#project-description)
* [Overview](#overview)
* [Business Problem](#business-problem)
* [Tools & Technologies](#tools--technologies)
* [Data Cleaning & Preparation](#data-cleaning--preparation)
* [Project Structure](#project-structure)
* [Key Findings](#key-findings)
* [Report Highlights](#report-highlights)
* [How to Use / Run This Project](#how-to-userun-this-project)
* [Final Recommendations](#final-recommendations)

---

## Overview

This analysis provides insights into:

* Customer-wise sales growth from **2019 to 2021**
* Market performance against **2021 sales targets**
* Profitability analysis by market (Net Sales, COGS, GM, GM%)
* Yearly and quarterly sales and margin trends
* **Top 10 Products** performance comparison (2021 vs 2020)

---

## Business Problem

The project aims to:

* Track **customer-level sales growth** and identify key contributors
* Compare **market performance vs targets** to uncover gaps
* Evaluate **profitability differences across markets**
* Identify **fastest-growing products** to support future business strategy

---

## Tools & Technologies

**Microsoft Excel (Advanced BI Features)**

* **Power Query** – Importing, cleaning, and transforming raw data
* **Power Pivot** – Data modeling and handling large datasets
* **Pivot Tables** – Summarizing customer, market, and product performance
* **DAX Measures** – Created KPIs such as:

  * Net Sales
  * Gross Margin %
  * YoY Growth %
  * Target Achievement %
* **Data Modeling** – Built relationships between Customer, Market, Product, Sales, and Date tables
* **Date Table** – Extracted Year, Quarter, and Month for time-based analysis

---

## Data Cleaning & Preparation

### Power Query

* Removed duplicates and invalid records
* Standardized data formats (Date, Currency, Percentage)
* Created a Date Table with:

  * Year
  * Quarter
  * Month

### Power Pivot & Data Modeling

* Established relationships:

  * Customer ↔ Sales
  * Market ↔ Sales
  * Product ↔ Sales
  * Date ↔ Sales
* Designed a **star schema** for efficient reporting

📷 *Data Model Screenshot available in the project folder*

### DAX Measures

* Net Sales
* Target Achievement %
* COGS
* Gross Margin & GM%
* YoY Comparison (2021 vs 2020)

---

## Project Structure

```
Customer-Sales-Market-Performance/
│
├─ Reports/
│  ├─ Customer_Net_Sales_Performance.pdf
│  ├─ Market Performance vs Target.pdf
│  ├─ P & L For Markets.pdf
│  ├─ P & L by Fiscal Year 1.pdf
│  └─ Top 10 Products.pdf
│
├─ Data_Model_Screenshot.png
└─ README.md
```

---

## Key Findings

* **Customer Growth:** Major customers such as *AtliQ eStore, Acclaimed Store, Amazon, AtliQ Exclusive, Flipkart,* and *BestBuy* showed strong growth from 2019–2021.
* **Market Targets:** Several markets missed their 2021 targets, resulting in an overall shortfall of approximately **9%**.
* **Profitability:**

  * High-margin markets: *Japan (46.5% GM)*, *New Zealand (48.2% GM)*
  * Low-margin market: *Germany (26.2% GM)*
* **Sales Trend:** Net Sales increased significantly:

  * **$87.5M (2019) → $196.7M (2020) → $598.9M (2021)**
* **Top 10 Products (2021 vs 2020):**

  * *AQ Mx NB* (+5723%), *AQ Smash 2* (+2589%), *AQ LION X Series* (1700%+)
  * Overall Top 10 products achieved **808% YoY growth**, driving major revenue in 2021

---

## Report Highlights

* **Customer Net Sales Report (2019–2021)** – Customer-wise growth analysis
* **Market Performance vs Target (2021)** – Actual vs target comparison
* **P&L by Market** – Net Sales, COGS, and Gross Margin %
* **P&L by Fiscal Year** – Yearly and quarterly trends
* **Top 10 Products (2021 vs 2020)** – Product-level YoY growth

---

## How to Use/Run This Project

1. Open the **Reports** folder
2. Review the PDFs in the following order:

   * *Customer_Net_Sales_Performance.pdf* → Customer growth
   * *Market Performance vs Target.pdf* → Market gap analysis
   * *P & L For Markets.pdf* → Market profitability
   * *P & L by Fiscal Year 1.pdf* → Sales trends
   * *Top 10 Products.pdf* → Product YoY growth

---

## Final Recommendations

* Focus on **top-performing customers** such as Amazon and AtliQ Exclusive
* Analyze **missed targets** in large markets (USA, India, Canada)
* Replicate strategies from **high-margin markets** like Japan and New Zealand
* Improve performance in **low-margin markets** such as Germany and Norway
* Invest further in **high-growth products** (AQ Mx NB, Smash 2, LION Series)
* Monitor customer, market, and product performance **quarterly** for better decision-making




