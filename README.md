# 📊 Customer Retention & Business Performance Analytics Platform

## 📌 Project Overview

This project focuses on analyzing retail sales data of technology products using **Power BI**. The goal is to transform raw transactional data into meaningful business insights through interactive dashboards. The analysis highlights **sales performance, customer behavior, product contribution, and regional trends** to support data-driven decision making.

The final solution is an **interactive Power BI dashboard with three analytical pages** designed to help stakeholders monitor business performance and identify growth opportunities.

---

# 🎯 Business Problem

Retail organizations generate large volumes of sales data from multiple products, customers, and regions. However, without proper analysis it becomes difficult to identify:

* Which products drive the most revenue
* Which regions generate the highest sales
* Customer purchasing behavior patterns
* Performance differences between sales channels

This project addresses these challenges by building a **Power BI dashboard that converts raw sales data into actionable business insights**.

---

# 🎯 Project Objectives

The key objectives of this project are:

* Analyze overall business performance and revenue distribution
* Identify high-performing products and their contribution to total sales
* Understand customer purchasing patterns
* Analyze regional sales performance across states
* Compare online vs offline sales channels
* Provide insights that help businesses improve decision making

---

# 📂 Dataset Information

The dataset contains transactional sales records for technology products sold across different regions.

### Key Fields in the Dataset

| Column         | Description                              |
| -------------- | ---------------------------------------- |
| Transaction ID | Unique identifier for each transaction   |
| Product        | Product name                             |
| Quantity       | Number of units sold                     |
| Unit Price     | Price per unit                           |
| Date           | Transaction date                         |
| Customer Name  | Customer who purchased the product       |
| State          | Customer location                        |
| Country        | Country of transaction                   |
| Sales Channel  | Online / Offline                         |
| Payment Type   | Payment method used                      |
| Sales          | Total revenue generated from transaction |

---

# 🛠 Tools & Technologies Used

| Technology          | Purpose                                           |
| ------------------- | ------------------------------------------------- |
| **Power BI**        | Data visualization & dashboard development        |
| **DAX**             | Creating calculated measures and business metrics |
| **Power Query**     | Data cleaning and transformation                  |
| **Microsoft Excel** | Initial dataset exploration                       |
| **GitHub**          | Project documentation and portfolio showcase      |

---

# 📊 Dashboard Structure

The Power BI dashboard contains **three analytical pages**, each focusing on a specific aspect of business performance.

---

## 📍 Page 1 — Overview

This page provides a **high-level summary of overall business performance**.

### Visualizations Included

* KPI Cards (Total Revenue, Total Orders, Average Order Value)
* Revenue by State
* Top Customers by Revenue
* Sales Revenue by Channel
* Top Products by Revenue
* Payment Distribution

📷 **Dashboard Preview**

```
https://github.com/yogeshkale09/Customer-Retention-Business-Performance-Analytics-Platform/blob/fd5d47ad0740a572d3a377c36178086f03c4ddfe/Dashboard%20Preview.png
```

---

## 📍 Page 2 — Customer & Regional Analysis

This page focuses on **customer purchasing behavior and regional sales performance**.

### Visualizations Included

* Customer KPI Metrics
* Revenue Trend Over Time
* Channel Performance by State

📷 **Dashboard Preview**

```
[(Add screenshot of Customer & Regional Dashboard here)](https://github.com/yogeshkale09/Customer-Retention-Business-Performance-Analytics-Platform/blob/fd5d47ad0740a572d3a377c36178086f03c4ddfe/Customer%20%26%20Regional%20Analysis.png)
```

---

## 📍 Page 3 — Product Performance Analysis

This page analyzes **product-level sales performance**.

### Visualizations Included

* Revenue by Product
* Quantity Sold by Product
* Average Product Price
* Revenue Share by Product

📷 **Dashboard Preview**

```
[(Add screenshot of Product Performance Dashboard here)](https://github.com/yogeshkale09/Customer-Retention-Business-Performance-Analytics-Platform/blob/fd5d47ad0740a572d3a377c36178086f03c4ddfe/Product%20Performance%20Analysis.png)
```

---

# 📈 Key Insights

* A small number of products contribute significantly to overall revenue, indicating strong demand for specific product categories.
* Sales performance varies across different states, highlighting regional differences in market demand.
* A limited number of customers generate a large share of total revenue.
* Online and offline sales channels show different performance trends.
* Revenue fluctuates over time, suggesting possible seasonal demand patterns.

---

# 💡 Business Recommendations

* Increase marketing and inventory focus on high-performing products.
* Expand promotional campaigns in top-performing states.
* Strengthen the most effective sales channel to increase overall revenue.
* Develop loyalty programs for high-value customers.
* Use revenue trends to plan seasonal promotions and inventory management.

---

# 📊 Example DAX Measures Used

Below are some important DAX calculations used in the dashboard.

### Total Revenue

```DAX
Total Revenue =
SUM(Sales[Sales])
```

### Total Orders

```DAX
Total Orders =
COUNTROWS(Sales)
```

### Average Order Value

```DAX
Average Order Value =
DIVIDE([Total Revenue], [Total Orders])
```

### Unique Customers

```DAX
Unique Customers =
DISTINCTCOUNT(Sales[Customer Name])
```

---

# 📌 Project Outcome

The Power BI dashboard enables stakeholders to:

* Monitor overall business performance
* Identify high-performing products
* Understand customer purchasing behavior
* Analyze regional sales trends
* Make informed data-driven business decisions

---

# 🚀 Future Improvements

Potential improvements for this project include:

* Implement **time intelligence analysis (YoY / MoM growth)**
* Perform **customer segmentation analysis**
* Add **profitability analysis dashboards**
* Integrate **real-time data sources**

---


