# Excel_Data_Analysis_Projects
# 📊 Market Research & Business Analytics Portfolio

## 📂 Project 1: Multi-Channel Marketing ROI Dashboard
**Domain:** Marketing Analytics | **Focus:** Ad Spend Efficiency

### ❓ The Business Problem
A digital marketing team is running ads across Facebook, Google, and Email but lacks a unified view of performance. They need to know which channel delivers the highest Return on Ad Spend (ROAS) to optimize their budget.

### 🛠 The Solution
I built a dynamic dashboard that aggregates campaign data to calculate key efficiency metrics.
* **Data Cleaning:** Converted raw logs into Official Excel Tables for scalability.
* **Advanced Metrics:** Engineered `CTR`, `CPC`, and `True ROAS` using Calculated Fields (avoiding "averages of averages").
* **Visualization:** Created a Dual-Axis Combo Chart to compare Spend (Volume) vs. ROAS (Efficiency) simultaneously.

**Key Insight:** Google Search Terms drove the highest revenue efficiency (4.8x ROAS), while other channels lagged despite high volume.

## 📂 Project 2: Customer Value & Retention (RFM Model)
**Domain:** Market Research | **Focus:** Customer Segmentation & Churn Risk

### ❓ The Business Problem
The sales team needed to identify VIP customers for rewards and "at-risk" customers for retention campaigns, but customer data was cluttered with duplicate transaction rows.

### 🛠 The Solution
I developed an RFM (Recency, Frequency, Monetary) segmentation model.
* **ETL Process:** Used Pivot Tables to "flatten" duplicate transactions into unique customer profiles.
* **Logic Modeling:** Applied `Nested IF` functions to automate customer tagging (VIP vs. Regular vs. At Risk).
* **Risk Quantification:** Used `SUMIF` to calculate the exact dollar value of potential revenue loss from at-risk clients.

**Key Insight:** Identified distinct customer segments, enabling targeted email campaigns that address specific churn risks.

## 📂 Project 3: Sales Variance & Trend Forecasting
**Domain:** Business Analysis | **Focus:** Budgeting & Predictive Analytics

### ❓ The Business Problem
Executives required a clear view of monthly performance against targets to understand variance and predict future quarters.

### 🛠 The Solution
I created a variance tracker with built-in forecasting tools.
* **Variance Analysis:** Calculated absolute ($) and relative (%) variance to standardize performance reporting.
* **In-Cell Visualization:** Implemented Conditional Formatting (Data Bars) for instant "good/bad" visual scanning.
* **Forecasting:** Applied Linear Trendlines to historical data to project sales performance 3 months into the future.

**Key Insight:** The model provides an early warning system for budget misses, allowing management to pivot strategy mid-quarter.

## 🧰 Technical Skills Matrix

| Skill Category | Excel Features Used |
| :--- | :--- |
| **Data Cleaning & ETL** | Power Query concepts, Remove Duplicates, Text-to-Columns |
| **Data Modeling** | Pivot Tables, Official Tables (Ctrl+T), Structured References |
| **Advanced Logic** | `IF`, `NESTED IF`, `SUMIF/S`, `GETPIVOTDATA` |
| **Time-Series Analysis** | Date Math (`TODAY`, `EOMONTH`), Trendlines, Forecasting |
| **Visualization** | Combo Charts (Dual Axis), Slicers, Conditional Formatting, Data Bars |
