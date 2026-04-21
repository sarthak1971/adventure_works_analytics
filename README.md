# 📊 Adventure Works Sales Analysis — Power BI Project

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📖 Project Overview

An end-to-end business intelligence solution built in **Power BI** to analyze Adventure Works' sales performance, customer behavior, product profitability, and regional trends. The project covers the full BI lifecycle — from raw data ingestion and cleaning to data modeling, DAX development, and interactive dashboard creation.

---

## 🎯 Business Objectives

- Analyze overall **sales and revenue performance**
- Identify **top-performing products** and categories
- Understand **customer purchasing behavior**
- Evaluate **regional and time-based** sales trends

---

## 📁 Project Structure

```
Adventure_Works_PowerBI/
│
├── Adeventure_works.pbix                          # Main Power BI report file
├── Adventure_Works_Power_BI_Project_Documentation.pdf  # Project documentation
└── README.md                                      # Project overview (this file)
```

---

## 🗂️ Data Sources

The dataset follows a **relational structure** and includes the following tables:

| Table | Description |
|---|---|
| Sales (Fact) | Core transactional sales records |
| Product | Product details and categories |
| Customer | Customer demographics and segments |
| Geography | Regional and location data |
| Date | Calendar table for time intelligence |

---

## 🧹 Data Cleaning & Preparation

- Removed unnecessary and duplicate records
- Handled missing values
- Standardized column names for consistency
- Corrected data types across all tables

---

## 🗃️ Data Modeling

- Implemented a **Star Schema** design
- Established relationships between fact and dimension tables
- Created a dedicated **Date table** to enable time intelligence functions

---

## 📐 DAX Measures & KPIs

| Measure | Description |
|---|---|
| **Total Sales** | Sum of all sales transactions |
| **Total Revenue** | Overall revenue generated |
| **Total Profit** | Revenue minus cost |
| **Profit Margin (%)** | Profit as a percentage of revenue |
| **Total Orders** | Count of all orders placed |
| **Average Order Value (AOV)** | Average revenue per order |
| **Year-over-Year Growth** | YoY % change in sales |

---

## 📊 Dashboard & Visualizations

- **KPI Cards** — Snapshot of core business metrics
- **Sales Trends** — Time-series analysis of revenue and orders
- **Category & Sub-category Performance** — Drill-down product analysis
- **Regional Analysis** — Geographic breakdown of sales performance

---

## 💡 Key Insights

- **High-margin products** are the primary drivers of overall profitability
- **Seasonal trends** significantly impact sales volumes across periods
- Certain **regions consistently outperform** others in revenue generation

---

## ✅ Business Recommendations

1. **Focus on high-performing categories** to maximize revenue contribution
2. **Optimize inventory region-wise** based on demand patterns
3. **Promote high-margin products** through targeted campaigns to improve profitability

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Data modeling, DAX, and dashboard creation |
| Power Query (M) | Data transformation and cleaning |
| DAX | Custom measures and KPIs |
| Star Schema | Data modeling methodology |

---

## 🚀 Getting Started

1. **Clone or download** this repository
2. Open **`Adeventure_works.pbix`** in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. If prompted, refresh the data source connections
4. Explore the report pages and interact with the visuals

> **Note:** Power BI Desktop is free to download. A Power BI Pro or Premium license is required to publish and share the report via the Power BI Service.

---

## 📄 Documentation

For a detailed walkthrough of the project methodology, refer to:
**`Adventure_Works_Power_BI_Project_Documentation.pdf`**

---

## 📬 Contact

Feel free to reach out for any queries or collaboration opportunities.

---

*This project demonstrates strong proficiency in data modeling, DAX development, and data visualization using Power BI.*
