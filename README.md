# 📊 AtliQ Hardware — Enterprise Business Intelligence Dashboard

An end-to-end multi-department Power BI analytics solution built for **AtliQ Hardware** (a global computer hardware manufacturer), providing executive visibility across Finance, Sales, Marketing, and Supply Chain operations.

## 🎯 Project Overview
This dashboard tracks **$3.74B in Net Sales**, **38.08% Gross Margin**, **-13.98% Net Profit**, and **81.17% Forecast Accuracy**, comparing actual performance against benchmarks (BM), last year (LY), and targets across global regions (APAC, EU, LATAM, NA).

## 📑 Report Views & Key Insights
1. **Executive View:** High-level KPI summary, revenue split by division (PC, P&A, N&S) and channel (Retailer, Direct, Distributor), regional sub-zone breakdown, and PC market share trends against competitors.
2. **Finance View (P&L):** Complete Profit & Loss statement detailing Gross Sales ($7,370.14M), pre/post-invoice deductions, COGS ($2,313.29M), operational expenses, and Net Sales trends over time.
3. **Sales View:** Customer performance matrix comparing Net Sales vs. Gross Margin %, top customer rankings (Amazon, AtliQ Exclusive, Flipkart), and unit economics breakdown.
4. **Marketing View:** Product segment performance matrix (Notebooks, Peripherals, Desktops, Accessories), regional profitability, and waterfall margin analysis.
5. **Supply Chain View:** Forecast accuracy tracking (81.17%), Net Error (-3,472.7K), Absolute Error (6,899.0K), and inventory risk classification (`EI` - Excess Inventory vs. `OOS` - Out of Stock) by customer and product segment.

## 🛠️ Tools & Technical Concepts Used
* **Power BI Desktop:** Multi-page navigation panel, dynamic slicers (Year, Quarter, YTD/YTG, vs LY/Target), conditional formatting, scatter performance matrices, and waterfall charts.
* **Power Query & Data Modeling:** Star-schema modeling connecting fact tables (Sales, Forecast, Operational Expenses) with dimension tables (Customer, Product, Market, Date).
* **DAX (Data Analysis Expressions):** Custom financial measures for P&L line items, benchmark comparisons, forecast error calculations, and dynamic metric switching.

## 📸 Dashboard Previews

### Executive View
![Executive View](screenshots/01_Executive_View.jpg)

### Finance View (Profit & Loss)
![Finance View](screenshots/02_Finance_View.jpg)

### Sales View
![Sales View](screenshots/03_Sales_View.jpg)

### Marketing View
![Marketing View](screenshots/04_Marketing_View.jpg)

### Supply Chain View
![Supply Chain View](screenshots/05_Supply_Chain_View.jpg)

## 📂 Repository Structure
* `/dashboard` — Contains the `.pbix` Power BI project file.
* `/screenshots` — High-resolution previews of all five report views.
* `/data` — Underlying dataset files used for modeling and analysis.
