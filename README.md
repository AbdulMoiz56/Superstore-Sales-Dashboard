# Superstore-Sales-Dashboard
# 📊 SuperStore Sales Dashboard & Forecasting

An interactive Power BI dashboard built to analyze retail sales performance, profitability, and delivery efficiency — with time-series forecasting to project future sales trends.

![Dashboard Overview](screenshots/dashboard-overview.png)

---

## 🎯 Objective

To contribute to data-driven business decision-making by analyzing retail sales data and applying time-series forecasting techniques to predict future sales trends, while surfacing actionable insights across regions, categories, and delivery performance.

---

## 🧩 Key Features

- **Interactive KPI Dashboard** — Sales, Profit, Order Count, and Average Delivery Days at a glance.
- **Multi-level Filtering** — Slice and drill down by Region, Category, Sub-Category, Segment, and Payment Mode.
- **Sales Forecasting** — 15-day sales forecast built on 2 years of historical order data using Power BI's time-series forecasting engine.
- **YoY Trend Analysis** — Monthly sales and profit trends compared year-over-year to identify seasonal patterns.
- **Geographic Insights** — Sales and profit distribution mapped across 49 U.S. states.
- **Custom DAX Logic** — Purpose-built measures and calculated columns for sales aggregation and delivery-time analysis.

![Forecasting Page](screenshots/forecasting-page.png)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard design, visualization, forecasting |
| **DAX** | Custom measures and calculated columns |
| **Excel / CSV** | Source dataset |

---

## 📈 Dashboard Breakdown

**Page 1 — Sales Overview**
- Sales by Payment Mode, Segment, and Region (donut charts)
- Monthly Sales & Profit by Year-over-Year (trend lines)
- Sales by Category & Sub-Category
- Geographic sales/profit distribution by state

**Page 2 — Forecasting**
- 15-day sales forecast with confidence interval
- Sales by State (ranked bar chart)
- Historical sales trend line for context

---

## 🧮 DAX Measures & Calculated Columns

See [`dax-measures.md`](./dax-measures.md) for full DAX code, including:
- `Total Sales` — aggregated using `SUMMARIZE()` for forecasting
- `AvgDelivery` — calculated using `DATEDIFF()` for delivery-time KPIs

---

## 📂 Repository Structure
Superstore-Sales-Dashboard/
├── README.md
├── dax-measures.md
├── SuperStore_Dashboard.pbix
├── SuperStore Sales DataSet.xlsx
├── dashboard-overview.png
└── forecasting-page.png

---

## 📊 Dataset

The dataset used is the publicly available **SuperStore Sales Dataset**, containing 5,900+ records across orders, shipping, customers, and product categories.

---

## 🚀 How to View

1. Download `SuperStore_Dashboard.pbix`
2. Open in **Power BI Desktop** (free download from Microsoft)
3. Explore the Dashboard and Forecasting pages interactively

---

## 👤 Author

**Abdul Moiz**
Data Analyst | Power BI • SQL • Python
📧 moiz13072004@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/amabdulmoiz) | [GitHub](https://github.com/AbdulMoiz56)
