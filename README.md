# 📊 Adventure Works Sales Data Analysis

## 🔍 Overview

This project is an end-to-end data analytics solution built using the Adventure Works dataset. It focuses on analyzing sales performance, customer behavior, and product trends using SQL, Excel, Power BI, and Tableau.

---

## 🎯 Objectives

* Analyze sales trends across time (yearly, quarterly, monthly)
* Identify top-performing and underperforming products
* Understand customer demographics and purchasing behavior
* Evaluate regional and country-level sales performance

---

## 🧱 Data Model

The project follows a hybrid Star Schema and Snowflake Schema approach:

* Central fact table: Sales data
* Dimension tables: Customer, Product, Geography, Time
* Product hierarchy is normalized:
  Product → Subcategory → Category

This structure balances performance with flexibility for hierarchical analysis.

---

## 🛠 Tools & Technologies

* Excel – Data cleaning, preprocessing, analysis and initial dashboard
* SQL – Data extraction and transformation
* Power BI – Interactive dashboards and KPI tracking
* Tableau – Data visualization and storytelling

---

## 📈 Key Insights (Quantified)

* Total sales reached **29.36M** with a profit of **12.08M (~41% margin)**
* United States (~32%) and Australia (~31%) together contributed **~63% of total revenue**
* Sales peaked in **2013 (~16.35M)**, contributing **~55% of total revenue**, with **~131% growth from 2011**
* **Weekday sales accounted for ~72%** of total revenue, indicating strong business-day dependency
* **Road Bikes contributed ~49% of total sales**, making it the top-performing subcategory
* Top 2 product subcategories contributed **~83% of total revenue**
* Customers aged **45–54 contributed ~33% of total sales**, forming the highest-value segment
* **Professionals were the largest customer group (~5.5K customers)**

---

## 📂 Excel Report

Due to file size limitations, the complete Excel analysis file is hosted externally:

👉 [Download Full Excel Report](https://docs.google.com/spreadsheets/d/1i5x6iUCgKf4_ZOVY00v_4jo8I8U_wpfa/edit?usp=sharing&ouid=118049495081469953094&rtpof=true&sd=true)

This file includes:

* Data cleaning and preprocessing
* Pivot tables and intermediate analysis
* Data transformations used for dashboard creation
* Initial dashboard
---

## 📁 Project Structure

Adventure-Works-Data-Analysis/

│
├── sql/
├── excel/
├── powerbi/
├── tableau/
├── final report/
├── images/
└── README.md

---

## 🚀 Outcome

This project demonstrates the complete data analysis lifecycle—from raw data processing to delivering actionable insights through dashboards and visual storytelling.

It highlights skills in:

* Data modeling
* Data analysis
* Data visualization
* Business insight generation

---

## 👩‍💻 Author

Ananya Gopalakrishnan
