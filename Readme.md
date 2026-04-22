# 📊 Supply Chain Analytics Dashboard (Power BI)

## 🚀 Project Overview

This project presents an end-to-end **Supply Chain Analytics Dashboard** built using **Power BI Desktop**, covering key aspects of:

* 📦 Sales & Revenue Analysis
* 🏭 Inventory Management
* 🚚 Logistics & Transportation
* ⚙️ Manufacturing Insights
* ❌ Quality & Defect Analysis

The dashboard provides **actionable insights** to optimize operations, reduce costs, and improve decision-making across the supply chain.

---

## 🎯 Business Objectives

* Identify top-performing products and revenue drivers
* Analyze stock levels and detect potential stock-outs
* Evaluate transportation cost efficiency
* Monitor delivery performance and delays
* Assess supplier quality using defect rates and inspection results

---

## 🧱 Data Description

The dataset contains supply chain data including:

* Product details (SKU, Product Type, Price)
* Sales metrics (Units Sold, Revenue)
* Inventory (Stock Levels, Availability)
* Logistics (Shipping Time, Carrier, Transport Mode, Route, Cost)
* Manufacturing (Production Volume, Lead Time, Cost)
* Quality (Inspection Results, Defect Rates)

---

## 🛠️ Tech Stack

* **Power BI Desktop** → Data visualization & dashboarding
* **Power Query** → Data cleaning & transformation
* **DAX (Data Analysis Expressions)** → KPI calculations

---

## 🔄 Data Processing Steps

### 1. Data Cleaning (Power Query)

* Renamed columns to standardized format
* Fixed data types (numeric, text, decimal)
* Removed duplicate columns
* Handled inconsistent values (e.g., "Unknown" → "Other")

### 2. Feature Engineering

Created new business columns:

* Profit
* Stock Status (Low / Sufficient)
* Delivery Status (On-Time / Delayed)
* Defect Category (High / Low)

### 3. Data Modeling

* Converted flat dataset into **Star Schema**
* Created dimension tables:

  * Dim_Product
  * Dim_Customer
  * Dim_Supplier
  * Dim_Logistics
* Established relationships with fact table

---

## 📐 Key Metrics (DAX)

* Total Revenue
* Total Profit
* Profit Margin %
* Total Cost
* Avg Shipping Time
* Avg Lead Time
* Stock to Sales Ratio
* Pass Rate %
* Delayed Deliveries

---

## 📊 Dashboard Structure

### 📄 Page 1: Sales & Inventory Overview

* KPI summary (Revenue, Profit, Units Sold, etc.)
* Revenue by Product Type
* Top Selling SKUs
* Stock vs Sales comparison
* Customer segmentation
* Inventory health (Low Stock analysis)

---

### 📄 Page 2: Operations & Logistics Insights

* Transport cost analysis by mode and route
* Shipping time by carrier
* Delivery performance (On-Time vs Delayed)
* Supplier defect analysis
* Inspection results distribution
* Production vs demand comparison

---

## 🎛️ Interactive Features

* Dynamic slicers:

  * Product Type
  * Customer Type
  * Supplier
  * Transport Mode

* Cross-filtering across all visuals

* Drill-down insights

---

## 📸 Dashboard Preview


* Page 1: Sales Overview
* Page 2: Logistics & Operations

---

## 💡 Key Insights

* Certain transport modes significantly increase cost
* Some SKUs show high demand but low stock levels
* Specific suppliers have higher defect rates
* Delivery delays are linked to higher shipping times

---

## 📌 Learnings

* Implemented **end-to-end BI workflow**
* Applied **data modeling (star schema)**
* Built **business KPIs using DAX**
* Designed **user-friendly dashboards**

---

## 🔮 Future Improvements

* Add time-based analysis (monthly trends)
* Integrate real-time data sources
* Apply predictive analytics (demand forecasting)

---

## 👨‍💻 Author

**Shauly Chakraborty**
📧 [shauly.mlg2002@gmail.com](mailto:shauly.mlg2002@gmail.com)
🎓 B.Tech ECSE (KIIT Bhubaneswar)

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to connect!