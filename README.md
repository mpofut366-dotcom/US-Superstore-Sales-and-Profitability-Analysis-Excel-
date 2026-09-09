# US SUPERSTORE SALES AND PROFITABILITY ANALYSIS / EXCEL 

# OVERVIEW 
This project uses the US Superstore dataset to analyse sales performance and profitability using Microsoft Excel. 

# AIM
To analyse sales and profit performance across the business, identify areas where profit is being lost and highlight areas for improvement. 

# Tools 
Excel |Powery Query |Power Pivot |DAX 

## METHODOLOGY 
- Cleaned and transformed the raw data using Power Query
- Built a Star Schema using Power Pivot, creating relationships between fact (orders) and dimension tables (customers, products, location) 
- Created DAX measures for revenue, profit, and profit margin
- Added calculated columns (COGS, Unit Price, Revenue lost to Discount, Gross sales and Gross Profit)
- Made Use of PivotTables to analyse sales and profitability across products and segments and identify areas where discounts  affected profitability.
- Built an interactive Excel Dashboard to showcase findings.

## KEY FINDINGS  
- While the business generated $ 2.30 million in revenue, profit was low at only $286.4K, resulting in a 12.47% profit margin across 9994 orders. 
- California and New York were the most profitable states, with Consumers being the most profitable segment.
- High sales volume did not always drive high profitability; heavily discounted items created significant gaps between gross potential profit and actual profit. E.g., tables stood out as a key example: 246 of 319 orders received a discount, at an average discount of 26%,  resulting in a net loss of $17,725.48.

### DASHBOARD PREVIEW 
<img width="1000" height="700" alt="US Superstore Dashboard (SS)" src="https://github.com/user-attachments/assets/9832076d-9819-4267-b944-22b7108d55da" />

### DATA MODEL 
<img width="1000" height="946" alt="Data Model US Superstore" src="https://github.com/user-attachments/assets/149264ae-19a9-4226-80be-be2f8d926efa" />
