# Exercise: Adding a Measure (Power BI – DAX)

## 📌 Overview
This exercise focuses on applying DAX and Power BI Quick Measures to analyze Adventure Works’ sales data. The goal is to enhance the data model by creating meaningful measures that support business analysis and reporting.

## 🎯 Objectives
By completing this exercise, you will be able to:
- Create a Quick Measure in Power BI.
- Write a custom DAX measure using the formula bar.
- Format measures using appropriate data types (currency with two decimal places).
- Understand how DAX evaluates calculations within a data model.

## 📊 Scenario
Adventure Works wants to analyze its sales performance over time. The primary objective is to compute a **running total of sales by year**, along with a **Total Revenue** measure to better understand overall business performance.

The provided Power BI project (**AdventureWorks.pbix**) contains a data model with five tables:
- Salesperson  
- Region  
- Date  
- Products  
- Sales  

## 🛠️ What Was Done (Exercise Steps)

### **Step 1 – Load the Power BI Project**
- Downloaded and opened **AdventureWorks.pbix** in Power BI Desktop.
- Reviewed the existing data model.

### **Step 2 – Create a Quick Measure**
- Created a Quick Measure named **Running Total in Year** using:
  - **Total Sales** from the Sales table  
  - **Year** from the Date table  
- Formatted the measure as **Currency (2 decimal places).**

### **Step 3 – Create a DAX Measure**
Created a new measure in the **Sales** table:

```DAX
Total Revenue =
SUMX(
    Sales,
    Sales[Quantity] * Sales[Unit Price]
)
