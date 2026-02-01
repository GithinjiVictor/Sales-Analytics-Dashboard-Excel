# Sales Operations & Analytics Dashboard 📊

## 📌 Project Overview
This project is an advanced Excel dashboard designed to analyze sales performance for a multi-regional electronics distributor. It transforms raw transactional data into actionable insights, focusing on revenue trends, shipping efficiency, and discount behavior.

**Tools Used:** Microsoft Excel (Pivot Tables, Advanced Formulas, Slicers, Charts)

## 🚀 Key Features

### 1. Data Cleaning & Integrity
- **Automated Error Correction:** Handled negative values in `UnitPrice` and missing entries in `City`/`Salesperson`.
- **Logic Validation:** Corrected `RequiredDate` errors where the delivery date was prior to the order date.

### 2. Scenario Modeling ("What-If" Analysis)
- Built a dynamic **Control Panel** allowing users to adjust:
  - **Inflation Rate (0-15%)**
  - **Discount Cap (0-25%)**
- The model instantly recalculates `Scenario Cost` and `Scenario Revenue` using linked absolute references, enabling real-time stress testing of profit margins.

### 3. Interactive Dashboard
- **KPI Tracking:** Real-time metrics for Total Revenue, Gross Profit, and On-Time Delivery %.
- **Slicers:** Filter the entire report by **Channel** (Retail, Online) and **Product Category**.
- **Visuals:**
  - *Top 10 SKUs* by Revenue.
  - *Regional Performance* breakdown.
  - *Discount Outliers* to identify sales reps exceeding the 20% discount threshold.

## 📂 How to Use
1. Download the file `Excel_Assignment_Githinji Victor Maina.xlsx`.
2. Open the **"Dashboard"** tab to view the main visuals.
3. Locate the **Control Panel** (on the Data sheet or Dashboard) to change the **Inflation %** and watch the margins update.

---
*Completed as part of the LuxDev Academy Data Science Curriculum (Week 1).*
