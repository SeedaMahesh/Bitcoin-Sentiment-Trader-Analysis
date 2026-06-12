# Bitcoin Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical Hyperliquid trading data.

The objective is to understand how market sentiment influences profitability, win rates, trading activity, and trader behavior.

## Datasets

### 1. Bitcoin Fear & Greed Index

* Date
* Sentiment Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

### 2. Hyperliquid Historical Trading Data

* Account
* Coin
* Execution Price
* Size USD
* Side
* Direction
* Closed PnL
* Timestamp
* Other trading attributes

## Methodology

1. Data loading and inspection
2. Data cleaning and date conversion
3. Merging sentiment and trading datasets using date
4. Exploratory Data Analysis (EDA)
5. Performance comparison across sentiment categories
6. Visualization and insight generation

## Key Findings

### Trading Activity

* Fear markets recorded the highest trading activity with 61,837 trades.
* Extreme Fear recorded the lowest activity with 21,400 trades.

### Profitability

* Extreme Greed generated the highest average profit per trade (67.89).
* Fear generated the highest total profit (3.36M).

### Win Rate

* Extreme Greed achieved the highest win rate (46.49%).
* Extreme Fear had the lowest win rate (37.06%).

### Trade Size

* Fear markets showed the largest average trade size (~7,816 USD).
* Extreme Greed markets showed smaller average trade sizes (~3,112 USD).

### Trader Concentration

* Trading profits were highly concentrated among a small number of accounts.
* The top trader generated over 2.14M in realized profits.

## Conclusion

The analysis demonstrates a clear relationship between market sentiment and trader performance. Traders achieved the highest average profitability and win rates during Extreme Greed periods, while Fear periods generated the largest overall profits due to higher trading activity. These findings suggest that market sentiment is a valuable factor when evaluating trading strategies and trader behavior.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
## Dataset Availability

The datasets used in this project were provided by Primetrade.ai as part of the hiring assignment.

Due to file size limitations and dataset ownership considerations, the raw datasets are not included in this repository.

Data Sources:
- Hyperliquid Historical Trader Data
- Bitcoin Fear & Greed Index
