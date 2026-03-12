# gold-forex-correlation-analysis
Python project analyzing correlations between Gold (XAU/USD) and major Forex pairs using historical market data and rolling correlation analysis.

Gold & Forex Correlation Analysis
Overview
This project analyzes the correlation between gold and major forex currency pairs using historical market data.
Gold often interacts with currency markets due to factors such as:
- US dollar strength
- risk sentiment
- commodity demand
- central bank policies
Understanding these relationships can help traders confirm trade signals, diversify positions, and manage risk.

This project uses Python to compute correlations and visualize how relationships between gold and currencies evolve over time.

Assets Analyzed
The following markets were included:

Gold	Gold Futures (GC=F)
EUR/USD	Euro vs US Dollar
GBP/USD	British Pound vs US Dollar
USD/JPY	US Dollar vs Japanese Yen
AUD/USD	Australian Dollar vs US Dollar
USD/CAD	US Dollar vs Canadian Dollar
USD/CHF	US Dollar vs Swiss Franc
NZD/USD	New Zealand Dollar vs US Dollar

Methodology

The analysis follows these steps:
- Retrieve historical price data using Yahoo Finance API
- Calculate daily percentage returns
- Compute Pearson correlation coefficients
- Visualize correlations using a heatmap
- Analyze 30-day rolling correlations between gold and selected currency pairs

Correlation Matrix
This heatmap shows the overall correlation between gold and the selected forex pairs: corr_heatmap.png

Rolling Correlation Analysis
Since correlations change over time, the project calculates a 30-day rolling correlation between gold and key currency pairs:
- EUR/USD
- USD/CHF
- AUD/USD
- USD/JPY

This helps traders observe dynamic relationships instead of static ones.

Positive values indicate assets that tend to move with gold, while negative values suggest inverse relationships.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

Project Motivation

This project was built to explore how gold interacts with major currency pairs. Such relationships can be useful for:

- confirming trading setups
- identifying macroeconomic relationships
- improving portfolio diversification
- risk management

