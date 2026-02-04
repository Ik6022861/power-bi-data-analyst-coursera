# Exercise – Merging Two Tables in Power BI

## Overview
This project demonstrates how to merge two datasets in Microsoft Power BI using Power Query.  
The Adventure Works Sales and Product tables were combined to enrich sales data with product information.

## Data Sources
- Sales.xlsx
- Product.xlsx  
(Common column: ProductKey)

## Objective
To merge Sales and Product tables and produce a dataset containing:
- Sales Order Number
- Order Date
- Product Name
- Quantity
- Unit Price

## Steps Performed
1. Created a new Power BI project named *Exercise – Merging two tables*.
2. Imported Sales and Product Excel files into Power BI.
3. Opened Power Query Editor.
4. Merged Sales and Product tables using **ProductKey**.
5. Applied a **Left Outer Join**.
6. Expanded the Product column to include Product Name.
7. Removed unnecessary columns and reordered the final dataset.

## Result
The final table successfully combines sales and product data and is ready for analysis and reporting in Power BI.
