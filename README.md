# Reliance Industries — 3-Statement Financial Model

## Overview
A fully integrated 3-statement financial model for Reliance Industries Ltd. 
(FY2025 actuals + 5-year projections through FY2030), with the Income Statement, 
Balance Sheet, and Cash Flow Statement dynamically linked.

## Model Architecture
The three statements are fully interconnected:
- Net Income flows from the Income Statement into both the Cash Flow Statement 
  and Retained Earnings on the Balance Sheet
- The Cash Flow Statement calculates Ending Cash
- Ending Cash links back to the Balance Sheet, which balances to zero every year

## Key Features
- **Income Statement:** Revenue-driven projections with EBITDA margin expansion 
  (17% to 19.5%) reflecting mix shift toward Jio & Retail
- **Balance Sheet:** PP&E roll-forward (prior + capex - depreciation), 
  revenue-driven working capital, retained earnings linkage
- **Cash Flow:** Operating, Investing, Financing sections capturing all 
  balance sheet movements
- **Self-balancing:** Check row confirms Assets = Liabilities + Equity for all 5 years

## Key Assumptions
- Revenue growth: 8% tapering to 7% (blended across O2C, Jio, Retail)
- EBITDA margin: 18% to 19.5% (mix shift to high-margin businesses)
- Capex: 12% of revenue tapering to 10%
- Tax rate: 23%

## Verified Data
FY2025 actuals sourced from Reliance's audited consolidated annual report:
Revenue ₹10,71,174 Cr | Net Profit ₹81,309 Cr | Total Assets ₹19,50,121 Cr

## Tools
Microsoft Excel — fully linked 3-statement model with cross-sheet references, 
PP&E schedule, and integrated cash flow
