# Online Retail Dataset Analysis using Microsoft Excel

## Project Overview

This project presents an end-to-end data analysis of the **Online Retail Dataset**, covering transactions from **December 2010 to December 2011**. The dataset belongs to a UK-based non-store online retail company that primarily sells unique all-occasion gift items, with many customers being wholesalers.
The analysis focuses on cleaning the raw transactional data, deriving key business metrics, and uncovering actionable insights to understand sales trends and overall business health.

## Project Objectives

- Perform thorough data cleaning and preprocessing to ensure data quality and accuracy.
- Create new calculated fields to support meaningful business analysis.
- Analyze sales trends over time (monthly performance).
- Understand the impact of returns and cancellations on overall sales.
- Provide data-driven insights and recommendations to support business decision-making.
- Build a clear and professional Excel dashboard for visualization.

## Dataset Description

**Original Columns:**
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

**Derived Columns Created:**
- **Net Quantity** — Quantity with negative values (returns/cancellations) replaced by 0
- **Net Unit Price**
- **Sales** — Calculated as `Net Quantity × Net Unit Price`
- **Invoice Month** — Extracted from InvoiceDate for time-based analysis

The dataset contains transactional records including purchases and returns.

## Data Cleaning & Preprocessing

Several data quality issues were identified and handled professionally:

### Issues Identified:
- Negative values in the **Quantity** column (product returns or order cancellations)
- Blank rows in the **Description** column
- Duplicate records
- Unnecessary columns for this analysis (`Description` and `CustomerID`)

### Cleaning Steps Performed:
1. **Negative Quantities** — Replaced with **0** instead of deleting rows. This approach preserves the records while preventing returns from negatively skewing total sales calculations.
2. **Duplicates** — Removed using Excel’s built-in **Remove Duplicates** tool.
3. **Blank Description rows** — Retained as they had no significant impact on the analysis.
4. **Derived Metrics** — Added four new calculated columns to enable deeper analysis.

All cleaning operations were performed in Microsoft Excel.

## Key Insights

The analysis revealed several important business findings:

- **Total Sales Performance**: The business generated significant revenue over the 13-month period, with clear seasonal patterns.
- **Monthly Trends**: Sales showed strong growth toward the end of the year from September to December (especially November and December), likely driven by holiday and festive gifting demand.
- **Returns Impact**: A notable portion of transactions involved returns or cancellations. Handling them by setting  Quantity to zero provided a more accurate view of actual sellable revenue.
- **Geographic Distribution**: The United Kingdom dominated sales, as expected for a UK-based retailer, while other countries contributed through international wholesale customers.
- **Cancellation & Return Rate**: Highlighted the need for better quality control, accurate product descriptions, and improved customer expectation management to reduce return rates.

These insights can help the business optimize inventory planning, improve marketing focus during peak seasons, and reduce losses from returns.

## Technologies & Tools Used

- **Microsoft Excel** (Primary tool)
  - Data Cleaning & Transformation
  - Formulas & Calculated Columns
  - PivotTables
  - Charts & Visualizations
  - Remove Duplicates Feature


  - Charts & Visualizations
  - Remove Duplicates Feature
