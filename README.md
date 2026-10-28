# Simple Percentage Analysis – Superstore

**Task 28 – Simple Percentage Analysis**
Veda Technology | Data Analytics Track | Level 1, Day 28

## About
I calculated the percentage contribution of each product category to total sales, total profit and number of transactions in the Sample Superstore dataset (2014-2017, 9,994 transactions) using Excel, and showed the result in a chart.

## What "percentage contribution" means here
Percentage contribution = **a category's value ÷ the total of all categories × 100**.

The denominator is always the total of all three categories, shown in the Total row of the table:
- % of Total Sales = category sales ÷ total sales of all categories (2,297,201)
- % of Total Profit = category profit ÷ total profit of all categories (286,397)
- % of Transactions = category transactions ÷ total transactions (9,994)

## Percentage table
| Category | Total Sales | % of Sales | Total Profit | % of Profit | Transactions | % of Transactions |
|----------|-------------|-----------|--------------|-------------|--------------|-------------------|
| Furniture | 741,999 | 32.3% | 18,451 | 6.4% | 2,121 | 21.2% |
| Office Supplies | 719,047 | 31.3% | 122,491 | 42.8% | 6,026 | 60.3% |
| Technology | 836,154 | 36.4% | 145,455 | 50.8% | 1,847 | 18.5% |
| **Total** | **2,297,201** | **100.0%** | **286,397** | **100.0%** | **9,994** | **100.0%** |

## How I checked the totals
- Each percentage column adds up to exactly 100%
- The category totals add up to the grand total taken straight from the Raw Data tab (a check cell shows a difference of 0 for sales, profit and transactions)

## Chart
A clustered column chart comparing each category's share of sales, profit and transactions.

## Findings
- **Technology** contributes the most sales (36.4%) and an even bigger share of profit (50.8%)
- **Furniture** contributes 32.3% of sales but only **6.4%** of profit, so it sells a lot but keeps very little of it
- **Office Supplies** has 60.3% of all transactions, but only 31.3% of sales, which means it has many small orders

## Files
- `Percentage_Analysis.xlsx` – workbook with the Raw Data tab and the Percentage Analysis tab (formulas and chart)
- `percentage_screenshot.png` – screenshot of the table and chart
- `README.md`

## Tools used
Microsoft Excel (SUMIFS, COUNTIFS, percentage formatting, charts)

## Author
Rabia
