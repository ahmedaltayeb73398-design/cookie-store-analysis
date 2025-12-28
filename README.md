# 🍪 Cookie Store Product Performance Analysis

## 📌 Project Overview

This Power BI project analyzes product performance for a cookie store to identify **top-selling items**, **most profitable products**, and **underperforming categories and flavors**. The goal is to support data-driven decisions related to product strategy, pricing, and inventory optimization.


## ❓ Business Problem

The cookie store needs clear insights into:

* Which products drive the highest sales volume
* Which products contribute the most profit
* Which flavors and categories are underperforming

Understanding these patterns helps improve product focus, marketing efforts, and overall profitability.


## 🎯 Key Business Questions

* What are the **top-selling products** by quantity?
* Which products generate the **highest profit**?
* Which **flavors** are underperforming?
* Which **product categories** generate the highest and lowest revenue?

---

## 🗂️ Data Model

The analysis is built using a star schema consisting of:

* **Fact_Sales** – Sales transactions (quantity, revenue, profit)
* **Dim_Product** – Product details (name, category, flavor)
* **Dim_Customer** – Customer information
* **Dim_Store** – Store locations
* **Dim_Date** – Date dimension for time analysis


## 🛠️ Tools Used

* **Power BI Desktop**
* DAX Measures
* Data Modeling & Relationships


## 📊 Key Insights

* **Hazelnut-filled Cookie**, **Kid's Chocolate Cookie**, and **Milk Chocolate Cookie** achieved the **highest sales volume**, although they were **not the most profitable** products.
* **Triple Chocolate Cookie** was the **most profitable product** overall.
* **Oat** and **Vegan** flavors recorded the **lowest quantities sold**, indicating underperformance.
* The **Premium category** generated the **highest revenue**, while the **Classic category** produced the **lowest revenue**.


## 📈 Dashboard Overview

The Power BI dashboard includes:

* **Bar Charts** for top-selling and most profitable products
* **Column Charts** for category and flavor performance
* **Interactive slicers** for:

  * Store
  * Date

These visuals allow users to explore performance trends dynamically across different dimensions.

---

## 🚀 Outcome

This project demonstrates how Power BI can be used to:

* Identify strong and weak products
* Support strategic product and category decisions
* Deliver clear, interactive insights through effective data visualization

---

## 📎 Files

* `.pbix` – Power BI report file
* `README.md` – Project documentation

