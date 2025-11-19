# Power-BI-Projects
# 🚀 Power BI Data Analytics Portfolio: Sales & Business Intelligence

## Project Overview

This repository features a collection of Business Intelligence (BI) projects developed using **Microsoft Power BI Desktop**. These projects demonstrate proficiency across the entire BI workflow, from **data preparation and modeling** to **advanced DAX calculations** and the design of highly interactive, executive-level **dashboards**. The portfolio includes foundational practice and a comprehensive sales analysis solution.

***

## ⚙️ Core Power BI Skills Demonstrated

This portfolio validates expertise in the following key areas, which are essential for building robust BI solutions:

### 1. Data Transformation & Modeling (Power Query)
* **Data Types:** Practiced explicitly setting and converting **data types** (e.g., Currency, Date, Whole Number) in Power Query to ensure accurate calculations and aggregation.
* **Data Structure:** Managed the structure of the data, transforming the raw data and understanding how to build visualizations by dragging measures into **Visual Columns** and dimensions into **Visual Rows/Axes**.
* **Model Building:** Established and managed efficient **one-to-many relationships** between Fact and Dimension tables to allow correct filter propagation across the report.

### 2. Analytical Calculations (DAX)
* **Fundamental Functions:** Utilized core **DAX (Data Analysis Expressions)** functions like **`SUM()`**, **`AVERAGE()`**, **`COUNTROWS()`**, and **`CALCULATE()`** to define key business metrics.
* **Profit Calculation:** Successfully derived the essential business metric of **Profit** by creating a measure using DAX: `Profit = SUM(Sales[Revenue]) - SUM(Sales[Cost])`.
* **Time Intelligence:** Developed measures for comparative analysis, such as Year-to-Date (YTD) and Year-over-Year (YoY) growth.

### 3. Visualization & Interactivity
* **Dashboard Creation:** Designed multi-page **Dashboards** that are visually compelling and organized for clear data storytelling.
* **Visualization Types:** Employed a variety of charts, including Line Charts (for trends), Bar Charts (for comparison), and Maps, by effectively mapping data fields to the visual properties.
* **Filters and Slicers:** Applied various report, page, and visual-level **filters**. Utilized **Slicers** as the primary interactive element, allowing users to dynamically filter data by date, category, and region.
* **Marks/Aesthetics:** Effectively used the **Visual Formatting Pane** to control visual aesthetics—adjusting colors, axis scales, and data labels (Marks)—to emphasize key data points and improve readability.

***

## 📊 Project Deep Dives

### Project 1: Sales Analysis Dashboard
* **File:** `08-Solution-Sales Analysis.pbix`
* **Goal:** To provide a comprehensive, executive-level view of sales performance, profitability, and individual/regional contribution.

#### Key Focus Areas:
* **Profitability Analysis:** The central analysis revolves around the calculated **Profit** measure (derived in DAX as `Total Revenue - Total Cost`) and the resulting **Profit Margin %**.
* **"My Performance" Feature:** The dashboard includes functionality to analyze **individual performance** (e.g., a specific sales rep or manager). This feature typically uses DAX measures combined with **Slicers** to compare the selected individual's Sales and Profit metrics against the **overall company total** or specific **targets**. This is achieved by using functions like `ALLEXCEPT()` to maintain the context of the total while filtering the view by employee.
* **Visualizations:** Features KPI Cards for high-level summaries, Line Charts for long-term trend analysis, and Bar/Column charts for product and regional breakdowns.

### Project 2: Foundational Power BI Practice
* **File:** `POWER BI DAY 1.pbix`
* **Goal:** This project represents the initial learning phase, focusing on mastering the Power BI Desktop environment, correct data loading, and building basic visuals.

#### Key Focus Areas:
* **Interface Familiarity:** Practice navigating between the Report, Data, and Model views.
* **Basic Data Flow:** Focusing on the sequence: **Get Data** ➡️ **Transform Data (Power Query)** ➡️ **Load Data** ➡️ **Visualize**.
* **Visual Building Blocks:** Practiced dragging measures and dimensions into the rows and columns of the visuals and observing how data types and aggregation functions influence the resulting chart output.

***

## 🚀 How to View the Projects

1.  **Clone the Repository:** Download the repository files to your local machine.
2.  **Install Power BI Desktop:** Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/downloads/) installed.
3.  **Open the Files:** Open both `.pbix` files.
4.  **Inspect the Model:** Navigate to the **Model View** to inspect table relationships and the **Data View** to examine applied data types and calculated columns.
5.  **Interact with the Reports:** Engage with the **Slicers** and click on different elements of the charts to experience the dynamic filtering capabilities of the dashboards, particularly in the Sales Analysis project.
