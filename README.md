# 💼 Jobs in Data – Salary Analysis Dashboard

**📊 Final Project - Excel & Tableau**  
**🗂️ Dataset source:** [Jobs and Salaries in Data Science (Kaggle)](https://public.tableau.com/app/profile/ileana.gisele.velazquez/viz/Jobs-in-data/Dashboard1 "Link to dataset")

---

## 👩‍💻 Overview

This dashboard analyzes job and salary data for Data-related positions from 2021 to 2023. The project is built for users exploring the data job market landscape, especially students or entry-level professionals in Data Analytics.

---

## 🔍 Dataset Details

**Main Fields Included:**
- **Row ID:** Unique identifier for each entry
- **Work Year:** Year of the salary record
- **Job Title:** Specific job role title
- **Job Category:** Classification by data specialization
- **Salary Currency / Salary USD:** Annual gross salary (local + converted to USD)
- **Residence:** Country of employee residence
- **Experience Level:** Seniority level of the role
- **Employment Type:** Type of employment contract
- **Work Setting:** Work model (remote, hybrid, in-person)
- **Company Location:** Location of the company
- **Company Size:** Size of the employer (S/M/L)

---

## 🎯 Objectives

This dashboard aims to explore:
- Year-over-year salary evolution
- Salary distribution across job titles and locations
- Influence of contract type, experience level, company size, and work setting
- Where high-paying jobs are concentrated

---

## ⚙️ Data Cleaning & Setup

- Removed duplicates and special characters
- Applied data validation
- Added a Row ID column for clarity
- Converted the Excel table to a structured format
- Connected the data to Tableau

---

## 📊 Visualizations & Interactivity

### KPIs
- **Max Salary:** `MAX([Salary USD])`
- **Min Salary:** `MIN([Salary USD])`
- **Total Job Records:** Count using Jobs in Data

### Salary Trends Over Time
- Used `AVG([Salary USD])` by Work Year to create a line chart
- Compared average salaries across years, filtered by user-selected category

### Interactive Filters
- Created a parameter (`P-Categoría`) and calculated field (`Categoría`) to dynamically filter results based on company location, company size, residence, employment type, experience level, work setting, job category, and job title.

### Map & Heatmap
- Displayed number of job records by country (bubble size)
- Used color gradient to show average salary (heatmap)

### Donut Charts
- Represented job distributions by category
- Used Exclude logic for accurate percentage calculations

### Dual-Axis Bar Chart
- Compared salary distribution across contract types

---

## 📌 Key Findings

### Salary Trends
- General upward salary trend over the years
- Slight declines observed in Data Management/Strategy and Cloud-related roles in 2022–2023

### Contract Type & Salary
- Full-time and Contract roles offer the highest averages
- Freelance and Part-time tend to offer the lowest

### Experience Level
- Executive roles have the highest salaries, followed by Senior, Mid-level, and Entry-level
- Entry-level roles typically earn less than half the global average

### Company Size & Work Setting
- Medium-sized companies offer the highest average salaries
- In-person jobs pay more than remote and hybrid

### Geography
- While the U.S. has the most job records, the highest salary averages are found in Qatar, Puerto Rico, and Japan, although based on smaller sample sizes

---

## 🧠 Conclusion

To aim for above-average salaries in Data:
- ✅ Seek Full-time or Contract roles
- ✅ Prioritize in-person or remote work settings (over hybrid)
- ✅ Focus on high-paying domains like Machine Learning, Data Science, and Data Engineering
- ✅ Target companies based in U.S., Canada, Qatar, or Puerto Rico
- ✅ Build experience — seniority has the biggest impact on