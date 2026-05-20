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

AAPL and MSFT generated the strongest cumulative returns over the analysed period, significantly outperforming broader market exposure through SPY. This reflected sustained growth within the technology sector, strong investor confidence in large-cap technology firms, and increased demand for digital services and cloud infrastructure.

Technology equities also demonstrated rapid recovery following periods of market disruption, particularly after the COVID-19 market shock in early 2020.

---

### Impact of COVID on Market Volatility

One of the most significant observations within the analysis was the sharp increase in volatility during early 2020, corresponding with the onset of the COVID-19 pandemic and global financial market uncertainty.

All analysed assets experienced substantial increases in rolling volatility during this period, reflecting:
- heightened investor uncertainty
- economic shutdown concerns
- supply chain disruption
- recession fears
- rapid shifts in monetary and fiscal policy expectations

Technology-focused equities recovered more quickly following the initial market disruption, supported by increased reliance on remote working, digital infrastructure, cloud computing, and online consumer activity.

Financial and energy equities displayed more cyclical behaviour and experienced greater sensitivity to macroeconomic conditions during the recovery period.

---

### Diversification Effects Through SPY

SPY displayed more stable long-term behaviour relative to individual equities due to its diversified exposure across the broader US equity market.

Although SPY produced lower cumulative returns than the strongest-performing technology equities, its lower volatility profile highlighted the importance of diversification in reducing portfolio risk.

This demonstrated one of the core principles of portfolio management:
higher diversification generally reduces idiosyncratic company-specific risk.

---

### Sector-Specific Behaviour

JPM and XOM exhibited behaviour more heavily influenced by macroeconomic and sector-specific conditions.

JPM's performance was closely linked to:
- interest rate expectations
- banking sector conditions
- broader economic growth expectations

XOM displayed stronger sensitivity to:
- commodity price movements
- oil market conditions
- geopolitical developments
- global energy demand

This created distinct performance and volatility characteristics compared to technology equities.

---

### Correlation & Diversification Analysis

Correlation analysis showed that AAPL and MSFT maintained relatively high correlations with SPY, reflecting the significant influence of large-cap technology companies on broader market performance.

XOM demonstrated lower correlations with technology-focused equities, suggesting potential diversification benefits from combining assets across multiple sectors.

Lower correlations between assets are particularly important in portfolio construction because they can help reduce overall portfolio volatility during periods of market stress.

---

## Visualisations Included

The project includes the following visualisations:

- Normalised Stock Performance
- 30-Day Rolling Volatility
- Correlation Heatmap

These visualisations were saved as PNG outputs and included within the project structure.

---

## Skills Demonstrated

This project demonstrates practical experience in:

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
