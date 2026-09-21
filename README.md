# financial-sales-analysis-excel# Financial Sales Analysis (Excel)

An end-to-end analysis of 700 sales records (September 2013 – December 2014) to identify which products, countries, segments, discount levels and months drive or erode profit. Built in Excel and presented in PowerPoint, structured around the CRISP-DM methodology.

## Business Problem
The business needs to understand how sales, costs, profit, discounts, products, countries, customer segments and months affect overall financial performance, and where to focus to improve profitability.

## Approach (CRISP-DM)
- **Business Understanding:** defined the problem statement and analysis goals.
- **Data Understanding:** 700 records, 16 fields, 5 segments, 5 countries, 6 products.
- **Data Preparation:** standardised inconsistent text, filled missing values (derived from related fields, otherwise median for numeric and mode for categorical fields).
- **Analysis:** 16 pivot tables summarising sales, COGS and profit by product, country, segment, discount band and month.
- **Evaluation:** findings checked against the problem statement; pivot totals reconcile across all views.
- **Deployment:** interactive dashboard with 13 charts and slicers, plus a report with recommendations.

## Key Findings
- Paseo is the top product: 33.1M in sales and 4.8M in profit.
- Government is the strongest segment (11.4M profit); Enterprise is the only loss-making segment.
- High discounts cut profit margin to 9.1%, against 14.4% for Medium and 17.9% for Low, without out-selling Medium.
- France is the most profitable country (3.77M); the United States has the highest sales and COGS but a lower margin.
- December is the peak profit month.

## Files
| File | Description |
|---|---|
| `project.xlsx` | Raw data, cleaned data, pivot tables and dashboard |
| `PROJECT_REPORT.pptx` | Full report with findings and recommendations |
| `PROJECT_REPORT.pdf` | PDF version of the report |

## Tools
Microsoft Excel (Pivot Tables, charts, slicers), Microsoft PowerPoint

## Author
Nicole Muthee
