# Coffee Shop Sales Performance Analysis | Excel

## Project Overview
This project analyzes six months of coffee shop transaction data (January–June 2023) to understand revenue trends, customer transaction patterns, product-category mix, and peak transaction hours. The workbook uses Excel-based data preparation, PivotTables, charts, and a dashboard with a store-location slicer.

## Business Questions
- How does revenue change month to month?
- Which product categories account for the most transactions?
- Which days and hours have the highest transaction volume?
- Which product types lead by transaction count versus revenue?
- How can the findings inform inventory planning and operational review?

## Workbook Structure
- `Transactions` — source transaction records.
- `Clean_Data` — analysis-ready data.
- `Pivot_tables` — summarized metrics used by the dashboard.
- `Final_Dashboard` — charts and a store-location slicer.

## Key Metrics
- Transaction records: **149,116**
- Total revenue: **$698,812.33**
- Analysis period: **January–June 2023**
- Highest-revenue month: **June, $166,485.88**
- Highest-volume hour: **10:00, with 18,545 transactions**

## Findings
### Revenue trend
Monthly revenue was $81,677.74 in January, fell to $76,145.19 in February, and then increased from March through June. June was the highest-revenue month at $166,485.88. This describes the observed trend; the workbook alone does not establish why revenue changed.

### Category transaction mix
Coffee recorded 58,416 transactions and Tea recorded 45,449, followed by Bakery (22,796) and Drinking Chocolate (11,468). These are transaction counts, not unique-customer counts.

### Peak hour
10:00 was the busiest hour in the summarized data, with 18,545 transactions. This may be a useful starting point for reviewing staffing and service operations, but transaction volume alone does not prove that staffing is insufficient.

### Product count versus revenue
The original product summary contains both transaction counts and revenue. These measures tell different stories: for example, Brewed Chai Tea has more transactions than Barista Espresso, while Barista Espresso has higher revenue in the current summary. A separate revenue-ranked file is included to make this comparison easier.

## Recommendations
1. Review the monthly revenue trend alongside store-level and transaction-level context before attributing causes to growth or decline.
2. Monitor Coffee and Tea availability because they lead the category transaction counts.
3. Review service flow around 10:00 using operational data before changing staffing.
4. Compare product transaction count, revenue, and—if cost data becomes available—profit before making product-priority decisions.
5. Use both transaction-count and revenue rankings when reviewing product performance.

## Tools
- Microsoft Excel
- Data cleaning and validation
- PivotTables
- Charts and dashboard slicer

## Project Files
- `Coffee_Sales_Excel_Dashboard_Upload.xlsx` — Excel workbook and dashboard.
- `Coffee_Shop_Top_Products_by_Revenue.csv` — product summary ranked by revenue, exported from the workbook's product summary.

## Data Quality Notes
The workbook's analysis range contains 149,116 transaction records. Before publishing, complete a final systematic check of missing values, duplicate transaction IDs, data types, and revenue calculations in Excel. The current summary values have been read from the workbook's PivotTables; this README does not claim that every possible data-quality issue has been ruled out. Revenue is not the same as profit, and no causal explanation for monthly changes is claimed.

## Limitations
- The data covers January–June 2023 only, so it does not show a full year or seasonality across multiple years.
- Revenue ranking does not establish profitability because product cost and margin are not part of the reported findings.
- Transaction counts should not be interpreted as unique customers.
- Recommendations are hypotheses for further review, not proven causes or guaranteed outcomes.
