# ShopNest ERP Analytics Dashboard — Tableau

![Tableau](https://img.shields.io/badge/Tableau-Public-blue)
![ERP](https://img.shields.io/badge/ERP-Analytics-orange)
![Oracle](https://img.shields.io/badge/Oracle-Fusion_SCM-red)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Live Dashboard

**[View on Tableau Public](https://public.tableau.com/app/profile/neha.reddy.pannala/viz/ShopNest-ERP-Procurement-Dashboard/ShopNestERPDashboard?publish=yes)**


## Overview

This Tableau dashboard replicates the **Oracle Analytics Cloud (OAC)** procurement and inventory reports used by ERP analysts inside Oracle Fusion Cloud SCM.

Built on simulated ERP data for **ShopNest Inc.** — a fictional e-commerce company with $120M annual revenue and 3 warehouses across New York, Chicago, and Los Angeles.


## Dashboard Views

| Chart | Description | Oracle OAC Equivalent |
|-------|-------------|----------------------|
| Inventory Status Heatmap | Stock levels and status across 3 warehouses | Inventory Management Dashboard |
| Supplier Spend Ranking | Total procurement spend ranked by supplier | Supplier Spend Analysis |
| Stock vs Reorder Point | Available stock vs reorder threshold per item | Inventory Planning Report |
| Category Spend Breakdown | Procurement spend split by product category | Spend by Category (Donut) |
| Monthly PO Trend | Supplier spend trend across Jan–Mar 2026 | Procurement Trend Report |


## Key Insights from the Dashboard

- **3 items** are critically below reorder point across all warehouses — Standing Desk, Office Chair, Monitor 27"
- **TechSource Global** is the top supplier at $51,000 spend — 38.5% of total procurement budget
- **Electronics** accounts for 62.9% of total category spend
- **FastParts Co** has only 1 PO in Jan 2026 — no activity in Feb or Mar, flagged for review
- Total procurement spend across all suppliers: **$143,400** over 3 months


## Data Source

Built from 4 flat data tables exported from the ShopNest ERP database:

| Sheet | Rows | Description |
|-------|------|-------------|
| Tableau_Inventory | 13 | Stock levels per item per warehouse |
| Tableau_Supplier_Spend | 5 | Supplier spend summary |
| Tableau_PO_Trend | 8 | Purchase order history with dates |
| Tableau_Category_Spend | 8 | Spend by item and category |

Data modelled after Oracle Fusion SCM tables — mirrors real ERP data structure.


## Tools & Technologies

Tableau Public · Microsoft Excel · Oracle Fusion Cloud SCM · ERP Analytics · Procure-to-Pay



*Built as a portfolio project to demonstrate ERP analytics and data visualization skills.*
*Simulates Oracle Analytics Cloud (OAC) dashboards used in Oracle Fusion Cloud SCM implementations.*
