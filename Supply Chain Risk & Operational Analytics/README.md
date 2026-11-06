# 📊 Supply Chain Risk & Operational Analytics

An end-to-end data analytics project focused on evaluating supply chain performance, identifying delivery risks, analyzing revenue exposure, and generating actionable business insights using **MySQL, Python, and Power BI**.

## 📌 Project Overview

This project analyzes the **DataCo SMART Supply Chain Dataset** to understand operational performance, delivery delays, shipping efficiency, product profitability, and regional supply chain risks.

Using SQL for data analysis, Python for data cleaning and feature engineering, and Power BI for interactive visualization, this project transforms supply chain data into meaningful business insights.

The dashboard helps identify high-risk regions, delayed shipping operations, loss-making products, and revenue exposure to support better operational and business decisions.

## 🎯 Business Problem Statement

Supply chain operations face challenges such as delayed deliveries, inefficient shipping methods, regional performance differences, and product-level financial losses.

Businesses need to understand:

- Which regions have the highest delivery risk?
- Which shipping modes experience the most delays?
- How much revenue is exposed to delivery-related risks?
- Which products generate financial losses?
- What operational improvements can reduce delivery delays and improve profitability?

**Objective:** Analyze supply chain data to identify operational bottlenecks, measure business risks, and provide data-driven recommendations for improving delivery performance and profitability.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL | Data querying, analysis, aggregations, and KPI calculations |
| Python | Data cleaning, feature engineering, and risk scoring |
| Pandas & NumPy | Data manipulation and numerical analysis |
| Jupyter Notebook | Data analysis and Python workflow |
| Power BI | Interactive dashboards and reporting |
| DAX | KPI calculations and business metrics |
| Power Query | Data transformation and preparation |

## 📂 Dataset Information

- **Dataset:** DataCo SMART Supply Chain Dataset
- **Source:** Kaggle
- **Total Records:** 180,519
- **Total Columns:** 53
- **Data Period:** 2015–2018

The dataset includes information about orders, customers, products, sales, shipping methods, delivery performance, and geographical regions.

## 🔄 Project Workflow

### 1. Data Understanding & Preparation
- Imported and explored the supply chain dataset.
- Examined data types, missing values, and duplicate records.
- Identified important business dimensions and performance metrics.

### 2. SQL Analysis – MySQL
- Performed data analysis using SQL queries.
- Calculated order, revenue, profit, and delivery performance metrics.
- Analyzed regional performance and shipping mode efficiency.
- Identified delayed deliveries and loss-making products.
- Prepared aggregated data for further analysis.

### 3. Python Analysis
- Cleaned and transformed the dataset using Pandas and NumPy.
- Performed feature engineering for operational analysis.
- Developed a weighted supply chain risk-scoring approach.
- Prepared analysis-ready tables for Power BI.

### 4. Power BI Dashboard Development
- Connected prepared datasets to Power BI.
- Created calculated measures using DAX.
- Designed interactive dashboards with KPIs, charts, and filters.
- Presented operational performance, delivery risks, and financial insights.

## 📊 Power BI Dashboard

The dashboard contains seven analytical pages:

| Page | Dashboard Analysis |
|---|---|
| 1. Executive Summary | Overall supply chain performance and business KPIs |
| 2. Risk Overview | Regional risk levels and revenue exposure |
| 3. Delivery Performance | On-time and late delivery performance |
| 4. Delay Analysis | Delivery delays and operational patterns |
| 5. Shipping Mode Analysis | Shipping method performance and efficiency |
| 6. Product Risk | Product profitability and loss analysis |
| 7. Action Dashboard | High-priority risks and improvement opportunities |


## 📸 Dashboard Screenshots

### 1. Executive Summary
![Executive Summary](./Screenshot/Executive%20Summary.png)

### 2. Risk Overview
![Risk Overview](./Screenshot/Risk%20Overview.png)

### 3. Delivery Performance
![Delivery Performance](./Screenshot/Delivery%20Performance.png)

### 4. Delay Analysis
![Delay Analysis](./Screenshot/Delay%20Analysis.png)

### 5. Shipping Mode Analysis
![Shipping Mode Analysis](./Screenshot/Shipping%20Mode%20Analysis.png)

### 6. Product Risk
![Product Risk](./Screenshot/Product%20Risk.png)

### 7. Action Dashboard
![Action Dashboard](./Screenshot/Action%20Dashboard%20.png)


## 📈 Key Business Metrics

| KPI | Value |
|---|---:|
| Total Orders | 65,752 |
| Total Revenue | $36.78M |
| Total Profit | $3.97M |
| Profit Margin | 10.78% |
| Late Delivery Rate | 54.83% |
| Revenue at Risk | $20.13M |
| Weighted Revenue at Risk | $22.87M |
| Loss Records | 33,784 |
| Loss Record Percentage | 18.71% |
| Average Shipping Delay | 0.57 Days |

## 🔍 Key Business Insights

### 1. Regional Risk Analysis
- Western Europe recorded the highest regional risk score of **77.12**.
- Its late delivery rate was **55.85%**.
- Revenue at risk reached approximately **$3.29M**.
- This indicates a need for closer monitoring of delivery operations in the region.

### 2. Shipping Mode Analysis
- First Class recorded the highest late delivery rate at **95.32%**.
- Standard Class handled approximately **59.81% of orders**.
- Standard Class had the lowest late delivery rate at **38.07%**.
- Its revenue at risk was approximately **$8.4M**.

### 3. Product Profitability Analysis

The analysis identified three loss-making products:

| Product | Profit |
|---|---:|
| SOLE E35 Elliptical | -$965 |
| Bushnell Pro X7 Jolt Slope Rangefinder | -$256 |
| SOLE E25 Elliptical | -$170 |

These products require further investigation into pricing, costs, and profitability.

### 4. Revenue Risk Analysis
- Revenue at risk was approximately **$20.13M**.
- Weighted revenue at risk was approximately **$22.87M**.
- These metrics help highlight the financial exposure associated with supply chain performance.

## ⚠️ Supply Chain Risk Scoring

A weighted risk-scoring approach was developed to evaluate supply chain risk using four factors:

| Risk Factor | Weight |
|---|---:|
| Late Delivery Rate | 35% |
| Revenue at Risk | 25% |
| Average Delay Days | 20% |
| Loss Profit Impact | 20% |

The factors were normalized to a 0–100 scale and combined into an overall risk score. A volume confidence weight was also applied to account for differences in order volume.

## 💡 Business Recommendations

- **Improve high-risk regional operations:** Investigate delivery bottlenecks in Western Europe.
- **Review First Class shipping performance:** Examine the reasons behind its high late delivery rate.
- **Monitor revenue exposure:** Prioritize operational improvements in areas with high revenue at risk.
- **Review loss-making products:** Evaluate pricing, procurement, and operational costs.
- **Strengthen delivery monitoring:** Track late delivery rates and average shipping delays regularly.

## 📁 Project Structure

```text
Supply Chain Risk & Operational Analytics/
│
├── Dataset/
│   ├── action_priority_table.csv
│   ├── delivery_risk_by_region.csv
│   ├── kpi_summary.csv
│   ├── product_profitability_risk.csv
│   └── shipping_mode_risk.csv
│
├── Python/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_Feature_Engineering.ipynb
│   ├── 03_Risk_Scoring.ipynb
│   └── 04_Export_Dashboard_Tables.ipynb
│
├── SQL/
│   ├── create-tables.sql
│   └── validate-data.sql
│
├── Dashboard/
│   └── Supply_Chain_Risk_Analytics.pbix
│
├── Screenshot/
│   ├── Executive Summary.png
│   ├── Risk Overview.png
│   ├── Delivery Performance.png
│   ├── Delay Analysis.png
│   ├── Shipping Mode Analysis.png
│   └── Product Risk.png
│
└── README.md
```

## 👩‍💻 Author

**Bhagyashree Katale**

Aspiring Data Analyst | SQL | Python | Power BI | Excel

- **GitHub:** [Bhagyashreekatale1](https://github.com/Bhagyashreekatale1)
- **LinkedIn:** [Bhagyashree Katale](https://www.linkedin.com/in/bhagyashree-katale-6b6256357/)
- **Portfolio:** [View My Data Analyst Portfolio](https://bhagyashreekatale1.github.io/Data-Analyst/)

