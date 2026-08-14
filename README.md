# Cryptocurrency Performance & Risk Analysis — 2025

## 📌 Project Overview

Cryptocurrency markets can provide high returns, but these returns often come with significant risk and price volatility. This project analyzes the historical performance of six cryptocurrencies during 2025 to determine which demonstrated the strongest performance relative to risk.

The analysis focuses on both **investment performance** and **risk**, rather than evaluating cryptocurrencies based only on their price appreciation.

---

## 🎯 Business Question

> **Which cryptocurrency demonstrated the strongest performance relative to risk during 2025?**

### Supporting Questions

* Which cryptocurrency generated the highest total return?
* Which cryptocurrency experienced the lowest volatility?
* Which cryptocurrency experienced the largest maximum drawdown?
* Which cryptocurrency achieved the strongest risk-adjusted performance?
* Did higher returns come with higher levels of risk?

---

## Hypothesis

I expect Bitcoin and Ethereum to demonstrate strong and relatively stable performance compared with the other cryptocurrencies because of their established positions in the cryptocurrency market.
However, smaller cryptocurrencies may generate higher returns while also experiencing greater volatility.

---

## Cryptocurrencies Analyzed

The analysis covers six cryptocurrencies:

| Cryptocurrency | Ticker  |
| -------------- | ------- |
| Bitcoin        | BTC-USD |
| Ethereum       | ETH-USD |
| Solana         | SOL-USD |
| XRP            | XRP-USD |
| Cardano        | ADA-USD |
| BNB            | BNB-USD |

---

## 📊 Dataset

The dataset contains daily historical cryptocurrency market data for the full 2025 calendar year.

**Period:** January 1, 2025 – December 31, 2025

**Records:** 2,190

**Cryptocurrencies:** 6

**Observations per cryptocurrency:** 365

### Data Elements

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Trading Volume
* Ticker
* Cryptocurrency Name

---

## 🛠️ Tools Used

* **Excel** — Data preparation, calculations, and summary analysis
* **Power Query** — Data cleaning and transformation
* **Power BI** — Data visualization and dashboard development

---

## Key Metrics

### Total Return

Measures the percentage change between the beginning and ending closing price during 2025.

> **Total Return = (Ending Close − Beginning Close) / Beginning Close**

### Average Daily Return

Measures the average daily percentage change in closing price.

### Volatility

Measures the variability of daily returns. Higher volatility indicates greater price fluctuations and therefore greater risk.

### Sharpe Ratio

The Sharpe Ratio was used to evaluate risk-adjusted performance by comparing the average daily return of each cryptocurrency with its daily volatility.

For this analysis, the Sharpe Ratio was calculated as:

> **Sharpe Ratio = (Average Daily Return / Daily Volatility) × √365**

The calculation does not subtract a risk-free rate. The ratio was annualized using 365 days because cryptocurrency markets operate continuously throughout the year, including weekends.

A higher Sharpe Ratio indicates stronger historical risk-adjusted performance, meaning the cryptocurrency generated relatively higher returns for the level of volatility experienced.

### Maximum Drawdown

Measures the largest decline from a previous peak during the analysis period.

---

## Analysis Results

### Overall Performance

BNB demonstrated the strongest performance based on total return.

| Cryptocurrency | Total Return | Volatility | Sharpe Ratio | Maximum Drawdown |
| -------------- | -----------: | ---------: | -----------: | ---------------: |
| **BNB**        |   **21.91%** |      2.73% |    **0.641** |          -36.85% |
| Bitcoin        |       -7.31% |  **2.20%** |        0.028 |          -32.15% |
| Ethereum       |      -11.35% |      3.94% |        0.211 |          -60.08% |
| XRP            |      -20.83% |      4.36% |        0.124 |          -49.16% |
| Solana         |      -35.70% |      4.52% |       -0.085 |          -59.71% |
| Cardano        |      -63.66% |      5.86% |       -0.411 |          -70.63% |

---

## 💡 Key Findings

### 1. BNB demonstrated the strongest overall performance

BNB generated a **21.91% total return**, making it the only cryptocurrency in the analysis to finish 2025 above its January 1 closing price.

It also achieved the highest Sharpe Ratio at **0.641**, indicating the strongest risk-adjusted performance among the six cryptocurrencies analyzed.

### 2. Bitcoin was the most stable

Bitcoin had the lowest volatility at **2.20%**, indicating the least variation in daily returns among the six cryptocurrencies.

However, Bitcoin still produced a **-7.31% total return** during 2025.

This means that Bitcoin demonstrated relatively stable performance but did not generate a positive annual return during the analysis period.

### 3. Higher volatility did not lead to higher returns

The cryptocurrencies with higher volatility did not consistently generate higher returns. Cardano had the highest volatility at 5.86% but also recorded the lowest total return at -63.66%. This suggests that higher risk did not translate into higher performance during the 2025 analysis period.

### 4. Cardano demonstrated the weakest performance

Cardano recorded:

* **-63.66% Total Return**
* **5.86% Volatility**
* **-0.411 Sharpe Ratio**
* **-70.63% Maximum Drawdown**

It therefore demonstrated the weakest combination of return and risk among the cryptocurrencies analyzed.

---

## 🧪 Hypothesis Evaluation

The hypothesis was **partially supported**.

The expectation that Bitcoin would demonstrate relatively stable performance was supported because Bitcoin had the lowest volatility at **2.20%**.

However, the expectation that Bitcoin and Ethereum would demonstrate strong performance was not supported by the 2025 results. Both cryptocurrencies ended the year with negative total returns.

The hypothesis that smaller cryptocurrencies could experience higher volatility was also supported. Solana, XRP, and Cardano had higher volatility than Bitcoin.

However, higher volatility did not result in higher returns during the analysis period.

---

## Power BI Dashboard

The Power BI dashboard presents the analysis through:

* Total Return comparison
* Cryptocurrency price trends
* Risk and volatility comparison
* Risk vs. Return analysis
* Maximum Drawdown comparison
* Cryptocurrency performance summary


---

## 📁 Project Structure
```text
cryptocurrency-performance-risk-2025/
│
├── README.md
│
├── data/
│   └── Raw_Crypto_historical_data.csv
│
├── excel/
│   └── Cleaned_Crypto_Risk_Return_Analysis_2025.xlsx
│
├── powerbi/
│   └── Crypto_Risk_Return_Dashboard.pbix
│
└── images/
    ├── dashboard_overview.png
```

---

## Limitations

This analysis is based on historical cryptocurrency data from 2025. Historical performance does not guarantee future results.

The analysis also does not account for:

* Transaction fees
* Taxes
* Liquidity differences
* Individual investor risk tolerance
* Macroeconomic conditions
* Cryptocurrency-specific news or events
* Future market conditions

Therefore, the results should be interpreted as a **historical data analysis rather than financial advice or a recommendation to buy or sell any cryptocurrency.**

---

## Conclusion

Based on the historical data analyzed, **BNB demonstrated the strongest performance relative to risk during 2025**.

BNB generated the highest total return at **21.91%** and the highest Sharpe Ratio at **0.641**, while maintaining relatively low volatility of **2.73%**.

Bitcoin demonstrated the greatest stability, with the lowest volatility at **2.20%**, but its total return was negative at **-7.31%**.

Overall, the analysis demonstrates why evaluating an investment based only on return can be misleading. Considering **return, volatility, risk-adjusted performance, and maximum drawdown together** provides a more complete view of historical investment performance.
