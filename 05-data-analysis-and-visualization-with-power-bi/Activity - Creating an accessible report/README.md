# Creating an Accessible Report in Power BI

## Overview

This project demonstrates how to **improve the accessibility of a Power BI report** by applying inclusive design principles. The goal is to ensure that reports are usable by **all users, including individuals with disabilities**.

In this activity, an existing sales report was enhanced using accessibility best practices such as **descriptive titles, alt text, markers, accessible color themes, and proper tab order**.

These improvements make the report easier to navigate, interpret, and interact with for a wider audience.

---

# Business Scenario

Adventure Works recently expanded its sales team and welcomed a new member, **Logan**, who is visually impaired. To promote an inclusive work environment, the company requested the analytics team to ensure that all reports are **accessible and user-friendly**.

As a data analyst, your task was to **enhance an existing Power BI report** containing sales data for **February, March, and April across multiple regions**, ensuring it follows accessibility best practices.

---

# Objectives

The main objectives of this activity were:

* Improve chart accessibility using better formatting and design
* Add descriptive titles and alt text for visuals
* Improve visual readability using markers and accessible colors
* Enhance report navigation using tab order
* Apply an accessible theme to the report

---

# Dataset and Visualizations

The report contains sales data for three months and includes the following visuals:

* Line Chart
* Clustered Column Chart
* Stacked Bar Chart
* Report Title Text Box

These visuals were enhanced using accessibility features.

---

# Steps Performed

## 1. Open the Existing Report

The provided `.pbix` file was opened in **Power BI Desktop** to review the current report structure and identify areas for improvement.

---

# 2. Add a Meaningful Report Title

A clear and descriptive report title was added to help users understand the purpose of the report quickly.

### Updated Title

`Adventure Works Quarterly Regional Sales Report`

This provides context for all users and improves report clarity.

---

# 3. Improve Chart Visual Accessibility

## Update Chart Titles

Default visual titles were replaced with more descriptive titles.

Updated chart titles:

* **Monthly Order Quantities by Order Status**
* **Monthly Order Total by Product Region**
* **Monthly Order Quantities by Product Region**

These titles help users understand the data presented in each chart.

---

# Display Markers in the Line Chart

Markers were enabled in the line chart to improve readability.

Each region was assigned a **different marker shape** to help users distinguish data points without relying only on color.

Benefits:

* Helps color-blind users
* Makes trends easier to follow

---

# Add Alt Text to Visuals

Alternative text descriptions were added to each visual so **screen readers can describe charts to visually impaired users**.

Example Alt Text:

**Clustered Column Chart**

> From February to April, canceled orders remained the lowest category, processing orders increased steadily, and shipped orders grew significantly, especially in April.

**Line Chart**

> Order totals increased monthly across all regions, with Europe leading growth and Asia showing slower growth from March to April.

**Stacked Bar Chart**

> Total order quantities increased monthly across all regions, with Europe consistently leading in sales.

Alt text ensures that users who cannot see the visuals can still understand the insights.

---

# 4. Apply an Accessible Theme

An **accessible Power BI theme** was applied to improve contrast and readability.

Theme used:
`Accessible City Park`

Accessible themes provide:

* High contrast colors
* Clear visual hierarchy
* Improved readability

These features benefit users with **visual impairments or color vision deficiencies**.

---

# 5. Improve Keyboard Navigation with Tab Order

The **Selection Pane** was used to organize the tab order of visuals.

Updated tab order:

1. Report Title
2. Monthly Order Total by Product Region
3. Monthly Order Quantities by Order Status
4. Monthly Order Quantities by Product Region

This allows users to navigate the report using a **keyboard**, which is essential for users who cannot use a mouse.

---

# Accessibility Improvements Summary

The following accessibility improvements were implemented:

### Descriptive Titles

Clear titles were added to the report and visuals so users can quickly understand the content.

### Alt Text

Alt text descriptions were added to visuals to support **screen reader users**.

### Markers

Markers were enabled in the line chart to differentiate data points without relying only on color.

### Accessible Colors

An accessible theme was applied to improve **color contrast and readability**.

### Tab Order

Tab navigation was organized to improve **keyboard accessibility**.

---

# Learning Outcomes

After completing this activity, the following skills were developed:

* Designing inclusive Power BI reports
* Applying accessibility best practices
* Using alt text for screen readers
* Improving chart readability with markers
* Implementing accessible themes
* Enhancing report navigation using tab order

---

# Tools Used

* Microsoft Power BI Desktop
* Adventure Works Sales Dataset
* Accessible Power BI Themes

---

# File Included

`Creating an accessible report.pbix`

This file contains the final accessible version of the report.

---

# Author

**Ibrar Khan**

Data Analytics | SQL | Power BI | Python
