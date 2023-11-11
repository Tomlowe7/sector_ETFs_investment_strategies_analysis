# Data Science for Finance: Sector ETFs Investment Strategies Analysis

![image](https://github.com/Tomlowe7/sector_ETFs_investment_strategies_analysis/assets/126796950/f72e65a5-0a6b-4798-8b64-87f24a676e84)


## Project Overview
In this project, we explore utilizing a $1,000,000 budget to maximize portfolio performance through various investment strategies in Sector ETFs. We implement and test these strategies over three distinct date ranges, comparing and ranking them based on performance.

Final Project in Financial Data Science
The goal of the project is to create 5 different trading strategies for using the Sector ETFs to get good portfolio performance.

XLK - Technology <br/>
XLE - Energy <br/>
XLF - Financials <br/>
XLV - Health Care <br/>
XLRE -  Real Estate <br/>
XLB - Materials <br/>
XLY - Consumer Discretionary <br/>
XLP - Consumer Staples <br/>
XLU - Utilities <br/>
XLI - Industrials <br/>
IYZ - Telecommunications

You can use technical analysis (Bollinger bands, MACD, RSI, Moving Averages) or any kind of fundamental or macro analysis (based on the interest rate, 10 year yield, unemployment rate, Inflation rate, etc).
You can rebalance your portfolio every day, every week or every quarter. Assume you have 1M$ as initial available cash. You do NOT have to utilize all the cash at each point. Your goal is to rebalance the allocation between the various sector ETFs and the available cash.
You need to describe your strategies, implement them and test them on 3 date ranges:
1.	1.1.2010-now
2.	1.1.2019-now
3.	1.1.2021-now
Rank the 5 strategies for each time range based on their performance.


### Key Objectives:
- Implement five different investment strategies for Sector ETFs.
- Analyze and compare the strategies over three separate date ranges.
- Determine the most effective strategy based on the total value and performance of the portfolio at the end of each period.

## Strategies Used:
1. **Exponential Moving Average (EMA)**
2. **Simple Moving Average (SMA)**
3. **Bollinger Bands**
4. **Relative Strength Index (RSI)**
5. **Volume Changes**

## Methodology
- We began by importing and installing the Pandas Technical Analysis package to obtain the necessary technical indicators.
- Each strategy involved logging transactions to track the mean change of securities bought and sold.
- We adjusted the portfolio after each transaction, recalculating the normalized profit/loss.

## Results Summary
Strategy Ratings
1st Date Range: 1.1.2010 – 16.2.2022
1. EMA +39,926%
2. SMA +1,692%
3. Bollinger Bands +881%
4. RSI +440%
5. Volume Changes +34%

2nd Date Range: 1.1.2019 – 16.2.2022
1. SMA +276%
2. Bollinger Bands +243%
3. Volume Changes -11%
4. RSI -40%
5. EMA -7318%

3rd Date Range: 1.1.2021 – 16.2.2022
1. EMA +67%
2. Volume Changes +48%
3. Bollinger Bands +44%
4. SMA +26%
5. RSI +16%

## Results and Performance Analysis
- **Date Range 1 (1.1.2010 – 16.2.2022):** EMA strategy outperformed others with a +39926% increase.
- **Date Range 2 (1.1.2019 – 16.2.2022):** SMA strategy was most effective, yielding a +276% rise.
- **Date Range 3 (1.1.2021 – 16.2.2022):** EMA strategy again showed the best performance with a +67% increase.

## Conclusions
- EMA is highly effective for long-term investment but showed mixed results in mid-range periods.
- SMA provided consistent performance across various timeframes.
- RSI, Bollinger Bands, and Volume Changes strategies had varying degrees of success.

## Acknowledgements
Acknowledgments for any third-party resources or individuals who contributed to the project.
