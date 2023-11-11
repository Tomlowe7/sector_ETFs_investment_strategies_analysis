# Data Science for Finance: Sector ETFs Investment Strategies Analysis

## Project Overview
In this project, we explore utilizing a $1,000,000 budget to maximize portfolio performance through various investment strategies in Sector ETFs. We implement and test these strategies over three distinct date ranges, comparing and ranking them based on performance.

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
