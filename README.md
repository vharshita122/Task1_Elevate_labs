# Task1_Elevate_labs
# 🧹 Customer Personality Analysis - Data Cleaning and Visualization (Excel)

## 📋 Description

This project involves cleaning and analyzing customer personality data provided in JSON format. The data was imported into Excel, cleaned for better structure, and visualized to extract meaningful insights.

---

## ✅ Tasks Completed

### 1. Data Cleaning (Excel)
- Imported JSON file using `Data → Get Data → From JSON`.
- Identified and handled missing values using filters and formulas.
- Removed duplicate rows using `Data → Remove Duplicates`.
- Standardized text fields (like Education and Marital Status) using formulas (`LOWER`, `TRIM`, `PROPER`).
- Converted `Dt_Customer` into `dd-mm-yyyy` format using `Format Cells`.
- Renamed column headers for consistency (lowercase, underscores).
- Fixed data types: made sure numeric fields were recognized correctly and dates formatted properly.

---

### 2. Creative Enhancements
- Added a new column to calculate customer **age** from `Year_Birth`.
- Calculated **customer tenure** from `Dt_Customer` to today.
- Categorized customers into **spender types** based on their total spending.
- Built a summary sheet with key KPIs:
  - Total number of customers
  - Average income
  - Most common education level
  - Number of customers who responded to campaigns

---

### 3. Visualization
- Created PivotTables to summarize data.
- Plotted bar and pie charts for:
  - Education distribution
  

---

## 📁 Files Included
- `cleaned_data.xlsx` – The cleaned and formatted Excel file with summary and charts
- `README.md` – This file explaining what was done

---

## 📌 Tools Used
- Microsoft Excel (Power Query, PivotTables, Charts)
