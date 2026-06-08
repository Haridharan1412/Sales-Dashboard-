<div align="center">

<!-- Animated Typing Banner -->
<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=F7A800&center=true&vCenter=true&width=800&lines=📊+Sales+Insights+Dashboard;🔍+Data+Analytics+%7C+Power+BI+%7C+SQL;💡+Turning+Raw+Data+into+Decisions;📈+Revenue+%7C+Profit+%7C+Performance" alt="Typing SVG" />
</a>

<br/>

<!-- Badges -->
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)

<br/>

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/sales-insights-dashboard?color=F7A800&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/sales-insights-dashboard?color=0078D4&style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/yourusername/sales-insights-dashboard?style=flat-square&color=F7A800)

<br/>

> **An end-to-end Sales Analytics project** — from raw MySQL data to a production-ready, multi-page interactive Power BI dashboard that delivers actionable revenue, profit, and performance intelligence across 15+ Indian markets.

</div>

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Dashboard Preview](#-dashboard-preview)
- [Key Insights](#-key-insights)
- [KPIs Tracked](#-kpis-tracked)
- [Tech Stack](#-tech-stack)
- [Data Model](#-data-model)
- [SQL Analysis](#-sql-analysis)
- [Dashboard Features](#-dashboard-features)
- [Folder Structure](#-folder-structure)
- [Business Impact](#-business-impact)
- [Installation & Usage](#-installation--usage)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 🎯 Project Overview

### 🏢 Business Problem

A hardware manufacturing company sells products to clients across India through both **Brick & Mortar** stores and **E-Commerce** channels. The sales director receives verbal, fragmented updates from regional managers — leaving leadership with no unified, real-time view of performance. Key questions remain unanswered:

- Which markets and customers are actually driving revenue?
- Where is the company losing money (negative profit margins)?
- How does current revenue compare to the prior year?
- What is the trajectory — is performance improving or declining?

### 🎯 Project Objective

Build a **self-service Power BI Sales Dashboard** that consolidates all transaction data into a single source of truth — enabling faster, data-driven decisions for the sales director and regional teams.

### ✅ Key Goals

| Goal | Description |
|------|-------------|
| 📊 Centralize Sales Data | Aggregate transactions from MySQL across all markets and years |
| 💰 Track Profitability | Measure profit margins by market, customer, and time period |
| 📉 Identify Underperformers | Surface markets and customers with negative margins |
| 🔄 Enable YoY Comparison | Compare current revenue against the prior year baseline |
| 🌍 Regional Performance | Break down North / South / Central zone contributions |

---

## 📸 Dashboard Preview

### 🔑 Key Insights — Revenue & Sales Overview

![Key Insights Dashboard](Key_Insights.png)

> **Overview of total revenue (₹142M), sales quantity (350K units), revenue by market, top 5 customers, and top 5 products for 2020.** Delhi NCR dominates revenue at ₹78M, while Electricalsara Stores is the #1 customer at ₹66M.

---

### 💹 Profit Analysis — Profitability Deep Dive

![Profit Analysis Dashboard](Profit_Analysis.png)

> **Multi-dimensional profitability view showing revenue contribution %, profit contribution % by market, and a customer-level profit margin table.** Lucknow shows a -2.7% revenue contribution — signaling a loss-making market requiring intervention.

---

### 🏆 Performance Insights — YoY & Customer Benchmarking

![Performance Insights Dashboard](Performance_Insights.png)

> **Year-over-year revenue trend comparison with profit margin % overlay, plus a detailed customer table showing Revenue, Revenue Contribution %, Profit Margin Contribution %, and Profit Margin %.** Electricalsara Stores contributes 46.2% of total revenue but only 0.4% profit margin.

---

### 🗂️ Data Model — Star Schema Architecture

![Data Model](Model_View.png)

> **Power BI star schema model** connecting Sales Transactions (fact table) to five dimension tables: Customers, Products, Markets, Date, and Profit Target — optimized for fast DAX calculations.

---

## 💡 Key Insights

### 📈 Revenue Trends
- Total revenue for the filtered 2020 period: **₹142M** with **350K** units sold
- Revenue peaked around **Feb–Mar 2020** (~₹27M/month) before a sharp decline into June 2020 (~₹15M), likely reflecting COVID-19 impact
- The Year-over-Year (LY) comparison reveals consistent under-performance in H1 2020 vs. the prior year baseline

### 💰 Profit Analysis
- Total Profit Margin for 2020: **₹2.1M** (overall margin ~**1.4%**)
- **Mumbai** leads profit contribution at 23.9%, followed by **Delhi NCR** at 22.1% and **Ahmedabad** at 19.0%
- **Lucknow** is the only market with a **negative revenue contribution (-2.7%)** — an urgent flag for the business
- **Epic Stores** records a **-4.7% profit margin** and **-6.8% profit margin contribution** — a loss-making customer relationship

### 🏪 Top-Performing Customers
| Rank | Customer | Revenue | Revenue Contribution | Profit Margin % |
|------|----------|---------|---------------------|-----------------|
| 1 | Electricalsara Stores | ₹6,56,41,977 | 46.2% | 0.4% |
| 2 | Excel Stores | ₹79,28,385 | 5.6% | 3.3% |
| 3 | Premium Stores | ₹58,99,748 | 4.1% | 0.5% |
| 4 | Electricalslytical | ₹55,37,904 | 3.9% | 0.5% |
| 5 | Info Stores | ₹50,64,374 | 3.6% | 3.2% |

> ⚠️ **Critical Finding:** Electricalsara Stores drives 46.2% of total revenue but only 0.4% profit margin — a high-risk revenue concentration with thin profitability.

### 🗺️ Regional Performance
- **Delhi NCR** contributes 54.7% of total revenue but only 22.1% of profits → margin compression in the North zone
- **Bhubaneshwar** leads performance contribution % at **10.5%** (South zone)
- **Hyderabad (6.7%)** and **Chennai (6.3%)** show strong balanced contributions
- **Surat (0.1%)** and **Kanpur (0.5%)** are low-priority markets with minimal impact

### 📦 Top Products
- **(Blank)** product category accounts for ₹65M — indicating a **data quality issue** in product classification
- **Prod047** and **Prod061** are the top named products at ₹4M each
- Product diversity is needed — over-reliance on unclassified SKUs obscures true category performance

---

## 📊 KPIs Tracked

<div align="center">

| KPI | Value (2020 Filter) | Visual |
|-----|--------------------|-|
| 💵 Total Revenue | ₹142M | Card Visual |
| 📦 Sales Quantity | 350K Units | Card Visual |
| 💰 Total Profit Margin | ₹2.1M | Card Visual |
| 📉 Profit Margin % | 1.4% | Line on Combo Chart |
| 🔄 Revenue LY (Prior Year) | Dynamic | Bar Chart (Grey) |
| 🎯 Profit Target | Configurable (e.g. 2%) | Slicer + Target Line |
| 🏪 Revenue by Market | Per Market | Bar Chart |
| 👥 Revenue by Customer | Per Customer | Table + Bar Chart |
| 🗺️ Revenue Contribution % | Per Market/Customer | Horizontal Bar |
| 📈 Profit Contribution % | Per Market | Horizontal Bar |

</div>

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Purpose | Version |
|------|---------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) | Dashboard & Visualizations | Desktop |
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) | Data Storage & Querying | 8.0.20 |
| ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat&logo=microsoft&logoColor=white) | Calculated Measures & KPIs | — |
| ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat&logo=microsoftexcel&logoColor=white) | Data Transformation & Cleaning | M Language |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white) | Supplementary Analysis | — |

</div>

---

## 🗄️ Data Model

The project uses a **Star Schema** design in Power BI with the following tables:

```
                    ┌─────────────────┐
                    │   sales date    │
                    │ ─────────────── │
                    │ date (PK)       │
                    │ cy_date         │
                    │ year            │
                    │ month_name      │
                    └────────┬────────┘
                             │ 1
                             │
┌──────────────┐      ┌──────▼──────────────┐      ┌──────────────────┐
│sales customers│  1  │  Sales transactions  │  *  │  sales markets    │
│ ──────────── │◄────┤ ──────────────────── ├────►│ ──────────────── │
│ customer_code│      │ Cost_Price           │      │ markets_code (PK) │
│ custmer_name │      │ currency             │      │ markets_name      │
│ customer_type│      │ customer_code (FK)   │      │ zone              │
└──────────────┘      │ market_code (FK)     │      └──────────────────┘
                      │ norm_sales_amount    │
┌──────────────┐      │ order_date (FK)      │      ┌──────────────────┐
│sales products│  1  │ product_code (FK)    │      │  Profit Target   │
│ ──────────── │◄────┤ Profit_Margin        │      │ ──────────────── │
│ product_code │      │ ProfitMargin%        │      │ Profit Target    │
│ product_type │      └──────────────────────┘      │ Profit Target Val│
└──────────────┘                                    │ Target Diff      │
                                                    └──────────────────┘
```

**Tables:** `customers` · `date` · `markets` · `products` · `transactions`

**Key Relationships:**
- `transactions.customer_code` → `customers.customer_code` (Many-to-One)
- `transactions.market_code` → `markets.markets_code` (Many-to-One)
- `transactions.order_date` → `date.date` (Many-to-One)
- `transactions.product_code` → `products.product_code` (Many-to-One)

**Customer Base:** 38 customers across Brick & Mortar (19) and E-Commerce (19) channels

**Markets:** 15 Indian cities + New York + Paris (international records filtered out for India-only analysis)

---

## 🔍 SQL Analysis

### Database Setup

```sql
CREATE DATABASE IF NOT EXISTS `sales`;
USE `sales`;
```

### Exploratory Queries

**1. Full Customer Records**
```sql
SELECT * FROM customers;
-- Returns all 38 customers across Brick & Mortar and E-Commerce types
```

**2. Total Customer Count**
```sql
SELECT COUNT(*) FROM customers;
-- Result: 38 customers
```

**3. Chennai Market Transactions**
```sql
SELECT * FROM transactions WHERE market_code = 'Mark001';
-- Chennai is mapped to market code Mark001
```

**4. Distinct Products Sold in Chennai**
```sql
SELECT DISTINCT product_code
FROM transactions
WHERE market_code = 'Mark001';
-- Identifies the unique product mix sold in the South zone's Chennai market
```

**5. USD Transactions (Multi-Currency Handling)**
```sql
SELECT * FROM transactions WHERE currency = 'USD';
-- Surfaces international/export transactions for currency normalization
```

**6. 2020 Transactions with Date Dimension**
```sql
SELECT transactions.*, date.*
FROM transactions
INNER JOIN date ON transactions.order_date = date.date
WHERE date.year = 2020;
-- Enriches transaction records with full date attributes for time-series analysis
```

**7. Total Revenue in 2020 (INR + USD)**
```sql
SELECT SUM(transactions.sales_amount)
FROM transactions
INNER JOIN date ON transactions.order_date = date.date
WHERE date.year = 2020
  AND (transactions.currency = 'INR\r' OR transactions.currency = 'USD\r');
-- Note: \r suffix handles Windows-style line endings in the raw CSV-imported data
```

**8. Revenue for January 2020**
```sql
SELECT SUM(transactions.sales_amount)
FROM transactions
INNER JOIN date ON transactions.order_date = date.date
WHERE date.year = 2020
  AND date.month_name = 'January'
  AND (transactions.currency = 'INR\r' OR transactions.currency = 'USD\r');
```

**9. Chennai Revenue in 2020**
```sql
SELECT SUM(transactions.sales_amount)
FROM transactions
INNER JOIN date ON transactions.order_date = date.date
WHERE date.year = 2020
  AND transactions.market_code = 'Mark001';
```

### 🧹 Data Cleaning Notes

| Issue | Resolution |
|-------|-----------|
| Currency values with `\r` suffix | Filtered using `currency = 'INR\r' OR currency = 'USD\r'` |
| USD transactions mixed with INR | Normalized in Power Query using `norm_amount` column |
| Markets: New York & Paris records | Filtered out — analysis scoped to Indian markets only |
| Blank product codes | Identified as a data quality issue for upstream fix |

### ⚙️ Power Query Transformation (M Language)

```m
= Table.AddColumn(
    #"Filtered Rows",
    "norm_amount",
    each if [currency] = "USD" or [currency] = "USD#(cr)"
         then [sales_amount] * 75
         else [sales_amount],
    type any
)
```

> This creates a normalized `norm_amount` column that converts USD transactions to INR at a fixed rate of ₹75 per USD, enabling apples-to-apples revenue aggregation across all markets.

---

## ✨ Dashboard Features

| Feature | Description |
|---------|-------------|
| 📅 **Year & Month Slicers** | Filter all visuals by year (2017–2020) and month simultaneously |
| 📊 **Revenue Trend Line** | Interactive time-series chart with Jan–Jun monthly granularity |
| 🔄 **YoY Comparison** | Side-by-side current vs. last year revenue bars with profit margin % overlay |
| 🎯 **Profit Target Toggle** | Adjustable profit target (%) slicer that dynamically recalculates target diff |
| 🏪 **Market Drill-Through** | Click any market bar to drill through to customer-level detail |
| 👥 **Customer Performance Table** | Revenue, contribution %, profit margin contribution %, and PM% per customer |
| 🗺️ **Zone-Level Aggregation** | Markets grouped by North / South / Central zones |
| 📄 **Multi-Page Navigation** | Three report pages: Key Insights · Profit Analysis · Performance Insights |
| 🔴 **Negative Margin Highlighting** | Conditional formatting flags loss-making markets (red bars) |

---

## 📁 Folder Structure

```
📦 sales-insights-dashboard/
├── 📊 Sales_dashboard.pbix          # Main Power BI report file
├── 🗄️ dataset.sql                   # MySQL database dump (customers, markets,
│                                    #   products, date, transactions tables)
├── 🔍 sql_queries.txt               # All exploratory SQL queries with comments
├── 📸 screenshots/
│   ├── Key_Insights.png             # Page 1 – Revenue & Sales Overview
│   ├── Profit_Analysis.png          # Page 2 – Profitability Deep Dive
│   ├── Performance_Insights.png     # Page 3 – YoY & Customer Benchmarking
│   └── Model_View.png               # Power BI Data Model (star schema)
└── 📖 README.md                     # This file
```

---

## 💼 Business Impact

### How the Dashboard Drives Decisions

| Decision Area | Before Dashboard | After Dashboard |
|--------------|-----------------|-----------------|
| Revenue Visibility | Verbal updates from regional managers | Real-time ₹142M revenue tracker with monthly trend |
| Market Prioritization | Equal attention to all markets | Focus on Delhi NCR (54.7% revenue share) |
| Loss Prevention | Unknown loss-making relationships | Lucknow (-2.7%) and Epic Stores (-4.7%) flagged immediately |
| Currency Risk | USD/INR mixing distorted totals | Normalized `norm_amount` ensures accurate aggregation |
| Customer Strategy | No tiering by profitability | 46.2% revenue concentration in one customer identified as risk |

### 📋 Strategic Recommendations

1. **Re-negotiate Electricalsara Stores contract** — 46.2% revenue at only 0.4% margin is unsustainable; price revision or volume-based incentives are needed.
2. **Exit or restructure Lucknow operations** — The only market with a negative revenue contribution (-2.7%) requires a cost-structure review or market exit.
3. **Investigate the Blank product category** — ₹65M in revenue sits under unclassified products; resolving this data quality issue will unlock real product-level insights.
4. **Protect Mumbai & Ahmedabad margins** — These markets punch above their revenue weight in profit contribution (23.9% and 19.0% respectively).
5. **Address the June 2020 revenue cliff** — The sharp month-on-month decline from May to June signals an operational or market disruption requiring root-cause analysis.

---

## 🚀 Installation & Usage

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free download)
- MySQL 8.0+ (optional, for re-running SQL queries)
- Git

### Steps to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/sales-insights-dashboard.git
cd sales-insights-dashboard
```

```sql
-- 2. (Optional) Restore the MySQL database
mysql -u root -p < dataset.sql
-- This creates the `sales` database with all 5 tables populated
```

```
3. Open Power BI Desktop
4. File → Open → Select Sales_dashboard.pbix
5. If prompted to refresh data source:
   - Go to Home → Transform Data → Data Source Settings
   - Update the MySQL server connection to: localhost / 127.0.0.1
   - Enter your MySQL credentials
   - Click "Refresh" to reload live data
6. Use the Year/Month slicers at the top to filter the dashboard
7. Navigate between pages using the tabs: Key Insights | Profit Analysis | Performance Insights
```

### Dataset Information

| Table | Rows (approx.) | Description |
|-------|---------------|-------------|
| `customers` | 38 | Customer master with type (B&M / E-Commerce) |
| `markets` | 17 | Market codes, names, and zones (incl. NY & Paris) |
| `products` | ~279 | Product codes and types |
| `date` | ~1,461 | Daily date spine from Jun 2017 to Jun 2020 |
| `transactions` | ~150,000 | Order-level sales transactions |

---

## 🔮 Future Enhancements

- [ ] 🔮 **Sales Forecasting** — Integrate Prophet or Azure ML for 3-month revenue forecasting
- [ ] 🔄 **Automated Data Refresh** — Schedule Power BI Service gateway refresh from MySQL
- [ ] 🌐 **Web Publishing** — Publish to Power BI Service for browser-based access & sharing
- [ ] 📱 **Mobile Layout** — Optimize dashboard layout for Power BI Mobile app
- [ ] 🤖 **Q&A Natural Language** — Enable Power BI Q&A for ad-hoc natural language queries
- [ ] 📧 **Automated Alerts** — Set data-driven alerts when revenue drops below threshold
- [ ] 📊 **Customer Segmentation** — RFM analysis (Recency, Frequency, Monetary) on customer base
- [ ] 🗺️ **Geo Map Visual** — Add a choropleth map of India for spatial revenue visualization
- [ ] 🔗 **API Integration** — Connect live sales pipeline data for real-time transaction tracking

---

## 👤 Author

<div align="center">

<img src="https://avatars.githubusercontent.com/yourusername?size=100" width="100px" style="border-radius:50%" alt="Author Avatar"/>

### Your Name

*Data Analyst | Power BI Developer | SQL Enthusiast*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-F7A800?style=for-the-badge&logo=google-chrome&logoColor=white)](https://yourportfolio.com)

</div>

---

<div align="center">

**⭐ If this project helped you, please consider giving it a star!**

*Built with 💛 using Power BI, MySQL, DAX & Power Query*

![Visitor Count](https://komarev.com/ghpvc/?username=yourusername&label=Profile+Views&color=F7A800&style=flat)

</div>
