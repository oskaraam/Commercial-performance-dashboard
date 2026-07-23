# 📊 Andes Retail Group – Commercial Performance Dashboard (2024–2025)

## 📌 Overview
This repository contains the design, data pipeline, and interactive visualizations for the **Andes Retail Group Commercial Dashboard**. Developed in Power BI / Tableau, this project provides a comprehensive analysis of sales performance, revenue trends, and customer segments across key target regions.

The goal of this project is to translate raw transactional data into actionable strategic insights, helping stakeholders identify profitability drivers and diagnose revenue fluctuations over time.

---

## 🛠️ Key Features & Architecture

### 1. Data Preparation & Transformation
* **Data Sources:** Structured and cleaned dataset (`Andes_Retail_Group_2024_2025`).
* **Time Hierarchy:** Configured dynamic time intelligence (*Year > Quarter > Month*).
* **Custom Metrics:** Logic applied for custom categories, including `Nivel_Venta` (*High / Low*) conditional logic.

### 2. Overview Dashboard (Executive Level)
* **High-Level KPIs:** Instant visibility into **Total Revenue**, **Profit Margin**, and **Units Sold** with trend indicators.
* **Interactive Slicers:** Dynamic filtering by year, product category, and geographic region.
* **Geographic & Category Breakdown:** Visual comparison of revenue distribution across countries and product lines.

### 3. Detail & Diagnostic Dashboard
* **Temporal Breakdown:** In-depth drill-down into quarter-over-quarter and month-over-month performance.
* **Segment Analysis:** Revenue distribution broken down by customer type (*e.g., Premium vs. Standard*).
* **Granular Data View:** Interactive metrics table detailing order volumes, customer reach, and average order value (AOV).

---

## 💡 Key Business Insights (SCQA Framework)

Applying the **Situation-Complication-Question-Answer (SCQA)** methodology, the analysis revealed:

* **Situation:** Sales expanded across core retail channels through 2024 and 2025.
* **Complication:** Significant year-over-year revenue drops were detected specifically during Q1 and Q4.
* **Question:** What drove the seasonal drop in performance during these periods?
* **Answer:** Diagnostic filtering showed that reduced spending from the **Premium Customer Segment** in southern regions was the primary contributor to Q1/Q4 revenue dips.

---

   git clone [https://github.com/your-username/andes-retail-dashboard.git](https://github.com/your-username/andes-retail-dashboard.git)
