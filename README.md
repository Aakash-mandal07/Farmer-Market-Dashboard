# 🌾 Farmer Market Dashboard | Power BI

## 📌 Project Overview

The Farmer Market Dashboard is a Power BI project created to analyze customer purchases, product performance, vendor activity, and sales trends within a farmer market dataset.

The goal of this project was to practice and strengthen core Power BI concepts including data cleaning, data modeling, relationships, DAX measures, KPI creation, and dashboard design.

---

## 🎯 Objectives

* Analyze sales and quantity metrics
* Understand customer purchasing behavior
* Evaluate vendor performance
* Explore product and category trends
* Create an interactive dashboard using Power BI

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Excel
* Data Modeling

---

## 📂 Dataset Structure

### Customer Table

* customer_id
* customer_first_name
* customer_last_name
* customer_zip

### Customer Purchases Table

* customer_id
* product_id
* vendor_id
* market_date
* quantity
* cost_to_customer_per_qty

### Product Table

* product_id
* product_name
* product_size
* product_qty_type
* product_category_id

### Product Category Table

* product_category_id
* product_category_name

### Vendor Table

* vendor_id
* vendor_name
* vendor_owner_first_name
* vendor_owner_last_name
* vendor_type

---

## 🔗 Data Model

Relationships were created between:

* Customer → Customer Purchases
* Product → Customer Purchases
* Vendor → Customer Purchases
* Product Category → Product

This helped build a structured data model for reporting and analysis.

---

## 📊 Dashboard KPIs

The dashboard includes:

* Total Customers
* Unique Customers
* Total Vendors
* Total Sales
* Total Quantity Sold

---

## 📈 Dashboard Insights

The dashboard allows users to:

* Compare sales across vendors
* Analyze product-wise sales performance
* Track customer purchase activity
* Monitor quantity sold across different dimensions
* Explore product category distribution

---

## 🚀 Key Learnings

Through this project, I learned:

* Data Cleaning using Power Query
* Building Relationships in Power BI
* Creating KPI Cards
* Working with DAX Measures
* Designing Interactive Dashboards
* Understanding Star Schema Concepts

---

## 📸 Dashboard Preview

sales and qunatity waise analysis
https://github.com/Aakash-mandal07/Farmer-Market-Dashboard/blob/main/Sales%20and%20quantity%20waise%20analysis.png
sales waise analysis

qunatity waise analysis

---



## 👨‍💻 Author

Aakash Mandal

This project was created as part of my Power BI learning journey to strengthen my data analytics and business intelligence skills.
