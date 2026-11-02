# SWYNEX – Interactive Data Analytics Dashboard (Task 3)

## Project overview
This project presents an interactive dashboard built from the cleaned Task 1 dataset and aligned with the findings in the Task 2 Exploratory Data Analysis workbook.

## Dashboard technology
- **Plotly.js** for interactive charts and data visualizations
- **HTML, CSS and JavaScript** for the dashboard interface, filters and KPI calculations
- **Excel** support workbook for tabular analysis and review

This is a standalone browser-based interactive dashboard. It is **not a Power BI (.pbix) or Tableau workbook**. It is an alternative interactive dashboard implementation using Plotly.js, which can be opened in a modern web browser.

## Dashboard features
- KPI cards: Total Records, Total Amount, Average Amount and Unique Cities
- Amount by Country
- Top 10 Cities by Amount
- Monthly Amount Trend
- Amount Distribution
- Interactive Country, City, From Date and To Date filters
- Seven key findings aligned with the Task 2 EDA workbook

## Dataset overview
- 120 cleaned records
- 9 countries
- 12 cities
- Date coverage: 01 September 2025 to 25 June 2026
- Total Amount: 13,613.31

The source dataset does not specify a currency, so amounts are displayed without a currency symbol.

## Files
- `interactive_dashboard.html` – open this file in Chrome, Edge or another modern browser to use the dashboard.
- `SWYNEX_Task3_Dashboard_Support.xlsx` – Excel support workbook with dashboard summary, country analysis, city analysis, monthly trends and cleaned data.
- `Task1_Cleaned_Source.xlsx` – cleaned source workbook.
- `cleaned_dataset.csv` – cleaned dataset in CSV format.
- `key_findings.md` – key findings from the analysis.

## How to use
1. Download or clone this repository.
2. Open `interactive_dashboard.html` in a modern browser.
3. Select a country, city or date range using the filters. KPI cards and charts update based on the selection.
4. For supporting tables, open `SWYNEX_Task3_Dashboard_Support.xlsx` in Excel.

## Data integrity note
The dashboard uses the supplied cleaned dataset. No currency has been assumed. Key findings are cross-checked against the Task 2 EDA workbook.
