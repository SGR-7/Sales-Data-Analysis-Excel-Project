# Analyzing 2015-2023 sales trend using **Pivot Tables/Charts & Power Query**

# Sales Performance Dashboard (Excel BI)

A dynamic, interactive **Sales Dashboard** built entirely in **Microsoft Excel**, leveraging **Power Query** for **ETL processes** and **Pivot Tables/Charts** for data visualization. This project tracks retail performance from **2015–2023**, providing actionable insights into **brand share**, **regional growth**, and **customer demographics**.
---

## Technical Stack

* **Microsoft Excel:** Core platform for analysis and visualization.
* **Power Query (M):** Used for data extraction, cleaning, and transformation.
* **Pivot Tables & Pivot Charts:** Used for multi-dimensional data aggregation.
* **Slicers:** Implemented for a seamless, interactive user experience.
---

## Executive Summary
The dashboard provides a high-level view of **$798.1k** in total sales across **10,308** orders. Key findings include:

* **Growth Trajectory:** A significant sales surge began in **2020**, peaking and stabilizing through **2023**.
* **Category Leader:** **Grains** is the top-performing category, significantly outperforming **Fruits** and **Meats**.
* **Brand Dominance:** **Brand B** command the largest market share, followed by **Brand D**.
* **Geographic Hub:** **Texas** represents the highest customer density, making it the most critical region for physical operations.
---

## The Data Workflow (ETL)
Unlike static spreadsheets, this dashboard is built on a structured data pipeline:

### 1. Data Cleaning (Power Query)
* **Standardization:** Used **Power Query** to ensure consistent naming conventions for **States** and **Categories**.
* **Data Typing:** Converted **"Sales"** and **"Average Order Value"** into **Currency** formats and **"Quantity"** into **Whole Numbers**.

### 2. Data Modeling
* Utilized **Pivot Tables** to create a **"Summary Layer"** that feeds the visual components.
* Calculated **Average Order Value ($77.42)** and **Top Category (Grains)** using specialized **Pivot calculations** to ensure the dashboard updates automatically when new data is added.

### 3. Interactivity
* Connected **Slicers (State, Year, Month)** to multiple **Pivot Charts** simultaneously using **Report Connections**. This allows the user to filter the entire dashboard with a single click.
---

## How to Use the Dashboard

1.  **Download** the **.xlsx** file from the **Dashboard/** folder.
2.  **Open** in **Excel** (**Enable Content/Macros** if prompted for the **Map visual**).
3.  **Interact:**
    * Use the **State Slicer** on the left to view data for specific regions.
    * **Filter by Year** to see how **Brand Share** evolved over time.
4.  **Refresh Data:** To add your own data, simply paste it into the **"Raw Data"** sheet and click **Data > Refresh All**.
---

## Key Insights & Recommendations
* **Market Saturation:** The plateau in **2022–2023** suggests the brand has reached a steady market share; future growth may require new product categories.
* **Gender Neutrality:** With a **52/48 male-to-female split**, marketing campaigns should remain broad and inclusive rather than gender-specific.
* **Logistics Focus:** With high customer counts in **Texas & California**, these states should be prioritized for **inventory warehousing** to reduce shipping times.
