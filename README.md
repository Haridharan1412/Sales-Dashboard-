<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--  HEADER BANNER — capsule-render waving with textBg animation  -->
<!--  FIX: replaced invalid `animation=twinkling` (not a valid     -->
<!--  root param) with `textAnimation=twinkling` which is correct  -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Sales%20Insights%20Dashboard&fontSize=48&fontColor=fff&textBg=false&animation=twinkling&fontAlignY=40&desc=Power%20BI%20%7C%20MySQL%20%7C%20DAX%20%7C%20Data%20Analytics&descAlignY=62&descSize=18" width="100%"/>

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--  TYPING SVG — demolab.com                                     -->
<!--  FIX 1: removed emoji chars from `lines=` (break URL parse)  -->
<!--  FIX 2: replaced `%` with %25 inside line text               -->
<!--  FIX 3: kept color without `#` prefix (correct for this API) -->
<!--  FIX 4: wrapped in <a> tag so GitHub renders it as an image  -->
<!-- ═══════════════════════════════════════════════════════════════ -->
<a href="https://github.com/yourusername/sales-insights-dashboard">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=3000&pause=1000&color=F7A800&center=true&vCenter=true&multiline=false&width=750&height=55&lines=Turning+Raw+Sales+Data+into+Actionable+Insights;Revenue+%7C+Profit+%7C+Performance+KPIs+Dashboard;MySQL+%2B+Power+BI+%2B+DAX+%2B+Power+Query;End-to-End+Data+Analytics+Project" alt="Typing SVG" />
</a>

<br/><br/>

<!-- ── Tech Stack Badges ─────────────────────────────────────────── -->
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)

<br/>

<!-- ── Static Informational Badges ──────────────────────────────── -->
![Made With](https://img.shields.io/badge/Made%20With-Power%20BI%20%26%20SQL-F7A800?style=flat-square&logo=powerbi)
![Dataset](https://img.shields.io/badge/Dataset-MySQL%208.0-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Sales%20Analytics-0078D4?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

<br/>

> **An end-to-end Sales Analytics project** — from raw MySQL data to a production-ready, multi-page interactive Power BI dashboard that delivers actionable revenue, profit, and performance intelligence across 15+ Indian markets.

</div>

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



---

### 🔑 Page 1 — Key Insights (Revenue & Sales Overview)

![Image Alt](https://github.com/Haridharan1412/Sales-Dashboard-/blob/f3852cd94fb6dc4a266541c632fe0d2eb0e26a6a/Key%20Insights.png)

**Overview of total revenue (₹142M), sales quantity (350K units), revenue by market, top 5 customers, and top 5 products for 2020.** Delhi NCR dominates revenue at ₹78M (54.7%), while Electricalsara Stores is the #1 customer at ₹66M. Revenue peaked in Feb–Mar 2020 and declined sharply through June.

---

### 💹 Page 2 — Profit Analysis (Profitability Deep Dive)

![Image Alt](https://github.com/Haridharan1412/Sales-Dashboard-/blob/281ea214a1e1a1eebad9795af3e98fdbab6b92dd/Profit%20Analysis.png)

Multi-dimensional profitability view** showing Revenue Contribution %, Profit Contribution % by market, and a customer-level profit margin table. Lucknow shows a **-2.7% revenue contribution** — the only loss-making market. Epic Stores records **-4.7% profit margin**, signaling a damaging customer relationship.

---

### 🏆 Page 3 — Performance Insights 

![Image Alt](https://github.com/Haridharan1412/Sales-Dashboard-/blob/c294e7f19e0a2bf390276a349473bf8b9365748b/Performance%20Insights.png)

Year-over-year revenue trend** with profit margin % overlay, plus a full customer breakdown table showing Revenue, Revenue Contribution %, Profit Margin Contribution %, and Profit Margin %. Current revenue consistently trails prior-year benchmarks across all 2020 months.

---

### 🗂️ Data Model — Star Schema Architecture

Power BI star schema** connecting the `Sales Transactions` fact table to five dimension tables: Customers, Products, Markets, Date, and Profit Target — optimized for fast DAX calculations and clean drill-through analysis.

---

## 💡 Key Insights

### 📈 Revenue Trends
- Total revenue for the 2020 filtered period: **₹142M** across **350K** units sold
- Revenue peaked around **Feb–Mar 2020** (~₹27M/month), then dropped sharply to ~₹15M by June — likely reflecting COVID-19 disruption
- Year-over-Year comparison shows consistent under-performance in H1 2020 versus the prior-year baseline

### 💰 Profit Analysis
- Total Profit Margin for 2020: **₹2.1M** at an overall margin of ~**1.4%**
- **Mumbai** leads profit contribution at 23.9%, followed by **Delhi NCR** at 22.1% and **Ahmedabad** at 19.0%
- **Lucknow** is the only market with a **negative revenue contribution (-2.7%)** — an urgent red flag
- **Epic Stores** records **-4.7% profit margin** and **-6.8% profit margin contribution** — a loss-generating customer relationship

### 🏪 Top-Performing Customers

| Rank | Customer | Revenue | Revenue Contribution | Profit Margin % |
|------|----------|---------|---------------------|-----------------|
| 🥇 1 | Electricalsara Stores | ₹6,56,41,977 | 46.2% | 0.4% |
| 🥈 2 | Excel Stores | ₹79,28,385 | 5.6% | 3.3% |
| 🥉 3 | Premium Stores | ₹58,99,748 | 4.1% | 0.5% |
| 4 | Electricalslytical | ₹55,37,904 | 3.9% | 0.5% |
| 5 | Info Stores | ₹50,64,374 | 3.6% | 3.2% |

> ⚠️ **Critical Finding:** Electricalsara Stores drives **46.2% of total revenue** but at only **0.4% profit margin** — a dangerous revenue concentration with unsustainably thin profitability.

### 🗺️ Regional Performance
- **Delhi NCR** contributes 54.7% of revenue but only 22.1% of profits → significant margin compression in the North zone
- **Bhubaneshwar (10.5%)**, **Hyderabad (6.7%)**, and **Chennai (6.3%)** show the strongest balanced performance contributions
- **Surat (0.1%)** and **Kanpur (0.5%)** remain low-priority markets with minimal impact

### 📦 Top Products
- **(Blank)** product category accounts for **₹65M** — a critical **data quality issue** in product classification
- **Prod047** and **Prod061** are the top named products at ₹4M each
- Over-reliance on unclassified SKUs masks true category-level performance

---

## 📊 KPIs Tracked

<div align="center">

| KPI | Value (2020) | Visual Type |
|-----|-------------|-------------|
| 💵 Total Revenue | ₹142M | KPI Card |
| 📦 Sales Quantity | 350K Units | KPI Card |
| 💰 Total Profit Margin | ₹2.1M | KPI Card |
| 📉 Profit Margin % | 1.4% | Line — Combo Chart |
| 🔄 Revenue LY (Prior Year) | Dynamic | Bar Chart (Grey) |
| 🎯 Profit Target | Configurable % | Slicer + Target Diff |
| 🏪 Revenue by Market | Per Market | Horizontal Bar |
| 👥 Revenue by Customer | Per Customer | Table + Bar |
| 🗺️ Revenue Contribution % | Per Market / Customer | Stacked Bar |
| 📈 Profit Contribution % | Per Market | Horizontal Bar |

</div>

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Role | Details |
|------|------|---------|
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) | Dashboard & Visualizations | Desktop — 3 interactive report pages |
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) | Data Storage & Querying | v8.0.20 — 5 relational tables |
| ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat&logo=microsoft&logoColor=white) | Calculated Measures & KPIs | Profit Margin %, norm_sales_amount, YoY |
| ![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=flat&logo=microsoftexcel&logoColor=white) | ETL & Data Transformation | M Language — USD→INR normalization |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white) | Supplementary Analysis | Profit Target table source |

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
│ customer_type│      │ customer_code  (FK)  │      │ zone              │
└──────────────┘      │ market_code    (FK)  │      └──────────────────┘
                      │ norm_sales_amount    │
┌──────────────┐   1  │ order_date     (FK)  │      ┌──────────────────┐
│sales products │◄────┤ product_code   (FK)  │      │  Profit Target   │
│ ──────────── │      │ Profit_Margin        │      │ ──────────────── │
│ product_code │      │ ProfitMargin%        │      │ Profit Target    │
│ product_type │      └──────────────────────┘      │ Profit Target Val│
└──────────────┘                                    │ Target Diff      │
                                                    └──────────────────┘
```

| Table | Rows (approx.) | Description |
|-------|---------------|-------------|
| `customers` | 38 | Customer master — Brick & Mortar (19) + E-Commerce (19) |
| `markets` | 17 | Market codes, city names, zones (incl. NY & Paris — filtered out) |
| `products` | ~279 | Product codes and types |
| `date` | ~1,461 | Daily date spine Jun 2017 → Jun 2020 |
| `transactions` | ~150,000 | Order-level sales with cost price and currency |

---

## 🔍 SQL Analysis

### Database Setup

```sql
CREATE DATABASE IF NOT EXISTS `sales`;
USE `sales`;
```

### Exploratory Queries

**1. All Customer Records**
```sql
SELECT * FROM customers;
-- Returns all 38 customers across Brick & Mortar and E-Commerce types
```

**2. Total Customer Count**
```sql
SELECT COUNT(*) FROM customers;
-- Result: 38 customers
```

**3. Chennai Market Transactions** *(market code: Mark001)*
```sql
SELECT * FROM transactions WHERE market_code = 'Mark001';
```

**4. Distinct Products Sold in Chennai**
```sql
SELECT DISTINCT product_code
FROM transactions
WHERE market_code = 'Mark001';
```

**5. USD Transactions** *(Multi-currency handling)*
```sql
SELECT * FROM transactions WHERE currency = 'USD';
-- Surfaces international/export transactions for normalization
```

**6. All 2020 Transactions with Date Dimension**
```sql
SELECT transactions.*, date.*
FROM transactions
INNER JOIN date ON transactions.order_date = date.date
WHERE date.year = 2020;
```

**7. Total Revenue in 2020** *(INR + USD)*
```sql
SELECT SUM(transactions.sales_amount)
FROM transactions
INNER JOIN date ON transactions.order_date = date.date
WHERE date.year = 2020
  AND (transactions.currency = 'INR\r' OR transactions.currency = 'USD\r');
-- \r suffix present due to Windows line endings in the raw CSV import
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
| USD transactions mixed with INR | Normalized in Power Query via `norm_amount` column |
| Markets: New York & Paris records | Filtered out — analysis scoped to Indian markets only |
| Blank product codes | Flagged as a data quality issue for upstream fix |

### ⚙️ Power Query Transformation — USD → INR Normalization

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

> Converts USD transactions to INR at a fixed rate of **₹75 per USD**, enabling accurate multi-currency revenue aggregation across all markets.

---

## ✨ Dashboard Features

| Feature | Description |
|---------|-------------|
| 📅 **Year & Month Slicers** | Filter all visuals simultaneously by year (2017–2020) and month |
| 📊 **Revenue Trend Line** | Interactive time-series with Jan–Jun monthly granularity |
| 🔄 **YoY Comparison** | Side-by-side current vs. last-year revenue bars + profit margin % overlay |
| 🎯 **Profit Target Toggle** | Adjustable profit target (%) slicer that dynamically recalculates Target Diff |
| 🏪 **Market Drill-Through** | Click any market to drill into customer-level detail for that region |
| 👥 **Customer Performance Table** | Revenue, Contribution %, Profit Margin Contribution %, and PM% per customer |
| 🗺️ **Zone-Level Aggregation** | Markets grouped by North / South / Central zones |
| 📄 **Multi-Page Navigation** | Three report pages: Key Insights · Profit Analysis · Performance Insights |
| 🔴 **Negative Margin Highlighting** | Conditional formatting flags loss-making markets in red |

---

## 💼 Business Impact

### How the Dashboard Drives Decisions

| Decision Area | Before Dashboard | After Dashboard |
|--------------|-----------------|-----------------|
| Revenue Visibility | Verbal updates from regional managers | Real-time ₹142M tracker with monthly trend |
| Market Prioritization | Equal attention across all markets | Focus on Delhi NCR (54.7% revenue share) |
| Loss Prevention | Unknown loss-making relationships | Lucknow (-2.7%) and Epic Stores (-4.7%) flagged immediately |
| Currency Risk | USD/INR mixing distorted totals | `norm_amount` ensures accurate multi-currency aggregation |
| Customer Strategy | No profitability tiering | 46.2% revenue concentration risk identified in one customer |

### 📋 Strategic Recommendations

1. **Re-negotiate Electricalsara Stores contract** — 46.2% revenue at 0.4% margin is unsustainable; volume-based pricing revision is critical.
2. **Exit or restructure Lucknow operations** — The only negative-contribution market (-2.7%) requires a cost-structure review or market exit decision.
3. **Resolve the Blank product category** — ₹65M in unclassified revenue hides true product performance; upstream data entry controls are needed.
4. **Protect Mumbai & Ahmedabad margins** — These markets punch above their revenue weight (23.9% and 19.0% profit contribution respectively).
5. **Investigate the June 2020 revenue cliff** — A sharp month-on-month decline from May to June requires root-cause analysis (COVID-19 impact vs. operational disruption).

---

## 👤 Author

<div align="center">

<!-- ══════════════════════════════════════════════════════════════ -->
<!--  AVATAR FIX — ui-avatars.com is reliable and needs no repo.  -->
<!--  Replace "Your+Name" with your actual name in the URL below. -->
<!-- ══════════════════════════════════════════════════════════════ -->
<img src="https://ui-avatars.com/api/?name=Your+Name&size=100&background=F7A800&color=fff&rounded=true&bold=true" width="100px" alt="Author Avatar"/>

### Haridharan KS

*Data Analyst · Power BI Developer · SQL Enthusiast*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hari-dharan-ks-64325a287/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Haridharan1412)

</div>

---

<div align="center">

<!-- Footer waving banner — no text, just the wave shape -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

*Built with 💛 using Power BI · MySQL · DAX · Power Query*

</div>
