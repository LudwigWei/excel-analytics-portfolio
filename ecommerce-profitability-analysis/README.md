# 🛒 E-commerce Sales & Profitability Dashboard

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Processing_%26_Visualization-blue?style=flat-square)

## 📌 Executive Summary
This project analyzes four years (2011–2014) of transactional data for a major e-commerce retailer using Microsoft Excel. Working with a pre-cleaned dataset of nearly 10,000 records, the objective was to extract immediate business value through advanced data processing and dynamic visualization. The resulting dashboard uncovers profitability drivers, geographical performance, and category-level trends to help stakeholders optimize discount strategies and focus on high-margin product lines.

---

## 🛠️ Data Processing & Methodology
Because the dataset was already clean and standardized, the technical focus of this project was on complex aggregations, logic building, and visual architecture.

**1. Data Exploration & Structuring:**
* Conducted Exploratory Data Analysis (EDA) on 9,994 individual transaction records to identify key dimensions (Temporal, Geographical, Financial).
* Structured the dataset to support complex, multi-layered Pivot Tables without lag.

**2. Aggregation & Metrics Calculation:**
* Built targeted Pivot Tables to evaluate Year-over-Year (YoY) growth, category performance, and state-level revenue.
* Calculated critical supplementary KPIs, such as overall profit margins and the specific impacts of discounts on net profitability.

**3. Dashboard Architecture:**
* Built a centralized, interactive dashboard featuring KPI scorecards, YoY trendlines, and a dynamic Top % Subcategories view.
* Implemented Slicers to allow users to filter the entire dashboard by Year, Region, and Customer Segment instantly.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Performance |
| :--- | :--- |
| 💰 **Total Sales Revenue** | $2,297,200 |
| 💵 **Total Net Profit** | $286,397 |
| 🛒 **Total Items Sold** | 37,873 |
| 📦 **Total Orders** | 9,994 |
| 📊 **Overall Profit Margin** | 12.47% |

---

## 💡 Actionable Business Insights

| Focus Area | Key Finding | Strategic Recommendation |
| :--- | :--- | :--- |
| 💻 **Category Profitability** | **Technology** is the strongest performer, accounting for **36.40%** of total sales revenue ($836K) and driving the vast majority of the net profit ($145K). | Increase inventory investments and marketing spend for high-margin Technology subcategories. |
| 🪑 **The Furniture Problem** | **Furniture** generates massive revenue ($741K) but yields extremely poor profits (only $18K), indicating a margin crisis. | Audit shipping costs, supplier agreements, and excessive discounting practices within the Furniture category. |
| 🗺️ **Geographic Dominance** | **California** ($457K) and **New York** ($310K) account for a massive share of total sales, outperforming all other states combined. | Establish localized distribution centers in CA and NY to reduce shipping times and costs for the largest customer bases. |
| 📉 **Discount Impact** | High discount rates in specific regions directly correlate with negative profit margins, effectively erasing sales gains. | Implement strict discount ceilings by category to protect baseline profitability, especially in underperforming states. |

---

## 🖥️ Dashboard Preview
*(The interactive dashboard allows filtering by Year, Region, and Segment Category)*
![E-commerce Dashboard](.ecommerce-profitability-analysis\assets\e-commerce_dashboard.png)

---

## 📂 Repository Contents
* `ecommerce-profitability-analysis.xlsx`: The complete Excel workbook containing the data, Year-over-Year calculations, Pivot Tables, and the final interactive dashboard.
* `assets/`: Contains dashboard screenshot.