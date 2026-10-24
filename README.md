# 📦 Inventory & Supply Chain Management Analysis — Power BI

## 📌 Project Overview

An interactive, single-page Power BI dashboard analyzing inventory and
supply chain performance across 4 regions and 4 product categories.
Built to uncover insights on warehouse capacity, inventory efficiency,
transportation cost, supplier lead time, sales demand, and backorder
fulfillment.

---

## 📊 Dashboard Summary

| Metric                   | Value  |
| ------------------------ | ------ |
| Warehouse Utilization    | 34.08% (target: 75%) |
| Days Sales of Inventory  | 15.56  |
| Inventory Turnover Ratio | 23.47  |
| Backorder Records        | 1,200  |
| Years Covered            | 2020 – 2024 |
| Regions                  | 4      |
| Product Categories       | 4      |

**Regions Covered:** North · West · East · South

**Categories Covered:** Accessories · Clothing · Electronics · Furniture

---

## 🗂️ Dashboard Page

### Inventory & Supply Chain Performance Overview

Analyzes how efficiently inventory is stored, moved, shipped, and
fulfilled, with Region and Category slicers for drill-down.

**Key Visuals:**

- KPI cards (Warehouse Utilization, Days Sales of Inventory,
Inventory Turnover Ratio)
- Gauge chart: Warehouse Utilization against the 75% target
- Clustered column chart: Total Transportation Cost by Region and Category
- Area chart: Units Sold by Year (2020 – 2024)
- Donut chart: Average Lead Time by Category
- Column chart: Count of Backorders by Order Status
- Bar chart: Sum of Inventory Level by Category and Region
- Region and Category slicers

**Key Insights:**

- Warehouse utilization is only 34.08% against a 75% target,
leaving significant unused capacity
- Inventory moves fast: turnover ratio of 23.47 and only 15.56 days
of sales held in stock
- Units sold dropped to near zero in 2021, recovered to about 200K
by 2022, and held steady through 2024
- Transportation cost peaks for Electronics in the West and
Furniture in the North
- Average lead time is similar across categories, from 15.29 days
(Clothing) to 16.60 days (Accessories)
- Of 1,200 backorders, 838 (about 70%) were fulfilled, 248 (about 21%)
are still pending, and 114 (nearly 10%) were canceled

---

## 🔧 Tools & Techniques

| Area         | Details                                               |
| ------------ | ----------------------------------------------------- |
| Tool         | Microsoft Power BI Desktop                            |
| Data Source  | Dataset.CSV                        |
| DAX Measures | Warehouse utilization, days sales of inventory,       |
|              | inventory turnover ratio                              |
| Visuals Used | KPI cards, gauge, clustered column, area chart,       |
|              | donut chart, bar chart, slicers                       |

---

## 💡 Business Questions Answered

1. How well is warehouse capacity being used?
2. How quickly does inventory move and sell?
3. Which regions and categories have the highest transportation cost?
4. How have units sold changed from 2020 to 2024?
5. How long do orders take to arrive, and which categories are slowest?
6. How many backorders are fulfilled, pending, or canceled?
7. How is inventory spread across categories and regions?

---

## 📈 Key Findings Summary

- **Unused Capacity:** Warehouse utilization is 34.08%, far below
the 75% target
- **Fast-Moving Stock:** A turnover ratio of 23.47 and 15.56 days
of sales in stock show inventory sells quickly
- **Demand Recovery:** Units sold fell to near zero in 2021, then
recovered to about 200K and stayed steady through 2024
- **Cost Hotspots:** Electronics in the West and Furniture in the
North carry the highest transportation cost
- **Lead Time:** Accessories take longest (16.60 days) and Clothing
shortest (15.29 days)
- **Backorder Risk:** About 21% of backorders are still pending and
nearly 10% were canceled, so clearing them and raising warehouse
utilization are the main priorities

---

👤 Author : Muhammad Ibtisam
Data Analyst | Power BI · SQL · Python · Excel
🔗 LinkedIn | GitHub

