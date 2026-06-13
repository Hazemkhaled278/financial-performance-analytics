# Financial Performance & Revenue Distribution Analytics Dashboard

## 📌 Business Case & Problem Statement
In global corporate environments, executives often struggle to gain a unified view of financial performance across fragmented international markets. Raw transactional data from disparate business units makes it difficult to track profitability real-time. 

This project solves this challenge by transforming scattered financial records into a centralized, interactive business intelligence platform. It provides senior leadership with instantaneous visibility into corporate health, revenue velocity, and budget tracking.

## 📊 Key Analytical Features
*   **Executive KPI Summary:** Displays core financial metrics including **Total Revenue ($10.21B)**, **EBITDA**, and **Gross Margin%** with dynamic "On Track" visual indicators against strategic forecasts.
*   **Actual vs. Budget Variance:** Features a monthly dual-axis time-series chart combining bar and trend lines to pin-point exact months where performance deviated from the budget targets.
*   **Business Unit Performance Breakdown:** Identifies driving units (e.g., **Platform at +13.0%** and **Data Products at +11.7%**) versus underperforming divisions (e.g., **Marketing at -8.9%** and **Sales at -8.1%**) using localized variance bars.
*   **Geographical Revenue Distribution:** Maps regional performance benchmarks across primary global markets (**EMEA, APAC, and AMER**) to guide resource allocation and market intervention strategies.

## 🛠️ Technical Architecture & Workflow
1.  **Data Extraction & ETL (Power Query):** Cleaned, transformed, and shaped raw financial data. Handled missing entries, standardized currency formats, and established a normalized date dimension table.
2.  **Data Modeling:** Developed a robust Star Schema optimized for analytical performance, separating Fact tables (Transactions/Budgets) from Dimension tables (Geography, Time, Business Units).
3.  **Advanced DAX Modeling:** Formulated complex DAX measures to compute dynamic Actual-vs-Budget variances, year-to-date (YTD) cumulative sums, and conditional formatting rules for visual alerts.
4.  **UI/UX Design:** Engineered a clean, corporate-styled dashboard utilizing custom navigation bars, KPI cards with information tooltips, and a global reset filter mechanism to streamline executive decision-making.

## 📷 Dashboard Preview
![Financial Performance Dashboard](Screenshot 2026-05-11 170619.jpg)

---
*Developed by Hazem Mohamed - Data Analyst & Computer Engineering Student.*
