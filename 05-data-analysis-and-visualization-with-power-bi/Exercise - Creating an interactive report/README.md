# Creating an Interactive Report in Power BI

## Overview

This project demonstrates how to build an **interactive sales report using Microsoft Power BI**. The goal of the report is to help stakeholders explore quarterly sales data and highlight important insights related to **Mountain Bike sales during the first quarter (Q1)**.

The report was designed to improve user experience by enabling dynamic data exploration through **drillthrough navigation, slicers, and bookmarks**.

---

# Business Scenario

You are a **Data Analyst at Adventure Works** preparing a quarterly sales report for the CEO. After analyzing the sales data, you discovered an important trend:

* Sales for **Mountain Bikes increase significantly toward the end of Q1**, especially in **March**, as customers prepare for summer.

To help the CEO explore this insight interactively, the report includes:

* Drillthrough functionality for deeper data analysis
* Slicers for easy filtering of product categories
* Bookmarks to quickly highlight key insights

---

# Project Features

## 1. Drillthrough for Data Exploration

A **Drillthrough page** called **Sales Detail** was created to allow users to explore detailed information behind the summary chart.

Users can:

* Right-click a data point
* Select **Drillthrough → Sales Detail**
* View detailed sales data for that specific month

### Sales Detail Page Includes

* Table visualization
* Customer Location
* Order Total
* Summary row showing total revenue

---

## 2. Slicer for Product Category Filtering

A **Slicer** was added to the Sales Summary page to allow users to filter sales by **Product Category**.

Example:

* Mountain Bikes
* Road Bikes
* Touring Bikes

This enables stakeholders to quickly focus on specific product categories.

---

## 3. Bookmark for Key Insight

A **Bookmark** was created to highlight a key business insight.

### Bookmark Name

`March Mountain Bikes Revenue`

This bookmark saves a report state where:

* Product Category = **Mountain Bikes**
* Month = **March**
* The report automatically drills through to the **Sales Detail page**

This allows the CEO to quickly view the important sales trend without manually filtering the report.

---

# Steps Performed in the Exercise

### Step 1: Create Sales Detail Page

* Added a new report page called **Sales Detail**
* Created a **Table Visualization**
* Displayed:

  * Customer Location
  * Order Total
* Recorded total revenue from the summary row

---

### Step 2: Configure Drillthrough

* Expanded **Order Date hierarchy**
* Added **Month** to the **Drillthrough field**
* Enabled navigation from the summary chart to the Sales Detail page
* Used the automatic **Back Button** to return to the main report page

---

### Step 3: Add Product Category Slicer

* Inserted a **Slicer Visual**
* Used **Product Category** as the filter field
* Allowed dynamic filtering of report data

---

### Step 4: Create Bookmark

* Filtered the report to:

  * **Product Category = Mountain Bikes**
* Right-clicked **March** column
* Selected **Drillthrough → Sales Detail**
* Created a bookmark named:

`March Mountain Bikes Revenue`

---

# Key Power BI Concepts Used

* Drillthrough Navigation
* Slicers
* Bookmarks
* Interactive Filtering
* Table Visualizations
* Report Navigation

---

# Learning Outcomes

After completing this exercise, I learned how to:

* Build interactive reports in Power BI
* Enable drillthrough navigation for deeper analysis
* Use slicers to filter report data dynamically
* Create bookmarks to highlight important insights
* Improve report usability for business stakeholders

---

# File Included

`Creating an interactive report.pbix`

This Power BI file contains the completed interactive report.

---

# Tools Used

* Microsoft Power BI
* Adventure Works Sales Dataset

---

# Author

**Ibrar Khan**

Data Analytics | Power BI 
