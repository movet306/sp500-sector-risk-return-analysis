## 1. Project Overview

Comprehensive, real-world analysis of S&P 500 sector risk, return, correlation, and crisis resilience (2021–2024).  
Utilizes robust Python workflows, web scraping, dynamic sector mapping, and advanced analytics to support actionable portfolio strategies.

---

## 2. Motivation & Self-Initiated Approach

This project was fully self-initiated, designed and executed out of personal curiosity to deeply explore sectoral risk, performance, and resilience within the S&P 500.  
Every step—from data sourcing and web scraping to advanced time series analysis—was conceptualized, built, and interpreted independently.

---

## 3. Data Sources & Methodology

- **S&P 500 Constituents:** Dynamically scraped from Wikipedia for up-to-date symbol lists.
- **Sector Mapping:** Downloaded and joined from external CSVs (e.g., datahub.io), matched with price data.
- **Historical Price Data:** Pulled from Yahoo Finance via yfinance API.
- **Methodology:**  
  - Data cleaning and outlier management  
  - Daily and annualized return & volatility calculations  
  - Risk-adjusted metrics (Sharpe ratio)  
  - Mapping, grouping, and pivoting for sector/year aggregation  
  - Multi-layered visualizations (scatter plots, heatmaps, line charts, bar charts)  
  - Benchmarking (sector alpha vs index)  
  - Crisis and recovery analysis over multiple years

---

## 4. Technical Highlights

- **Web Scraping:** Automated collection of both company symbols and sector mapping for full data freshness.
- **Data Cleaning:** Rigorous filtering to remove incomplete or low-quality records, ensuring robust results.
- **Dynamic Mapping:** Merging company-level price data with up-to-date sector information from independent sources.
- **Grouping & Aggregation:** Advanced use of groupby, melt, and pivot for flexible sector, year, and crisis period analysis.
- **Time Series Analysis:** Year extraction and longitudinal breakdown to capture sectoral performance during crisis and recovery.
- **Visualization:**  
    - Risk-return scatter plots with top/bottom performers highlighted  
    - Sector-level bar and line charts for return, volatility, Sharpe  
    - Correlation heatmaps to identify diversification opportunities  
    - Trend analysis of sector resilience and rotation
- **Alpha Benchmarking:** Sector returns versus index returns (alpha) for performance attribution.

---

## 5. Main Results & Analytical Insights

- **Energy & Information Technology** delivered the strongest positive alpha—consistently outperforming the S&P 500 index, especially in post-crisis periods.
- **2022 crisis:** Most sectors suffered negative returns, but **Energy** was a notable outlier with significant gains driven by macro shocks.
- **Defensive sectors** (Health Care, Consumer Staples, Utilities) were most resilient during downturns, showing lower volatility and less negative (or even slightly positive) returns.
- **Aggressive/cyclical sectors** (Communication Services, Real Estate, Consumer Discretionary) underperformed during crises, but rebounded rapidly during recovery years.
- **Risk/return analysis:** Only a small handful of stocks achieved truly high Sharpe ratios (high return per unit risk); most high-return stocks also carried high risk.
- **Sector correlation matrix:** Revealed strong clustering (e.g., IT & Communication Services), and identified low-correlation sectors (e.g., Energy & Utilities) for portfolio diversification.
- **Sector-year analysis:** Enabled clear identification of “crisis-resilient” versus “growth-boosted” sectors in each year.
- **Alpha evaluation:** Provided clear, quantitative evidence of which sectors consistently added value above a passive index investment.

---

## 6. Investment Takeaways

- **Sector allocation drives risk and return:** Portfolio construction should combine both aggressive and defensive sectors—defensive sectors offer downside protection, while aggressive sectors fuel long-term growth.
- **Crisis periods demand resilience:** Overweighting defensive sectors during uncertainty (e.g., 2022) helps reduce losses.
- **Sector rotation is key:** Adjusting exposure based on macro trends (post-crisis recovery, new bull markets) enhances performance.
- **Don’t chase returns without risk context:** Top performers often come with high volatility; prioritize risk-adjusted metrics (Sharpe ratio) over raw returns.
- **Diversification pays:** Sector correlation analysis supports smarter allocation and more robust, shock-resistant portfolios.

---

## 7. Limitations & Future Work

- **Data limitations:** Survivorship bias may be present; index composition and sector definitions can change over time.
- **Backward-looking:** All analysis is historical; future market conditions may differ.
- **Potential extensions:** Integration of fundamentals, machine learning models, or macroeconomic variables for predictive analytics.

---

## 8. Author & Contact

**Project Owner & Analyst:**  
**Mert Ovet**  
[LinkedIn](https://www.linkedin.com/in/mertovet)  
For questions or collaboration, feel free to reach out.
## Project Notebook

All code, analysis, and visualizations are documented in the main Jupyter notebook:  
[**S&P 500 Multi-Year Performance & Risk Analysis (.ipynb)**](https://github.com/movet306/sp500-sector-risk-return-analysis/blob/main/%23%20S%26P%20500%20Stocks%20MultiYear%20Performance%20%26%20Risk%20Analysis%20(3).ipynb)

> Open in GitHub or download to explore the full analysis workflow.


