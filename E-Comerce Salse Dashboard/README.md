# 🛒 E-Commerce Sales Dashboard

_An interactive Power BI dashboard visualizing sales performance, customer insights, and profitability trends for an e-commerce business._

---

## 📌 Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Data Preparation](#data-preparation)
- [Dashboard Insights](#dashboard-insights)
- [Key Findings](#key-findings)
- [How to Run This Project](#how-to-run-this-project)
- [Conclusion](#conclusion)
- [Author & Contact](#author--contact)

---

## 🧩 Overview

This project presents a comprehensive **E-Commerce Sales Analysis Dashboard** created using **Power BI**.  
It enables users to monitor total sales, profits, and customer performance while analyzing patterns by **state, category, payment mode, and month**.  

The dashboard helps business stakeholders track growth and identify profitable segments effectively.

---

## 🎯 Business Problem

E-commerce companies often struggle to track performance across multiple dimensions such as customer behavior, product category, and payment modes.  
This analysis answers key questions like:  
- Which states contribute the most to sales?  
- Which payment methods are most popular?  
- Which sub-categories generate the highest profit?  
- How does profit vary month by month?  

---

## 📁 Dataset

**Source:** Simulated retail sales dataset (Excel/CSV)  

**Key Columns Used:**  
- `State`  
- `Customer Name`  
- `Category` and `Sub-Category`  
- `Quantity`  
- `Profit`  
- `Amount`  
- `Payment Mode`  
- `Month`  

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – for data visualization  
- **Excel / CSV Data** – as data source  
- **Power Query** – for cleaning and transformation  
- **DAX (Data Analysis Expressions)** – for calculated measures  
- **Microsoft Excel** – for initial dataset formatting  

---

## 🧹 Data Preparation

- Cleaned and removed null values  
- Ensured consistency in categorical values (e.g., payment modes, states)  
- Created calculated columns:  
  - Average Order Value (AOV)  
  - Total Amount, Profit, and Quantity  
- Built relationships between tables (if any)  

---

## 📊 Dashboard Insights

### 🔹 KPIs Overview
- **Total Sales Amount:** 438K  
- **Total Profit:** 37K  
- **Total Quantity Sold:** 5615  
- **Average Order Value (AOV):** 121K  

### 🔹 Sales by State
Top-performing states include **Maharashtra**, **Madhya Pradesh**, and **Uttar Pradesh**.  

### 🔹 Quantity by Payment Mode
- **Cash on Delivery (COD)** leads with **43.74%**, followed by **UPI (20.61%)**.  

### 🔹 Profit by Month
Profit peaks in **March, October, and November**, while **July and December** record lower profits.  

### 🔹 Quantity by Category
- **Clothing (62.62%)** dominates overall sales volume, followed by **Electronics (20.55%)** and **Furniture (16.83%)**.  

### 🔹 Profit by Sub-Category
Top sub-categories by profit include **Printers**, **Bookcases**, and **Sarees**.  

---

## 📈 Key Findings

1. **Maharashtra** generates the highest sales volume among all states.  
2. **COD** is the most used payment method, highlighting customer trust in post-delivery payment.  
3. **Printers and Bookcases** deliver the most profit, while **Tables** and **Accessories** have lower margins.  
4. **Clothing** leads in total quantity sold, showing strong product demand.  
5. **Sales dip** during mid-year months (June–July) but recover strongly in festive periods (October–November).  

---

## 🚀 How to Run This Project

1. Open Power BI Desktop.  
2. Import the dataset (`ecommerce_sales_data.csv`).  
3. Open the Power BI file:
   ```bash
   dashboard/ecommerce_sales_dashboard.pbix
   ```
4. Refresh data connections if needed.  
5. Interact with slicers (Quarter, Payment Mode, etc.) to explore insights.  

---

## 🧭 Conclusion

The E-Commerce Sales Dashboard delivers an in-depth analysis of business performance across customers, regions, and product categories.  
It helps decision-makers optimize marketing strategies, identify top-performing regions, and plan inventory effectively.  

---

## 👤 Author & Contact

**Anurag Digrase**  
📧 Email: [anuragdigrase2003@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/anurag-digrase-799348243/)  
💼 Data Analyst | Power BI | SQL | Excel | Python  

---

## 🖼️ Dashboard Preview

![E-Commerce Sales Dashboard](E-Comerce%20Salse%20Dashboard.png)
