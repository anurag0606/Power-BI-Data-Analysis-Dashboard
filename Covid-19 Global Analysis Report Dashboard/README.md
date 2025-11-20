# 🌍 COVID-19 Global Analysis Report Dashboard

_An interactive Power BI dashboard providing a comprehensive global overview of COVID-19 confirmed cases, deaths, recoveries, and regional trends._

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

This project visualizes the worldwide spread and impact of **COVID-19** through an interactive **Power BI dashboard**.  
It provides a detailed analysis of confirmed cases, deaths, recoveries, and fatality rates across different countries and time periods.  

The dashboard supports global policymakers and analysts in understanding how the pandemic evolved and which regions were most affected.  

---

## 🎯 Business Problem

During the pandemic, tracking the real-time spread of COVID-19 and analyzing its impact was crucial.  
This dashboard helps address key questions such as:  
- Which countries have the highest confirmed and death counts?  
- What are the global recovery and fatality rates?  
- How do trends in confirmed, recovered, and death cases compare over time?  
- Which countries achieved the highest recovery rates and lowest fatality rates?  

---

## 📁 Dataset

**Source:** Public COVID-19 data from WHO / Johns Hopkins University (2020–2023)  

**Key Columns Used:**  
- `Country/Region`  
- `Date` (Year, Month, Day)  
- `Confirmed Cases`  
- `Deaths`  
- `Recovered Cases`  
- `Active Cases`  

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard design and interactivity  
- **Excel / CSV Dataset** – Source data  
- **Power Query** – Data transformation and cleaning  
- **DAX (Data Analysis Expressions)** – Calculations for KPIs  
- **Map Visuals & Line Charts** – For regional and time-series analysis  

---

## 🧹 Data Preparation

- Removed duplicate and null entries  
- Converted date formats for time-based filtering  
- Calculated new metrics:  
  - **Case Fatality Rate (CFR%)** = (Deaths / Confirmed) × 100  
  - **Recovery Rate (%)** = (Recovered / Confirmed) × 100  
  - **Active Cases** = Confirmed − (Recovered + Deaths)  
- Merged country-level summaries for mapping visuals  

---

## 📊 Dashboard Insights

### 🔹 KPI Overview
- **Total Confirmed Cases:** 829M  
- **Total Deaths:** 43M  
- **Total Recovered Cases:** 388M  
- **Total Active Cases:** 397M  
- **Case Fatality Rate (CFR):** 5.24%  
- **Recovery Rate:** 47%  

### 🔹 Global Trends
The **COVID-19 Trends Chart** shows rapid growth in confirmed cases and recoveries between January and July, with deaths growing at a slower pace.  

### 🔹 Country-Level Insights
- **Top 5 Countries by High CFR%:** Yemen, Belgium, Italy, United Kingdom, United States  
- **Top 5 Countries by High Recovery Rate%:** New Zealand, Greece, Iceland, Liechtenstein, Thailand  

### 🔹 Regional Comparisons
- Highest confirmed and death counts observed in **Spain**, **United Kingdom**, and **Italy**.  
- Global map visualization shows concentration in **North America**, **Europe**, and **Asia**.  

---

## 📈 Key Findings

1. **Global confirmed cases** reached nearly 829 million, with over 43 million deaths.  
2. **Average fatality rate** globally stands around **5.24%**.  
3. **Recovery rate** improved steadily to **47%** by mid-year.  
4. **European nations** like Italy and Spain had some of the highest confirmed and death rates.  
5. **Asian and Oceanic countries** demonstrated better recovery performance.  

---

## 🚀 How to Run This Project

1. Open **Power BI Desktop**.  
2. Import the dataset (`covid_19_global_data.csv`).  
3. Open the Power BI file:  
   ```bash
   dashboard/covid_19_global_analysis.pbix
   ```  
4. Refresh data connections.  
5. Interact with filters for country/region and date to analyze specific trends.  

---

## 🧭 Conclusion

This **COVID-19 Global Dashboard** provides a powerful visual summary of the pandemic’s global impact.  
It helps researchers, analysts, and policymakers identify affected regions, analyze recovery trends, and plan preventive strategies.  

---

## 👤 Author & Contact

**Anurag Digrase**  
📧 Email: [anuragdigrase2003@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/anurag-digrase-799348243/)  
💼 Data Analyst | Power BI | SQL | Excel | Python  

---

## 🖼️ Dashboard Preview

![COVID-19 Global Analysis Report Dashboard](Covid-19%20Global%20Analysis%20Report%20Dashboard%20.png)
