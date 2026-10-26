# Major Banks Stock Analysis & Portfolio Optimisation

## Overview
This project analyses the stock performance of major global banks from 2018 to 2023, 
covering three Singapore banks (DBS, OCBC, UOB) and four global banks (Bank of America, 
HSBC, Goldman Sachs, JP Morgan). Using daily closing prices sourced from yfinance, the 
analysis examines how these stocks performed relative to one another and how they responded 
to key macroeconomic events, specifically the COVID 19 pandemic and the 2022 Federal 
Reserve interest rate hike cycle. The analysis further applies Monte Carlo simulation and 
mathematical optimisation to identify the optimal portfolio allocation across these seven banks.

## Key Findings
- Goldman Sachs and DBS delivered the strongest cumulative returns over the period
- Singapore banks (DBS, OCBC, UOB) consistently showed lower volatility than US banks across all market periods
- COVID-19 (2020-2021) caused the largest volatility spike across all banks, with US banks hit hardest
- Mathematical optimisation identified OCBC (67.6%), GS (27.1%) and UOB (5.3%) as the optimal portfolio, achieving a Sharpe Ratio of 0.73

## Tools & Libraries
- Python, Pandas, NumPy, Matplotlib
- yfinance (data extraction)
- scipy (portfolio optimisation)

## Project Structure
- **Part 1 — Performance Analysis:** Cumulative returns across all 7 banks
- **Part 2 — Volatility by Market Period:** Volatility comparison 
  across all 7 banks & how volatility changed across pre-COVID, COVID and post-COVID periods
- **Part 3 — Correlation Analysis:** How banks move relative to each other
- **Part 4 — Portfolio Optimisation:** Monte Carlo simulation and mathematical optimisation to find the optimal portfolio allocation

## Limitations
- Based on historical data (2018–2023), past performance does not guarantee future results
- Assumes normally distributed returns, which underestimates tail risk
- Does not account for transaction costs or liquidity constraints
- Sharpe Ratio penalises upside and downside volatility equally
