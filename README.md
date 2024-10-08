# Portfolio Management - Monte Carlo Simulation and Mean-Variance Approach
Comparison of different portfolio allocation strategies and estimation of Value-at-Risk (VaR) and Conditional Value-at-Risk (CVaR) using Parametric, Historical Simulation and Monte Carlo Simulation methods.

## Requirement
`pandas` </br>
`numpy` </br>
`scipy` </br>
`datetime` </br>
`matplotlib` </br>
`seaborn` </br>
`yfinance` </br>
`pypfopt` </br>

## Structure
1. Importing libraries
2. Loading the data and Pre-processing
3. Descriptive analysis of simple and cumulative returns
   - Daily Returns
   - Daily Cummulative Returns
   - Risk-Return profile
   - Correlation and Covariance matrices
4. Portfolio Optimization
5. Analysis of optimized Portfolios' Performance
   - Rolling Standard Deviation
   - Rolling Beta
   - Exponentially Weighted Average
   - Rolling Sharpe Ratio
6. Tail Risk Analysis
   - Historical Drawdown
   - VaR and CVaR
     - Historical (Non-Parametric) Method
     - Variance-Covariance (Parametric) Method
     - Monte Carlo Simulation     

## Data
Investiment universe consists of the 10 largest companies listed on the London Stock Exchange (LSE) acording to its market value: 1. Shell (SHEL.L), 2. AstraZeneca (AZN.L), 3. HSBC Holdings (HSBA.L), 4. Unilever Group (ULVR.L), 5. BP (BP.L), 6. Diageo (DGE.L), 7. Rio Tinto Group (RIO.L), 8. Glencore (GLEN.L), 9. British American Tobacoo (BATS.L) and 10. GlaxoSmithKline (GSK.L). </br>

Close prices from January 31, 2012 to January 31, 2023 were pulled with Yahoo Finance API (yfinance library).

## Portfolio Strategies
1. Market Cap-Weighted (MCAP)
2. Naïve Equally-Weighted (EW)
3. Global Minimum Variance (GMV)
4. Tangency - Maximum Sharpe Ratio (MSR)
