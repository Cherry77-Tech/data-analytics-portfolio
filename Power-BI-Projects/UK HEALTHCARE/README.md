# UK Private Healthcare Financial Dashboard

## Project Overview
An interactive Power BI dashboard for exploring financial performance in a UK private healthcare dataset. The project is designed to help users review revenue and costs, outstanding balances, and performance across healthcare departments and service categories.

## Tools
- **Power BI Desktop** — dashboard development and interactive reporting
- **Power Query** — data import, transformation, and preparation
- **Excel workbook** — source data

## Data Source
The report connects to `UK_Private_Healthcare_Financial_Dashboard_Data.xlsx`, which contains these worksheets:
- `Healthcare_Data`
- `City_Summary`
- `Department_Summary`

The workbook is a local source file. Update the source path in Power Query if the workbook is moved to another folder. The dataset should be described as synthetic or anonymised only if that matches the actual source; do not publish confidential patient or client information.

## Dashboard Focus
The analysis is intended to support review of:
- Revenue and cost performance
- Outstanding balances and payment status
- Department-level comparisons
- City-level comparisons
- Financial patterns across healthcare services

Use the measures and visuals present in the actual report as the authoritative list of KPIs.

## Project Structure
```text
UK-Private-Healthcare-Financial-Dashboard/
├── README.md
├── dashboard/
│   └── UK_Private_Healthcare_Financial_Dashboard.pbix
├── data/
│   └── UK_Private_Healthcare_Financial_Dashboard_Data.xlsx
└── screenshots/
    ├── power-query-source-path.png
    └── source-workbook-location.png
```

## Reproducibility
1. Open the Power BI report in Power BI Desktop.
2. Ensure the source workbook is available in the `data/` folder.
3. If necessary, update the file path in Power Query's **Source** step.
4. Select **Close & Apply**, then refresh the report.
5. Review the visuals after refresh to confirm that the data loaded correctly.

## Privacy and Data Limitations
Before publishing, verify that the workbook contains no personally identifiable information, confidential client data, or licensed data that cannot be redistributed. Do not publish raw data unless its sharing terms permit it. If the workbook is synthetic, state that explicitly and explain that the dashboard is a portfolio demonstration rather than evidence of real provider performance.

## Portfolio Note
The included screenshots document the source-file setup. Add a clear screenshot of the finished Power BI dashboard to this folder before publishing the repository so visitors can preview the report without opening the `.pbix` file.
