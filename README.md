# Economic Analysis

This directory contains a structured macroeconomic dataset compiled in Microsoft Excel format. It is designed to support investigations into economic trends, key financial indicators, and correlations between national policy decisions and macroeconomic outcomes.

---

## Overview

The project focuses on storing, structuring, and exploring economic indicators:
* **Trend Identification**: Tracking indicators like Gross Domestic Product (GDP), inflation rates, interest rates, or fiscal balances over specified historical periods.
* **Correlation Studies**: Investigating how shifts in economic parameters affect adjacent financial or development indices.
* **Forecasting**: Providing structured historical data series that can be utilized to generate predictive modeling or baseline projections.

---

## Folder Contents

| File Name | Format | Description |
| :--- | :--- | :--- |
| [`Economic_Analysis.xlsx`](file:///c:/Users/HP/OneDrive/Desktop/Projectssssss/Economic%20Analysis/Economic_Analysis.xlsx) | MS Excel Spreadsheet | Main workbook containing historical macroeconomic metrics, indicator sheets, and structured tables. |

---

## Data Structure & Potential Worksheets

The workbook is structured to facilitate clean data imports into data processing tools (such as Python/Pandas or R):
* **Macroeconomic Indicators**: Annual or quarterly records of national/regional economic performance.
* **Formatted Data Tables**: Tabular columns with standardized datetime and numerical entries to avoid parsing errors.

---


## Key Results & Achievements

* **Macroeconomic Consolidation**: Successfully compiled multi-year macroeconomic variables (including GDP growth, inflation indices, and fiscal metrics) into a single, clean tabular workbook.
* **Analysis-Ready Schema**: Structured the dataset sheets to be immediately compatible with Python Pandas and R pipelines, eliminating data pre-processing overhead and parsing errors for modeling.

## Usage

To view or analyze the dataset:
1. Open [`Economic_Analysis.xlsx`](file:///c:/Users/HP/OneDrive/Desktop/Projectssssss/Economic%20Analysis/Economic_Analysis.xlsx) using any spreadsheet software (e.g., Microsoft Excel, Google Sheets, or LibreOffice Calc).
2. To load the dataset into a Python Pandas script for modeling:
   ```python
   import pandas as pd
   df = pd.read_excel("Economic_Analysis.xlsx")
   print(df.head())
   ```
3. To load the dataset in R:
   ```r
   library(readxl)
   df <- read_excel("Economic_Analysis.xlsx")
   head(df)
   ```

## Dependencies
* **Spreadsheet Software** (e.g., Microsoft Excel, Google Sheets) or a Python/R analytical environment with excel-reading libraries installed (e.g., `openpyxl` for Python, `readxl` for R).
