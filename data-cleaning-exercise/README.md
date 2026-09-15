# Power BI Data Cleaning Exercise

## Overview
A small exercise cleaning a raw dataset in Power Query to make it analysis-ready — resolving irrelevant columns, blank rows, duplicates, inconsistent text formatting, and data type/error issues.

## Steps Applied

| # | Step | What I Did |
|---|------|------------|
| 1 | **Removed Column** | Dropped a log-detail column not needed for analysis |
| 2 | **Removed Blank Rows** | Removed rows with no data |
| 3 | **Removed Duplicates** | Grouped by ID column to surface duplicate records, then removed them |
| 4 | **Trimmed Text** | *First Name* and *Last Name* had extra white space. Verified this by duplicating each column and comparing text length before/after a trial trim — the mismatch confirmed the white space — then trimmed both columns |
| 5 | **Capitalized Each Word** | Applied to *First Name* and *Last Name* for consistent casing |
| 6 | **Changed Case (Lowercase)** | Applied to *Email* for consistent formatting |
| 7 | **Rounded Up** | Applied to the *Amount* column |
| 8 | **Rounded to 1 Decimal** | Applied to the *Price* column |
| 9 | **Replaced Value (Invalid Characters)** | *Order Date* contained an unexpected character causing conversion errors. Replaced the character, then replaced the resulting errors with `null` |
| 10 | **Changed Type** | Set correct data types across cleaned columns (e.g. Date, Number) once formatting issues were resolved |

## Outcome
The dataset went from having irrelevant fields, blank/duplicate rows, inconsistent text casing and spacing, and a broken date column, to a clean, consistently formatted table ready for analysis and visualisation in Power BI.

## Screenshots
<img width="817" height="392" alt="Screenshot 2026-09-15 165546" src="https://github.com/user-attachments/assets/60379ea1-c371-45d0-8e0f-654472ac9ef7" />

## Tools Used
- Power BI (Power Query Editor)

