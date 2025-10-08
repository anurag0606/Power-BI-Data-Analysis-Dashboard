# 📊 Data Professional Survey Breakdown

_An interactive Power BI dashboard analyzing global data professionals’ demographics, salaries, and work satisfaction insights._

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

This project explores trends in the data industry by visualizing results from a **Data Professionals Survey**.  
The Power BI dashboard reveals insights into:
- Average salaries by job title  
- Work–life balance satisfaction  
- Popular programming languages  
- Industry distribution  
- Gender demographics  
- Global participation  

---

## 🎯 Business Problem

The data industry is expanding rapidly, yet pay scales, satisfaction, and career growth vary widely.  
This analysis helps answer key questions like:
- Which data roles earn the highest salaries?  
- How happy are professionals with their pay and work–life balance?  
- Which programming languages dominate the field?  
- How difficult is it to break into data-related careers?  

---

## 📁 Dataset

**Source:** Kaggle – *Data Professional Survey (2023)*  

**Key Columns Used:**
- `Job Title`
- `Average Salary`
- `Programming Language`
- `Difficulty to Break into Data`
- `Happiness with Salary`
- `Happiness with Work/Life Balance`
- `Country`, `Gender`, `Industry`

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – for dashboard creation  
- **Excel / CSV Data** – for raw data storage  
- **Power Query** – for cleaning and transformation  
- **DAX (Data Analysis Expressions)** – for calculated fields  
- **Python / Pandas (optional)** – for preprocessing large datasets  

---

## 🧹 Data Preparation

- Removed missing or duplicate responses  
- Standardized job titles and industries  
- Converted salary values to consistent scale  
- Created calculated columns for:
  - Average salary per role  
  - Happiness index  
  - Percentage distribution by gender and country  

---

## 📊 Dashboard Insights

### 🔹 Average Salary by Job Title
Data Scientists and Engineers lead salary charts, while entry-level roles earn comparatively less.

### 🔹 Happiness with Salary & Work–Life Balance
- Average salary satisfaction: **4.27 / 10**  
- Work–life balance satisfaction: **5.74 / 10**  

### 🔹 Difficulty to Break into Data
Most respondents rated it as *“Easy”* or *“Neither Easy nor Difficult”*, showing better accessibility into data careers.

### 🔹 Favorite Programming Languages
**Python** dominates, followed by **R** and **SQL**, reaffirming Python’s leadership in the data field.

### 🔹 Industry & Country Overview
- Top industries: *Tech, Finance, and Healthcare*  
- Top countries: *United States and India*  

### 🔹 Demographics
- Average respondent age: **29.87 years**  
- Gender split visualized via interactive filters  

---

## 📈 Key Findings

1. **Data Scientists** earn the highest average salaries among all roles.  
2. **Python** remains the preferred language for most professionals.  
3. **Work–life balance** satisfaction is higher than salary satisfaction.  
4. **Majority of respondents** find it moderately easy to enter the data field.  
5. **Tech industry** employs the largest number of data professionals.  

---

## 🚀 How to Run This Project

1. Open Power BI Desktop.  
2. Load the dataset (`data_professional_survey.csv`).  
3. Open the `.pbix` file:
   ```bash
   dashboard/data_professional_survey_breakdown.pbix
   ```
4. Refresh data connections if needed.  
5. Interact with slicers and filters to explore specific insights.  

---

## 🧭 Conclusion

The dashboard highlights how experience, role, and skills shape salaries and satisfaction in the data industry.  
It serves as a benchmark for aspiring data professionals and organizations planning workforce development.  

---

## 👤 Author & Contact

**Anurag Digrase**  
📧 Email: [anuragdigrase2003@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/anurag-digrase-799348243/)  
💼 Data Analyst | Power BI | SQL | Python

---

## 🖼️ Dashboard Preview

![Data Professional Survey Breakdown Dashboard](Data%20Professional%20Survey%20Breakdown.png)
