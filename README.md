# 🛒 Hill-Top Global Superstores Executive Performance Suite

## 📌 Business Overview
Hill-Top Global Superstores is a multinational retail enterprise generating sales across diverse product categories and customer segments. Despite high sales volume, profitability fluctuates significantly across geographical regions and product lines due to operational inefficiencies and discounting strategies.

This project delivers an interactive executive BI dashboard designed to evaluate revenue performance, regional profit margins, shipping bottlenecks, and product category trends to drive data-backed decision-making.

---

## 🎯 Key Business Objectives
* **Revenue & Profitability Audit:** Identify top-performing product categories, sub-categories, and low-margin regional areas.
* **Customer Segment Performance:** Evaluate purchasing trends across Consumer, Corporate, and Home Office segments.
* **Logistics & Order Fulfillment:** Identify delivery delays and cost leakages across different shipping modes.
* **Data Integrity Restructuring:** Clean duplicate transaction logs and resolve data anomalies to ensure exact financial metrics.

---

## 🧹 Data Cleaning & Transformation
A primary focus of this project was enforcing strict data integrity before building reporting metrics:
* **Raw Dataset:** Started with a retail dataset containing 1,041 transaction records.
* **Deduplication:** Identified and removed 140 duplicate transactions under the `Transaction ID` field.
* **Financial Accuracy Impact:** Retaining these duplicates would have artificially inflated total revenue metrics by ~13%.
* **Final Clean Dataset:** Successfully processed 901 unique, verified rows for analysis.

---

## 🛠️ Data Pipeline & Technical Architecture
1. **Data Ingestion & Quality Control:**
   * Audited raw transaction tables for structural inconsistencies and record duplicates in Power Query.
2. **Data Modeling & Transformation:**
   * Constructed a relational star schema linking Fact Transactions to Dimension Tables.
   * Developed robust DAX measures for dynamic KPIs (Total Revenue, Total Profit, Profit Margin %, YoY Growth, Average Order Value).
3. **Visualization & Dashboard Engineering:**
   * Designed a high-impact executive view emphasizing top-level KPI cards, interactive slicers (Region, Year, Segment), and intuitive drill-down charts.

---

## 💡 Key Business Insights
* **Profit Margin Drain:** While the Furniture category yields high gross revenue, heavy promotional discounting significantly erodes net profitability compared to Technology and Office Supplies.
* **Regional Disparities:** Specific geographic zones demonstrate strong order volume but negative net margins, highlighting localized logistics or pricing challenges.
* **Segment Dominance:** The Consumer segment drives over 50% of overall order volume, whereas Corporate orders generate the highest Average Order Value (AOV).

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Data Modeling, DAX, Interactive Visualization
* **Power Query:** ETL, Data Cleaning & Deduplication
* **Microsoft Excel:** Preliminary Data Auditing

---

## 📊 Executive Dashboard Preview
