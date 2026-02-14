\# Activity: Set Up a Common Date Table



\## Introduction

In this lesson, we explored the importance of creating a common date table in a Power BI data model. A date dimension table is essential for performing time intelligence analysis. This exercise demonstrates how to create and configure a date table using DAX in Power BI.



\## Case Study

Adventure Works collects data from multiple tables including:



\- Sales

\- Salesperson

\- Products

\- Reseller

\- Region



However, the data model does not contain a date dimension table, which limits time-based analysis.



\## Objective

The objective of this exercise is to create a common date table using DAX and configure it properly to support time intelligence calculations.



\## Steps Performed



\### 1. Open AdventureWorks.pbix

Loaded the provided Power BI file containing the existing data model.



\### 2. Create Date Table Using DAX

Used the following DAX formula:



Date = CALENDAR ( DATE(2017,1,1), DATE(2021,12,31) )



This created a table containing a continuous list of dates.



\### 3. Add Date Attributes

Additional columns were created using DAX:



Year = YEAR('Date'\[Date])

Month = FORMAT('Date'\[Date], "MMMM")

Month Number = MONTH('Date'\[Date])

Day of the Week = FORMAT(WEEKDAY('Date'\[Date]), "dddd")

Week Number = WEEKNUM('Date'\[Date])







These columns allow detailed time-based analysis.



\### 4. Mark as Date Table

The table was marked as a Date Table in Power BI and validated successfully.



\### 5. Create Relationships

Established relationships between the Date table and the Sales fact table.



\## Conclusion

By creating and configuring a date dimension table, the data model now supports advanced time intelligence calculations. This improves reporting, historical performance analysis, and enables predictive insights. Mastering date tables is essential for building scalable and efficient Power BI data models.







