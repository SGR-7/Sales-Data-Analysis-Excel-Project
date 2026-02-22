# Sales Performance Dashboard (Excel BI)

A dynamic, interactive Sales Dashboard built entirely in Microsoft Excel. This project leverages **Power Query** for ETL processes and **Pivot Tables/Charts** for data visualization to track retail performance from 2015–2023.

---

## Technical Stack

* **Microsoft Excel:** Core platform for analysis and visualization.
* **Power Query (M):** Used for data extraction, cleaning, and transformation.
* **Pivot Tables & Charts:** Used for multi-dimensional data aggregation.
* **Slicers:** Implemented for a seamless, interactive user experience.

---

## Executive Summary

The dashboard provides a high-level view of **$798.1k** in total sales across **10,308** orders. 

### Key Findings:
* **Growth Trajectory:** A significant sales surge began in 2020, peaking and stabilizing through 2023.
* **Category Leader:** *Grains* is the top-performing category, significantly outperforming *Fruits* and *Meats*.
* **Brand Dominance:** *Brand B* commands the largest market share, followed by *Brand D*.
* **Geographic Hub:** *Texas* represents the highest customer density.

---

## The Data Workflow (ETL)

Unlike static spreadsheets, this dashboard is built on a structured data pipeline:

### 1. Data Cleaning (Power Query)
* **Standardization:** Ensured consistent naming conventions for States and Categories.
* **Data Typing:** Converted "Sales" and "Average Order Value" into Currency formats.

### 2. Data Modeling
* Utilized Pivot Tables to create a "Summary Layer."
* Calculated **Average Order Value ($77.42)** and **Top Category (Grains)** using automated calculations.

### 3. Interactivity
* Connected **Slicers** (State, Year, Month) to multiple Pivot Charts simultaneously using *Report Connections*.

---

## How to Use the Dashboard

1.  **Download:** Grab the `.xlsx` file from the `Dashboard/` folder.
2.  **Open:** Open in Excel (Enable Content/Macros if prompted for the Map visual).
3.  **Interact:** * Use the **State Slicer** on the left to view specific regions.
    * Filter by **Year** to see brand evolution.
    * **Refresh Data:** To add your own data, paste it into the "Raw Data" sheet and click `Data > Refresh All`.

---

## Key Insights & Recommendations

* **Logistics Focus:** With high customer counts in Texas & California, these states should be prioritized for inventory warehousing to reduce shipping times.
* **Market Saturation:** The plateau in 2022–2023 suggests future growth may require new product categories.
* **Gender Neutrality:** With a 52/48 male-to-female split, marketing campaigns should remain broad and inclusive.

---
