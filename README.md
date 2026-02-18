# data_analyst_intern_assignment
Excel-based data analysis assignment (cleaning, funnel analysis, insights)

# 📊 Data Analyst Intern Assignment (Excel)

This repository contains my submission for a Data Analyst Intern assignment.  
The goal of this project is to clean raw data, analyze user engagement and purchases, and extract a meaningful business insight using **Microsoft Excel**.

The work focuses on:
- Data cleaning and preparation
- Funnel analysis (engagement → purchase)
- Time-series and bar chart visualizations
- Clear, concise business interpretations

---

## 📁 Files in This Repository

- **Data_Analyst_Intern_Assignment.xlsx**
  - Cleaned datasets (Events, Orders, Customers)
  - Funnel metrics and conversion rate calculation
  - Daily trend analysis (Active Users vs Ordering Customers)
  - Customer behavior insight (bar chart)
  - Summary sheet with explanations and assumptions

---

## 🧹 Data Cleaning Steps

- Converted `event_date` and `order_date` into proper Excel date format  
- Removed duplicate records from all datasets  
- Filtered Orders to keep only rows where `order_status = "Valid"`  
- Standardized `user_id` and `customer_id` as text to ensure reliable joins  

---

## 🔢 Key Calculations

- **Users with events:** 147,336  
- **Users who placed at least one valid order:** 36,077  
- **Conversion rate:**  
  \[
  36,077 \div 147,336 \approx 24.5\%
  \]

This means roughly **1 out of 4 active users** converted into a customer.

---

## 📈 Visualizations

1. **Time-series line chart**  
   - Daily Active Users vs Ordering Customers  
   - Shows how user engagement and purchases change over time  

2. **Bar chart (Customer Behavior Insight)**  
   - Analysis by **Acquisition Channel** (or City)  
   - Used to identify which segment performs best in terms of revenue or order value  

---

## 💡 Key Insights

- There is a clear gap between active users and ordering customers, showing room to improve conversion.  
- **Channel 1** generates the highest revenue, suggesting it brings more valuable or more frequent customers compared to other channels.

---

## ⚠️ Assumptions

- Only orders with `order_status = "Valid"` were considered for analysis  
- `net_sales` is treated as the final sale value  
- User and customer IDs were handled as text to avoid precision and formatting issues  
- The provided data is assumed to be correct for the given time period  

---

## 🛠 Tools Used

- Microsoft Excel  
  - Data cleaning  
  - Pivot tables  
  - Formulas  
  - Charts and visualizations  

---

## ✅ What This Project Demonstrates

- Ability to clean and prepare real-world data  
- Understanding of funnel metrics and conversion analysis  
- Skill in creating clear, useful visualizations  
- Ability to communicate insights in a simple, business-friendly way  

---

## 📌 How to Use

1. Download `Data_Analyst_Intern_Assignment.xlsx`  
2. Start with the **Summary** sheet to understand the analysis  
3. Explore:
   - `Events_Cleaned`
   - `Orders_Cleaned`
   - `Customers_Cleaned`
   - `Trend` (time-series chart)
   - `Insight` (bar chart)

---

👤 **Author:** Jalagam Dolender  
🎯 **Goal:** Data Analyst / Data Scientist role  

