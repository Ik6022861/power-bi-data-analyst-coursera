# Activity: Using the CALCULATE Function

## Overview
This activity focuses on understanding and applying the **CALCULATE** function in DAX within Power BI. The goal is to modify filter context in calculations to answer specific business questions.

## Case Study: Adventure Works

Adventure Works required:
- Total Revenue calculation
- Non-US Revenue calculation
- Sales of Black Road Bikes
- Sales by Sales Managers

## Key Concepts Applied

### 1. Using CALCULATE to Modify Filter Context
The CALCULATE function changes the filter context of a measure to return specific analytical results.

### 2. Non-US Sales Measure
Used CALCULATE with FILTER to exclude United States sales:

```DAX
Non-US Sales =
CALCULATE (
    [Total Revenue],
    FILTER ( Region, Region[Country] <> "United States" )
)
