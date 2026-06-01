# ☕ Coffee Sales Analysis & Dashboard

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white) ![Data Analysis](https://img.shields.io/badge/Data_Analysis-Processing_%26_Visualization-blue?style=for-the-badge)

## 📌 Executive Summary
In the modern retail landscape, data is the new oil. This project explores a robust **Coffee Orders** dataset, demonstrating a passion for transforming messy data into actionable business insights. The objective was to clean, link, and analyze transactional records, customer details, and product catalogs contained within a single workbook to build an interactive dashboard tracking global sales performance, loyalty habits, and historical revenue trends.

---

## 🛠️ Data Processing & Methodology
To ensure accurate reporting and dynamic visualization, raw relational sheets were structured, joined, and processed completely inside a unified Excel workbook before being mapped to the final dashboard interface.

**1. Data Architecture & Modeling:**
* Consolidated three raw relational datasets into dedicated sheets within the workbook: `orders`, `customers`, and `products`.
* Modeled data relationships dynamically using lookup formulas (`XLOOKUP`/`VLOOKUP`) to map product pricing, coffee types, roast details, and customer locations directly into the master transaction tracking sheet.

**2. Data Cleaning & Aggregation:**
* Standardized date formatting and isolated data rows across a multi-year timeframe (2019–2022) to enable clean time-series analysis.
* Generated dedicated working sheets utilizing targeted Pivot Tables to aggregate total revenue by year, geographic markets, and individual customer spend.

**3. Dashboard Architecture:**
* Designed a centralized, professional dashboard sheet featuring a time-series line chart for historical tracking, alongside horizontal bar and donut charts for categorical distributions.
* Connected interactive Slicers (**Roast Type**, **Size**, and **Loyalty Card** status) across all Pivot Charts to allow stakeholders to dynamically filter performance and drill down into customer segments.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Performance |
| :--- | :--- |
| 💰 **Total Sales Revenue** | $45,134.26 |
| 📦 **Total Quantity Sold** | 3,551 Units |
| 👥 **Unique Customers** | 913 |
| 🏆 **Top Performing Market** | United States ($35,639 - ~79% share) |
| ☕ **Best Selling Coffee Type** | Excelsa (27% revenue share) |

---

## 💡 Key Sales Insights

| Focus Area | Key Finding | Insight / Trend |
| :--- | :--- | :--- |
| 📍 **Geographic Dominance** | The **United States** heavily dominates the revenue mix, generating $35,639 compared to Ireland ($6,697) and the United Kingdom ($2,799). | Core business health relies almost entirely on US sales; marketing campaigns and localized inventory strategies should prioritize this region. |
| 💳 **Loyalty Impact** | Slicer filtration reveals that **Loyalty Card holders** maintain robust, recurring purchase cycles across all coffee types. | The loyalty infrastructure provides a highly predictable revenue stream, proving its retention value. |
| 📅 **Historical Trends** |Sales show intense monthly volatility, with individual coffee types frequently peaking between **$600** and **$850+** in a single month. |Demand is highly cyclical. Excelsa dominated the peak surges in mid-2019, whereas Arabica and Liberica experienced explosive, back-to-back record peaks between late 2021 and early 2022. |
| ☕ **Product Layout** | **Excelsa ($12.3K)** and **Liberica ($12.0K)** lead overall revenue generation, closely followed by Arabica ($11.7K), with Robusta ($9.0K) trailing behind. | Production and procurement strategies should lean heavily into maximizing stock for premium types like Excelsa to avoid high-margin out-of-stock scenarios. |

---

## 🖥️ Dashboard Preview

![Coffee Sales Dashboard](.assets/coffee_orders_dashboard.png)

---

## 📂 Repository Contents
* `coffee_orders.xlsx`: The main workbook containing all project components:
  * `orders`, `customers`, `products`: Raw transaction and master relationship data sheets.
  * `Pivot Tables`: Dedicated calculation sheets processing behind-the-scenes metrics.
  * `Dashboard`: The clean, interactive consumer-ready UI panel complete with dynamic charts and connected slicers.
* `assets/`: Contains dashboard screenshot used for documentation.

