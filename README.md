# Mobile Sales Dashboard and MTD Report

## Overview

This project involves building an **interactive Power BI dashboard** to visualize mobile sales data and generate a **Month-to-Date (MTD) report** for performance analysis. The purpose is to provide stakeholders with a platform to track mobile sales trends and monitor sales performance in real-time.

## Key Features

- **Interactive Dashboard:**  
  The Power BI dashboard visualizes mobile sales data with dynamic filters (such as date range, product categories, regions, etc.), allowing users to explore various sales metrics interactively.

- **MTD Report Generation:**  
  The project includes a Month-to-Date (MTD) report that calculates the total sales, units sold, and compares current performance with historical data. The report is generated and displayed in Excel and can be incorporated into the Power BI dashboard.

- **Real-Time Data Updates:**  
  The dashboard dynamically reflects the most up-to-date sales data by linking to the latest Excel files or data sources.

## Tools & Technologies Used

- **Power BI**:  
  Used to build the interactive dashboard and visualizations.

- **Excel**:  
  Used for storing and manipulating raw sales data, including filtering, cleaning, and preparing data for analysis.

- **DAX (Data Analysis Expressions)**:  
  Used within Power BI to create calculated columns, measures, and aggregations (e.g., MTD calculations).

## Project Structure

```bash
/Project_Root
│
├── /data
│   └── Mobile Sales Data.xlsx.xlsx          # Raw sales data stored in Excel
│
├── /powerbi
│   └── MS_Dashboard -.pbix  # Power BI dashboard (.pbix) file
│
├── README.md                    # Project documentation
└── LICENSE                      # License details (if applicable)

### Key Points:
**Images for Power BI Dashboard and MTD Report:**
```
Mobile Sales Dashboard
![Mobile Sales Dashboard](./Dashboard.jpg)

Same Period Last Year report
![Same Period Last Year report](./Same%20Period%20Last%20Year%20report.jpg)
MTD Report
![MTD Report](./MTD%20Report.jpg)

```