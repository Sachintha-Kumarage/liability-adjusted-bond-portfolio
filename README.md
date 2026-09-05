# Liability-Adjusted Bond Portfolio Construction — Sri Lankan Government Securities Market

## Overview
A quantitative case study constructing a bond portfolio that immunizes a 
liability stream using real Sri Lankan Treasury bond and bill data (CBSL 
Primary Dealer reports), applying Redington immunization theory.

## Objective
Build a Liability-Driven Investment (LDI) portfolio for a Sri Lankan insurer/
pension fund context, aligning asset duration and convexity with a 10-liability 
stream (LKR 10M–100M, maturing 2027–2037) under IRCSL/IBSL solvency norms.

## Methods
- Macaulay duration & convexity calculation across T-bills and T-bonds
- Redington immunization (PV match, duration match, convexity condition)
- Portfolio optimization via Excel Solver (cost minimization subject to 
  duration/PV constraints)
- Interest rate shock analysis (±100 bps sensitivity)

## Key Result
Achieved exact present value match (LKR 67.03M) between assets and liabilities, 
with both sides carrying an identical modified duration of 5.41 years — 
satisfying first-order immunization under IBSL solvency requirements.

## Files
- `Case_Study_3_Report.pdf` — Full case study report with methodology, results, and analysis
- `bond_portfolio_worksheet.xlsx` — Excel workbook with liability schedule, bond universe, Solver 
  optimization, and sensitivity analysis

## Tools
Excel Solver, CBSL daily PD reports (Central Bank of Sri Lanka)

## Author
Sachintha Kumarage — BSc (Hons) Finance & Insurance,Department of Mathematics, University of Colombo
