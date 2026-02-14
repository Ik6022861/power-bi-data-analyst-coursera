\# Exercise - Using Time Intelligence to Compare to Previous Year



\## Overview

This exercise demonstrates the use of DAX time intelligence functions in Power BI to evaluate year-over-year (YoY) sales performance for Adventure Works.



\## Objectives

By completing this exercise, we:



\- Created measures to compare Adventure Works’ year-over-year sales growth.

\- Applied proper data formatting for currency and percentage measures.

\- Built a matrix visualization to analyze monthly and annual sales trends.



\## Scenario

Adventure Works needed to analyze sales performance and growth to support business planning for the next financial year. The goal was to compare current year sales with previous year sales and calculate year-over-year changes.



\## Steps Performed



\### 1. Data Preparation

\- Loaded the AdventureWorks.pbix file into Power BI.

\- Verified and reviewed the Sales, Products, Region, and Salesperson tables.

\- Checked relationships and data quality.



\### 2. Created Revenue Measure

Used DAX SUMX function:



Revenue = SUMX(Sales, Sales\[Unit Price] \* Sales\[Quantity])



Formatted as currency with two decimal places.



\### 3. Created Previous Year Revenue Measure



RevenuePY =

CALCULATE(

&nbsp;   \[Revenue],

&nbsp;   SAMEPERIODLASTYEAR('Date'\[Date])

)



Formatted as currency.



\### 4. Created Revenue YoY %



Revenue YoY % =

DIVIDE(

&nbsp;   \[Revenue] - \[RevenuePY],

&nbsp;   \[RevenuePY]

)



Formatted as percentage with two decimal places.



\### 5. Created Matrix Visualization

\- Added Year and Month to rows.

\- Added Revenue, RevenuePY, and Revenue YoY % to values.

\- Analyzed monthly and annual trends.



\## Conclusion

This exercise demonstrates how DAX time intelligence functions such as CALCULATE, SAMEPERIODLASTYEAR, and DIVIDE can be used to evaluate business growth. Proper measure formatting and visualization allow Adventure Works to make data-driven decisions.



