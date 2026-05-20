# Market Analysis

## Overview

This project analyses market performance, volatility, and correlations using Python and historical financial market data.

The analysis investigates the behaviour of multiple equities across different sectors in order to compare performance, investment risk, and diversification over time. My project focuses on understanding how major market events, type of sector, and other economic conditions influence stock behaviour.

Historical market data was collected using the `yfinance` in Python library, while analysis and visualisation were completed using pandas, matplotlib, seaborn, and numpy.

---

## Objectives

The main objectives of this project were to:

- Analyse long-term market performance across multiple sectors
- Compare cumulative returns between diversified and sector specific assets
- Evaluate volatility and changing market risk over time
- Investigate correlation and diversification benefits

---

## Assets Analysed

The following assets were selected to provide exposure across different sectors of the US market:

| Ticker | Company / ETF | Sector |
|---|---|---|
| AAPL | Apple | Technology |
| MSFT | Microsoft | Technology |
| JPM | JPMorgan Chase | Financials |
| XOM | Exxon Mobil | Energy |
| SPY | SPDR S&P 500 ETF | Market Index ETF |


---

## Technologies & Libraries Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- Jupyter Notebook
- VS Code

---

## Analysis Performed

### 1. Historical Price Collection

Five years of historical market data was downloaded using the `yfinance`. Adjusted closing prices were used to ensure there was consistency across the dataset.

### 2. Daily Return Calculations

Daily percentage returns were calculatedto analyse price movements and prepare the dataset for volatility and correlation analysis.

### 3. Performance Analysis

Stock prices were normalised to represent the growth of an $100 investment in each stock. This allowed direct comparison between each with very different starting prices.

### 4. Volatility Analysis

30-day rolling annualised volatility was calculated to evaluate the changing levels of market risk over time.

### 5. Correlation Analysis

A correlation heatmap was created to evaluate how strongly assets moved together and to assess potential diversification benefits.

---

## Key Findings

### Technology Sector Outperformance

AAPL and MSFT had the strongest cumulative returns over the period, reflecting the strength within the technology sector. This reflected growth within the technology sector, sustained investor confidence in major technology companies, and growing demand for digital and cloud based services.

Technology also demonstrated rapid recovery following the periods of market disruption, mainly after the COVID-19 market shock in early 2020.

---

### Impact of COVID on Market Volatility

One of the most significant observations within this analysis was the sharp increase in volatility during early 2020, caused by the COVID-19 pandemic and global market uncertainty.

All analysed assets experienced increases in rolling volatility during this period, meaning:
- increased investor uncertainty
- economic shutdown concerns
- supply chain disruptions
- recession fears

Technology focused equities recovered more quickly following the initial market disruption, which could be due increased reliance on remote working, digital infrastructure, cloud computing, and online consumer activity.

Financial and energy companies were more influenced by changing economic conditions during the recovery period, causing their stock prices to fluctuate more alongside the broader economy.

---

### Sector-Specific Behaviour

JPM and XOM exhibited behaviour more heavily influenced by economic and sector specific conditions.

JPM's performance was closely linked to:
- interest rate expectations
- banking sector conditions
- broader economic growth expectations

XOM displayed stronger sensitivity to:
- price movements
- oil market conditions
- geopolitical developments
- global energy demand

This resulted in performance and volatility patterns that differed from those in technology equity. 

---

## Visualisations Included

The project includes the following visualisations:

- Stock Performance
- 30-Day Volatility
- Correlation Heatmap

---

## Skills Demonstrated

This project demonstrates experience in:

- Financial data analysis
- Quantitative analysis
- Portfolio risk analysis
- Equity market interpretation
- Data visualisation
- Python programming
- Statistical analysis
- Risk-return evaluation
- Diversification analysis
- Analytical problem solving

---

## Project Structure

equity-market-analysis/

├── data/
│   ├── stock_prices.csv
│   └── daily_returns.csv

├── notebooks/
│   └── portfolio_analysis.ipynb

├── visuals/
│   ├── normalised_performance.png
│   ├── rolling_volatility.png
│   └── correlation_heatmap.png

└── README.md

---

## Author

Arjun Dhillon

LinkedIn: https://www.linkedin.com/in/-arjun-dhillon
GitHub: https://github.com/arjundhillon03
