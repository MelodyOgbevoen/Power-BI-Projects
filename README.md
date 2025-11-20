# Power-BI-Projects
# 🚀 Power BI Data Analytics Portfolio: Sales & Financial Reporting

## Project Overview

This repository showcases a comprehensive portfolio of Business Intelligence (BI) projects developed using **Microsoft Power BI Desktop**. These projects demonstrate proficiency across the entire BI workflow, from **data connection and transformation** to **advanced DAX modeling** and the creation of highly interactive, executive-level **dashboards** in both Sales and Financial domains.

***

## ⚙️ Core Power BI Skills Demonstrated

### 1. Data Transformation & Modeling (Power Query)
* **Data Types:** Proficiently connected to raw sources (Excel, CSV) and managed **data types** (e.g., converting text to whole number, decimal to currency) to ensure accurate calculations.
* **Data Cleansing:** Applied transformation steps in Power Query to handle errors, rename fields, and structure the data for optimal performance.
* **Visual Building Blocks:** Understood how to construct visualizations by dragging measures into **Visual Columns** and dimensions into **Visual Rows/Axes**, controlling the visual aggregation.
* **Model Building:** Established and managed relationships between tables (Fact and Dimension) to create robust analytical models.

### 2. Analytical Calculations (DAX)
* **Fundamental Functions:** Utilized core **DAX (Data Analysis Expressions)** functions like **`SUM()`**, **`AVERAGE()`**, **`COUNTROWS()`**, and **`CALCULATE()`** to define key business metrics.
* **Profit Calculation:** Successfully derived the essential business metric of **Profit** by creating a measure using DAX:
    * `Profit = SUM(Sales[Revenue]) - SUM(Sales[Cost])` (or similar logic based on COGS).
* **Time Intelligence:** Developed measures for comparative analysis, such as Year-to-Date (YTD) and Year-over-Year (YoY) metrics.
* **Context Control:** Mastered the use of filter functions (e.g., `ALL`, `FILTER`) within `CALCULATE` for advanced comparative analysis (e.g., "My Performance" vs. total company).

### 3. Visualization & Interactivity
* **Dashboard Design:** Created visually compelling and well-structured **Dashboards** that adhere to best practices for data storytelling.
* **Visualization Types:** Utilized a variety of visuals (Line, Bar, Map, KPI Cards) by correctly placing fields in the visual's **Rows** and **Columns** to convey clear insights.
* **Filters and Slicers:** Implemented various report, page, and visual-level **filters**. Extensive use of **Slicers** for dynamic user interaction and on-the-fly data segmentation.
* **Marks/Aesthetics:** Utilized the formatting options to refine visual encoding (**Marks**), controlling color, size, and data labels for maximum impact and readability.

***

## 📊 Project Deep Dives

### Project 1: Executive Summary – Finance Report (Core Financials)
* **Power BI File:** `Executive Summary – Finance Report.pbix`
* **Source Data:** `Financial Sample.xlsx - Sheet1.csv`
* **Focus:** Comprehensive financial performance reporting, providing management with a clear view of revenue, cost, and profitability across the business.

#### Key Analysis & Visualizations:
* **Core Metrics:** Calculation and tracking of **Gross Sales**, **Sales**, **COGS (Cost of Goods Sold)**, and the calculated **Profit**.
* **Profitability Breakdown:** Analysis of Profit and Profit Margin (%) segmented by **Segment**, **Country**, and **Product**.
* **Discount Band Analysis:** Visualizing the relationship between different `Discount Bands` (e.g., High, Medium, Low) and their direct impact on volume (`Units Sold`) and overall `Profit`.
* **Temporal Trends:** Line charts tracking **Sales** and **Profit** across the `Year` and `Month` to identify seasonality and growth rates.

### Project 2: Sales Analysis Dashboard (Performance Tracking)
* **Power BI File:** `08-Solution-Sales Analysis.pbix`
* **Focus:** Detailed sales and profitability analysis, with an emphasis on individual and regional performance tracking.

#### Key Focus Areas:
* **Profit Calculation:** Uses the DAX formula for `Profit = Total Sales - Total Cost` to drive margin analysis.
* **"My Performance" Feature:** This feature demonstrates an intermediate DAX skill. It utilizes **Slicers** and advanced **DAX filter context control** to allow a user to select an individual or team and see their Sales/Profit metrics compared side-by-side with the **Overall Company Total** or their **Goal/Target**.
* **Visualizations:** Features KPI Cards, Line Charts for temporal trends, and Geographic Maps for regional sales contribution.

### Project 3: Foundational Power BI Practice
* **Power BI File:** `POWER BI DAY 1.pbix`
* **Focus:** Mastering the basic BI workflow, ensuring correct data loading, and building simple, accurate visualizations based on initial data exploration.

#### Key Learning Focus:
* Practicing the fundamental data flow sequence and ensuring all required columns (e.g., numerical fields used for `SUM` or `AVERAGE`) are loaded with the correct data type.
* Building initial basic visuals like **clustered column charts** and **pie charts** to break down basic metrics by simple dimensions.

***

## 📂 Repository Files

| File Name | Project | Description |
| :--- | :--- | :--- |
| `Executive Summary – Finance Report.pbix` | **Finance Report** | The comprehensive Power BI dashboard for financial performance analysis. |
| `Financial Sample.xlsx - Sheet1.csv` | **Finance Report** | The clean transactional data source used to build the Finance Report. |
| `08-Solution-Sales Analysis.pbix` | **Sales Analysis** | The solution file for the advanced Sales Analysis (My Performance) project. |
| `POWER BI DAY 1.pbix` | **Foundational Practice** | Initial project demonstrating mastery of the basic Power BI interface and data flow. |

***

## 🚀 How to View the Projects

1.  **Clone the Repository:** Download the repository files to your local machine.
2.  **Install Power BI Desktop:** Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/en-us/downloads/) installed.
3.  **Open the Files:** Open all `.pbix` files.
4.  **Inspect the Model & DAX:** Navigate to the **Model View** to inspect table relationships and the **Data View** to examine applied data types and calculated measures.
5.  **Interact with the Reports:** Use the **Slicers** and click on different elements of the charts to experience the dynamic filtering and drill-down capabilities of the dashboards.
