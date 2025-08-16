# -Population-Analysis-PowerBI-1980-2040
Power BI project analyzing population data (1980–2040). The project demonstrates end-to-end BI workflow including data modeling, DAX measures, Power Query transformations, interactive dashboarding, and performance optimization. Key insights include population growth trends, regional variations, gender distribution, and category contributions.
# 📊 Population Data Analysis (1980–2040) using Power BI  

---

## 📌 Project Overview  
This repository contains my Power BI project analyzing **population data from 1980 to 2040**.  

The project had two main objectives:  
1. To uncover long-term demographic trends across regions, categories, and gender.  
2. To demonstrate a complete **Power BI workflow** — from raw data preparation to optimized dashboards.  

---

## ⚙️ Methodology & Implementation  

### 🔹 Data Modeling  
- Built relationships across tables.  
- Designed a **Star Schema** for better structure and performance.  

### 🔹 DAX (Data Analysis Expressions)  
Custom measures created included:  
- `SUMX` → row-by-row aggregations  
- `CALCULATE` → context-based filtering  
- `FILTER` → subset refinements  
- Concatenated measures → enhanced labels  

### 🔹 Power Query (Data Transformation)  
- Cleaned data (removed duplicates, handled missing values).  
- Standardized columns for consistency.  
- Applied **M language** for:  
  - **Merging** queries  
  - **Pivoting/Unpivoting** data  
  - Creating **custom columns**  

### 🔹 Visualization & Dashboarding  
Built a **4-page interactive dashboard** using:  
- **Column & Line Charts** → Population growth trends  
- **TreeMap** → Category-wise distribution  
- **Slicers** → Year, region, and category filters  
- **Cards (KPIs)** → Population totals, gender ratios  

### 🔹 Performance Optimization  
- Removed unused columns/tables to minimize file size.  
- Optimized **DAX measures** for efficiency.  

---

## 📊 Key Findings  

✅ **Population Growth Trend (1980–2040):**  
- Strong upward trend across most regions.  

✅ **Regional Variations:**  
- Some regions grew faster, suggesting migration and urbanization.  

✅ **Gender Distribution:**  
- Male-to-female ratios fluctuated by category and year.  

✅ **Category Contributions:**  
- Clear shifts in population distribution across different demographic categories.  

## 🚀 Conclusion  
This project highlights the **full Power BI pipeline** — from raw data cleaning, modeling, and transformation to optimized visualization.  

The analysis provides valuable insights into population dynamics over six decades (1980–2040), useful for **researchers, policymakers, and decision-makers**.  

##Report View
https://github.com/Anik575/-Population-Analysis-PowerBI-1980-2040/blob/main/population_dashboard.JPG
