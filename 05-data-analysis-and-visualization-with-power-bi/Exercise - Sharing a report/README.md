# Power BI Exercise: Sharing a Report

## Overview

This exercise demonstrates how to paginate, publish, and export a Power BI report using the Adventure Works Product Sales dataset. The goal is to organize report visuals across multiple pages and share the report through Power BI Service.

By completing this exercise, you will learn how to:

* Navigate Power BI Desktop views
* Create and rename report pages (pagination)
* Distribute report visuals across pages
* Publish a report to Power BI Service
* Export a report as a PDF file

---

## Prerequisites

Before starting this exercise, ensure you have:

* Power BI Desktop installed
* Access to the Adventure Works Product Sales Report (.pbix file)
* A Power BI account to publish reports

---

## Step 1: Open the Report

1. Open **Power BI Desktop**.
2. Click **File**.
3. Navigate to the location where the `.pbix` report file is saved.
4. Select the file and click **Open**.

---

## Step 2: Observe the Data

1. From the left navigation bar, select **Table View**.
2. Review the dataset displayed in the center of the screen.
3. Locate the **Product Name** column.
4. Observe the first 10 records to understand the structure of the dataset.

---

## Step 3: Switch to Report View

1. From the left navigation panel, select **Report View**.
2. This view allows you to design and organize visual reports.

---

## Step 4: Create Pages for Pagination

1. Navigate to the **Pages section** at the bottom of the screen.
2. Click the **+ (New Page)** button.
3. Add **two new report pages**.

---

## Step 5: Rename the Pages

### Rename First Page

1. Select the first new page.
2. Open the **Format pane** in the Visualizations panel.
3. Expand **Page Information**.
4. Change the page name to:

```
Sales Monthly Summary
```

### Rename Second Page

Repeat the same steps and rename the second page to:

```
Top Product Categories
```

---

## Step 6: Distribute Report Content Across Pages

Move visuals from the main report page to the new pages.

### Move Visual 1

* Move **Order Total by Product Category** visual to the page:

```
Top Product Categories
```

### Move Visual 2

* Move **Order Total by Month** visual to the page:

```
Sales Monthly Summary
```

This step helps organize the report and improves readability.

---

## Step 7: Publish the Report

> Note: The report must be saved before publishing.

1. Click **Save**.
2. Go to the **Home** tab.
3. Click **Publish**.
4. Select **My Workspace**.
5. Click **Select**.

Power BI will upload the report to **Power BI Service**.

Once publishing is complete:

* A confirmation message will appear.
* Click **Open** to view the report online.

---

## Step 8: Export the Report

1. Click the **Export** button.
2. Select **PDF** from the dropdown menu.
3. In the **Export with** option, choose:

```
Current Values
```

4. Click **Export**.

The report will be downloaded as a PDF file.

---

## Result

After completing this exercise, you will have:

* Organized report visuals using pagination
* Published the report to Power BI Service
* Exported the report as a PDF for sharing

---

## Conclusion

This exercise demonstrates how Power BI enables analysts to transform raw data into structured reports that can be easily shared with stakeholders. By organizing visuals across pages, publishing reports to the cloud, and exporting them into shareable formats, analysts can provide meaningful insights to help guide business decisions.

---

## Author

Data Analytics Practice Exercise
