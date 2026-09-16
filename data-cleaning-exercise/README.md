# Power BI Data Cleaning Exercise

## Overview
A small exercise cleaning a raw dataset in Power Query to make it analysis-ready — resolving irrelevant columns, blank rows, duplicates, inconsistent text formatting, and data type/error issues.

## Steps Applied

| # | Step | What I Did |
|---|------|------------|
| 1 | **Removed Column** | Dropped a log-detail column not needed for analysis |
| 2 | **Removed Blank Rows** | Removed rows with no data |
| 3 | **Removed Duplicates** | Grouped by ID column to surface duplicate records, then removed them |
| 4 | **Trimmed Text** | - *First Name* and *Last Name* had extra white space<br>- Checked this by copying each column and comparing text length before and after trimming<br>- Trimmed both columns |
| 5 | **Capitalized Each Word** | Applied to *First Name* and *Last Name* |
| 6 | **Changed Case (Lowercase)** | Applied to *Email* |
| 7 | **Rounded Up** | Applied to the *Amount* column |
| 8 | **Rounded to 1 Decimal** | Applied to the *Price* column |
| 9 | **Replaced Value (Invalid Characters)** | - *Order Date* had a weird character causing errors<br>- Replaced the character first<br>- Replaced the resulting errors with `null` |
| 10 | **Changed Type** | Set correct data types once the above was fixed |
| 11 | **Handled Missing Values** | - Set a standard for blanks<br>- *Product Name* and *Email* replaced with "NA"<br>- *Price* replaced with 0 |
| 12 | **Split Column** | *Product Name* split into Product Name and Category using a delimiter |
| 13 | **Extracted from Column** | - *Customer ID*: made a copy of the column to keep the original intact<br>- Extracted the last 2 characters from the copy to get the country code |
| 14 | **Merged Columns** | *First Name* and *Last Name* merged into one column |

## Screenshots

<img width="925" height="188" alt="Screenshot 2026-09-16 121801" src="https://github.com/user-attachments/assets/57f06475-2b5a-4e22-bea8-0d34f713e941" />
<img width="365" height="176" alt="Screenshot 2026-09-16 121819" src="https://github.com/user-attachments/assets/1da02191-4f08-43f2-abcb-74389e5b5fc4" />

## Tools Used
- Power BI (Power Query Editor)

