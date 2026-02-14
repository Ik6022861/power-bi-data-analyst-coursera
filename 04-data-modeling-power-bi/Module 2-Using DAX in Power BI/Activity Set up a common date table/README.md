# 📅 Activity: Set Up a Common Date Table (Power BI)

---

## 📌 Overview

This exercise focuses on creating a **Common Date Dimension Table** in Power BI using DAX.  
A properly structured date table is essential for performing **time intelligence analysis**, improving model performance, and enabling advanced reporting capabilities.

---

## 🏢 Case Study: Adventure Works

The existing data model contains the following tables:

- Sales  
- Salesperson  
- Products  
- Reseller  
- Region  

However, the model lacks a **Date Dimension Table**, making time-based analysis (YTD, MTD, YoY, etc.) difficult.

---

## 🎯 Objective

To create and configure a **Date Dimension Table** using DAX and integrate it into the existing data model to support time intelligence calculations.

---

## 🛠 Implementation Steps

### 1️⃣ Load the Project File

Opened `AdventureWorks.pbix` containing the existing data model.

---

### 2️⃣ Create Date Table Using DAX

Created a new calculated table using:

```DAX
Date = CALENDAR ( DATE(2017,1,1), DATE(2021,12,31) )

---

3️⃣ Add Date Attributes 

Enhanced the Date table with additional time-related columns:

Year = YEAR('Date'[Date])
Month = FORMAT('Date'[Date], "MMMM")
Month Number = MONTH('Date'[Date])
Day of the Week = FORMAT(WEEKDAY('Date'[Date]), "dddd")
Week Number = WEEKNUM('Date'[Date])

---

4️⃣ Mark as Date Table

The table was marked as an official Date Table in Power BI:

Selected Mark as Date Table

Assigned the Date column

Validation completed successfully

---

5️⃣ Create Relationships

Established relationships between:

Date Table → Sales Fact Table

----

📊 Outcome

The data model now supports:

Time Intelligence calculations (YTD, MTD, YoY)

Trend analysis

Historical performance tracking

Improved reporting accuracy

---

🚀 Key Takeaways

A Date Dimension is essential for professional data models

DAX provides full control over calendar creation

Proper date modeling improves scalability and analytical flexibility

---

👨‍💻 Author

Ibrar Khan

