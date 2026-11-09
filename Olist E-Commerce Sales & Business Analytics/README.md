Olist # E-Commerce Sales & Business Analytics

An end-to-end data analytics project using the **Olist Brazilian E-Commerce Dataset** to analyze sales performance, customer behavior, order trends, seller performance, and product categories.

This project demonstrates a complete analytics workflow using **PostgreSQL, SQL, Power BI, and DAX**, transforming raw e-commerce data into meaningful business insights through data validation, exploratory analysis, and interactive dashboards.

---

## Project Overview

The objective of this project is to analyze Olist's e-commerce operations and understand key business performance indicators across customers, orders, sellers, and product categories.

The analysis focuses on identifying sales trends, evaluating order and delivery performance, understanding customer purchasing patterns, and providing insights that support business decision-making.

## Business Context & Objectives

The project addresses important e-commerce business questions:

- How is overall sales and order performance?
- Which customer locations contribute to the business?
- What are the trends in order volume and delivery performance?
- How do sellers perform across different regions?
- Which product categories generate the highest sales?
- What patterns can be identified in customer reviews and payment methods?

## Data Sources

This project uses the publicly available **Olist Brazilian E-Commerce Dataset** from Kaggle.

- **Dataset:** [Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Source:** Kaggle

The dataset contains information about orders, customers, sellers, products, payments, reviews, geolocation, and product category translations.

**Note:** The original dataset files are not included in this repository due to their large file size. Download the dataset directly from Kaggle using the link above to reproduce the analysis.

## Project Workflow

1. **Data Collection** – Obtained the Olist e-commerce dataset from Kaggle.
2. **Database Creation** – Created a PostgreSQL database and structured tables for the dataset.
3. **Data Loading** – Imported the CSV files into PostgreSQL.
4. **Data Validation** – Checked missing values, duplicate records, data consistency, and invalid values.
5. **SQL Analysis** – Performed exploratory data analysis using joins, aggregations, subqueries, and window functions.
6. **Power BI Development** – Connected the analytical data to Power BI and developed interactive dashboards.
7. **DAX Measures** – Created measures for business KPIs and performance analysis.

## Project Structure

```text
Ecommerce-Sales-Business-Analytics/
│
├── Dataset/
│   └── README.md
│
├── SQL/
│   ├── 01_Create_Tables.sql
│   ├── 02_Load_Dataset.sql
│   ├── 03_Data_Validation.sql
│   └── 04_Exploratory_Data_Analysis.sql
│
├── DAX_Measures/
│   └── DAX_Measures.dax
│
├── Dashboard/
│   └── Screenshots/
│       ├── Summary.png
│       ├── Customers.png
│       ├── Orders.png
│       ├── Sellers.png
│       └── Categories.png
│
└── README.md
```

## SQL Analysis

PostgreSQL was used to create the database, load the dataset, validate records, and perform business-focused analysis.

Key analysis areas include:

- **Customer Analysis:** Customer distribution, location-based analysis, and purchasing behavior.
- **Order Analysis:** Order trends, order status, and delivery performance.
- **Seller Analysis:** Seller distribution and seller-level performance.
- **Product & Category Analysis:** Product distribution, category-level sales, and product performance.
- **Payment Analysis:** Payment types, payment values, and installment patterns.
- **Review Analysis:** Customer ratings and review trends.

## Power BI Dashboard

An interactive Power BI dashboard was developed to present business performance across five analytical pages.

### Dashboard Pages

1. **Summary** – Overall business performance and key performance indicators.
2. **Customers** – Customer distribution and geographic analysis.
3. **Orders** – Order trends, order status, and delivery performance.
4. **Sellers** – Seller distribution and performance analysis.
5. **Categories** – Product category analysis and sales performance.

### Dashboard Screenshots

#### 1. Summary
![Summary Dashboard](Dashboard/Screenshots/Summary.png)

#### 2. Customers
![Customers Dashboard](Dashboard/Screenshots/Customers.png)

#### 3. Orders
![Orders Dashboard](Dashboard/Screenshots/Orders.png)

#### 4. Sellers
![Sellers Dashboard](Dashboard/Screenshots/Sellers.png)

#### 5. Categories
![Categories Dashboard](Dashboard/Screenshots/Categories.png)

## Power BI Dashboard File

The Power BI dashboard file (`.pbix`) is hosted externally due to GitHub file size considerations.

**Download:** [Olist E-Commerce Power BI Dashboard](PASTE_YOUR_GOOGLE_DRIVE_LINK_HERE)

Download the file and open it using Power BI Desktop to explore the interactive dashboard.

## DAX Measures

DAX measures are used to calculate business KPIs and support interactive dashboard analysis.

The DAX measures file is available in the `DAX_Measures` folder.

## Tools & Technologies

| Category | Tools |
|---|---|
| Database | PostgreSQL |
| Query Language | SQL |
| Data Visualization | Microsoft Power BI |
| Calculations | DAX |
| Data Transformation | Power Query |
| Data Source | Olist Brazilian E-Commerce Dataset |
| Version Control | Git & GitHub |

## Key Takeaways

This project demonstrates practical data analytics skills through:

- Structuring and managing relational databases.
- Performing data cleaning and validation using SQL.
- Writing analytical SQL queries to answer business questions.
- Analyzing customer, order, seller, and product category performance.
- Developing interactive Power BI dashboards.
- Using DAX to calculate business KPIs.
- Communicating data-driven insights through visualizations.

## Project Outcome

Developed an end-to-end e-commerce analytics solution that transforms raw transactional data into structured business insights using **PostgreSQL, SQL, Power BI, and DAX**.
