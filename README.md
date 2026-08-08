# 📈 Global Sales & Pareto (ABC) Analytics in Google Sheets

## 📌 Project Overview
This project presents an end-to-end commercial performance analysis for an international e-commerce & offline retailer. Using Google Sheets, the raw sales dataset was cleaned, enriched with key financial metrics, analyzed across various business dimensions (geography, channels, delivery SLAs, seasonality), and categorized using the **Pareto Principle (ABC Analysis)**.

---

## 🛠️ Tech Stack & Methods
* **Tool:** Google Sheets
* **Functions & Techniques:** `VLOOKUP` / `XLOOKUP`, `SUMIFS`, `COUNTIFS`, `INDEX/MATCH`, `WEEKDAY`, Pivot Tables, Data Validation & Cleaning.
* **Analytics Methods:** Financial Performance Tracking, Order Fulfillment (SLA) Analysis, Seasonality & Trend Analysis, ABC (Pareto) Analysis.
* **Visualization:** Interactive Google Sheets Dashboard (Scorecards, Bar Charts, Line Trends, Pareto Charts).

---

## 📊 Core Analysis & Methodology

### 1. Data Cleaning & Financial Metrics Enrichment
* Cleaned raw transactional tables (`Events`, `Products`, `Countries`) by resolving anomalies and missing values.
* Added calculated financial columns:
  * **Total Revenue:** `Units Sold * Unit Price`
  * **Total Cost:** `Units Sold * Unit Cost`
  * **Total Profit:** `Total Revenue - Total Cost`

### 2. Dimensional Performance Breakdown
* **Product Categories:** Identified high-margin vs. high-cost product lines.
* **Geographical Insights:** Performance split by Country, Region, and Sub-region to detect key global markets.
* **Sales Channels:** Comparative analysis between Online vs. Offline sales performance.
* **Fulfillment SLA (Order-to-Ship Interval):** Measured dispatch delays across categories and regions to evaluate if shipping lag impacts profitability.

### 3. Time Series & Seasonality Analysis
* Tracked monthly and yearly sales trends to highlight seasonal peaks and demand drops.
* Analyzed order volume patterns across days of the week (`WEEKDAY()` logic).

### 4. ABC (Pareto) Analysis
Categorized products based on their contribution over the last year:
* **Category A (Top 20%):** Generates ~80% of total revenue/profit (core business drivers).
* **Category B (Next 15%):** Generates ~15% of revenue/profit (stable performers).
* **Category C (Bottom 65%):** Generates ~5% of revenue/profit (long-tail products for review).

---

## 📁 Repository Structure & Deliverables
├── assets/
│   ├── dashboard_overview.png   # Screenshot of the main Google Sheets dashboard
│   └── abc_analysis_chart.png   # Pareto visualization
└── README.md                    # Project documentation

---

## 🔗 Live Links & Reports
* 📑 **Google Sheets Working File:** https://docs.google.com/spreadsheets/d/14FS5QyHYH_fFBKRAefxwyH0-KsLTTD85_n0ekCocTbU/edit?usp=sharing
* 📄 **Executive Summary & Business Conclusions:** https://docs.google.com/document/d/1ud9T5up8IR0ChUUqc7tGYiu8rnKAVISWwpRWNkxT8P4/edit?usp=sharing
