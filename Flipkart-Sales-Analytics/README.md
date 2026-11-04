# 📊 Flipkart Sales Performance Analytics Dashboard

An interactive Power BI project designed to analyze sales performance, profitability, product trends, customer segments, regional distribution, and order fulfillment through business intelligence and data visualization.

## 1. 📌 Project Overview

The Flipkart Sales Performance Analytics Dashboard provides a comprehensive view of sales and operational performance using interactive Power BI reports.

The project focuses on transforming raw sales data into meaningful business insights through data analysis, KPI monitoring, and interactive visualizations.

The dashboard consists of three main pages:

- **Sales Overview:** Analyzes overall sales, profit, product categories, and geographical performance.
- **Sales Performance:** Tracks sales trends, customer segments, order distribution, and sales performance over time.
- **Order Fulfillment:** Analyzes order volume, shipping costs, order quantities, shipping modes, and order priorities.

## 2. 🎯 Business Problem

Retail businesses generate large volumes of sales and order data across different products, customer segments, geographical regions, and shipping methods.

Without a centralized reporting solution, management may face challenges in identifying profitable product categories, understanding customer purchasing patterns, monitoring regional sales performance, and evaluating order fulfillment operations.

The business requires an interactive analytics dashboard to consolidate sales and order information, monitor key performance indicators, identify business trends, and support data-driven decision-making.

## 3. 🎯 Project Objectives

- Analyze overall sales, profit, quantity, and order performance.
- Identify high-performing product categories and sub-categories.
- Evaluate sales contributions across customer segments.
- Analyze regional and geographical sales distribution.
- Monitor sales trends across different years and order priorities.
- Compare shipping methods and their contribution to order volume.
- Track shipping costs, order quantities, and order priorities.
- Provide interactive filters for detailed business analysis.
- Identify opportunities to improve profitability and operational efficiency.

## 4. 📂 Dataset Description

The project uses an Excel workbook containing three datasets: Orders, Returns, and People.

| Dataset | Description |
|---|---|
| Orders | Contains sales transactions, customer details, product information, shipping details, and financial metrics. |
| Returns | Contains returned order information and market details. |
| People | Contains regional manager information. |

**Key columns used:**

- Order ID, Order Date, Ship Date
- Ship Mode, Order Priority
- Customer ID, Customer Name, Segment
- City, State, Country, Market, Region
- Category, Sub-Category, Product Name
- Sales, Quantity, Discount, Profit
- Shipping Cost

**Dataset Overview:**

| Metric | Value |
|---|---:|
| Total Records | 51,289 |
| Unique Orders | 25,035 |
| Unique Customers | 1,590 |
| Order Date Range | 2011–2014 |
| Total Sales | 12.64M |
| Total Profit | 1.47M |
| Total Quantity | 178K |


## 5. 🛠️ Tools & Technologies

- **Microsoft Power BI:** Dashboard development and data visualization.
- **Microsoft Excel:** Dataset storage and initial data inspection.
- **Power Query:** Data cleaning and transformation.
- **DAX:** KPI calculations and business metrics.
- **Data Modeling:** Organizing relationships between datasets.

## 6. 📊 Dashboard Pages

### Page 1: Sales Overview

**Purpose:** Provide a consolidated overview of sales, profitability, product categories, and geographical performance.

**Key Visualizations:**

- Average Sales KPI
- Total Quantity KPI
- Total Profit KPI
- Sales by City
- Sales by Shipping Mode
- Sales by Country
- Category and Sub-Category Analysis
- Profit by Market
- Category Slicer

**Business Questions:**

- Which cities and countries generate the highest sales?
- Which shipping mode contributes the most to sales?
- Which product categories and sub-categories perform best?
- How is profit distributed across different markets?

### Page 2: Sales Performance

**Purpose:** Evaluate sales performance over time and understand customer segment contributions and order distribution.

**Key Visualizations:**

- Total Order Count KPI
- Total Sales KPI
- Quantity KPI
- Sales Trends by Year and Order Priority
- Order Distribution by Order ID
- Orders by Priority
- Sales by Customer Segment
- Sales Performance Gauge
- Global Sales Distribution

**Business Questions:**

- How do sales and order trends change over time?
- Which order priorities contribute the most to order volume?
- Which customer segment generates the highest sales?
- How does the business perform against its sales target?
- How are sales distributed across different markets?

### Page 3: Order Fulfillment

**Purpose:** Monitor order distribution, shipping costs, quantities, and priority levels to understand fulfillment performance.

**Key Visualizations:**

- Total Orders KPI
- Total Shipping Cost KPI
- Total Quantity KPI
- Orders by Shipping Mode
- Orders by Order Priority
- Shipping Cost and Order Analysis by Region
- Order Date Range Slicer
- Ship Mode Slicer
- Order Priority Slicer
- Region Slicer

**Business Questions:**

- Which shipping mode handles the highest number of orders?
- How are orders distributed across priority levels?
- How do shipping costs vary across regions?
- Which regions contribute to higher order volumes?
- How do order patterns change over time?

## 📸 Dashboard Preview

### 1. Sales Overview
![Sales Overview](images/Sale%20Overview.png)

### 2. Sales Performance
![Sales Performance](images/Sales%20Performance.png)

### 3. Order Fulfillment
![Order Fulfillment](images/Order%20Fulfilled.png)

## 7. 🔍 Key Insights

Based on the full Orders dataset:

1. **Technology leads in sales:** Technology generates approximately 4.74M in sales, making it the highest-performing product category.
2. **Consumer segment contributes the most:** The Consumer segment generates approximately 6.51M in sales.
3. **Standard Class dominates shipping:** Standard Class accounts for approximately 7.58M in sales and has the highest order volume.
4. **Central region leads regional sales:** The Central region contributes approximately 2.82M in sales.
5. **Phones lead sub-category sales:** Phones generate approximately 1.71M in sales, followed by Copiers at approximately 1.51M.
6. **Tables show negative profitability:** The Tables sub-category records an overall loss of approximately 64K, indicating a need for further profitability analysis.

## 8. 💡 Business Recommendations

- **Focus on profitable categories:** Strengthen sales strategies for high-performing categories such as Technology.
- **Improve low-profit products:** Investigate pricing, discounting, and operational costs associated with loss-making sub-categories such as Tables.
- **Strengthen customer segment strategies:** Develop targeted marketing campaigns to retain and grow the Consumer segment.
- **Optimize regional performance:** Study successful markets and identify opportunities to improve sales in lower-performing regions.
- **Review shipping operations:** Evaluate shipping costs and delivery methods to identify opportunities for operational cost optimization.
- **Monitor order priorities:** Use order priority information to improve fulfillment planning and resource allocation.
- **Use continuous KPI monitoring:** Track sales, profit, and order performance regularly to support informed business decisions.

---

## 👩‍💻 Project Details

**Project Name:** Flipkart Sales Performance Analytics Dashboard

**Domain:** Retail / E-Commerce Analytics

**Tools:** Power BI, Microsoft Excel, Power Query, DAX

**Dashboard Pages:** 3

**Author:** Bhagyashree Katale
