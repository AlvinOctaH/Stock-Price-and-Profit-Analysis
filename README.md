# Stock Price and Profit Analysis Tesla VS GameStop
----------------
## Table of contents

- [Introduction](#Introduction)
- [Data Source](#Data-source)
- [Visualizations](#Visualizations)
  - [Tesla](#1-tesla)
  - [Gamestop](#2-gamestop)

----------
## Introduction
<p align="justify">
This repository will discuss financial data analysis and stock price movements for two companies, Tesla and GameStop, with a primary focus on understanding the dynamics of short selling and investor behavior. Understanding the factors that influence stock prices, such as company profits and growth prospects, is crucial in determining the appropriate investment strategy.
</p>
<p align="justify">
The cases of Tesla and GameStop offer an interesting perspective on how market expectations and investor activity can influence stock prices, regardless of the company's fundamentals. In the case of Tesla, many investors engaged in short selling with the expectation that the stock price would fall. However, as Tesla's profitability increased, the stock price surged, resulting in losses for investors who had shorted the stock.
On the other hand, the GameStop case demonstrates a unique phenomenon where massive demand from individual investors on the Reddit forum WallStreetBets drove a surge in GameStop's stock price, despite the company experiencing losses. This resulted in significant losses for hedge funds that had shorted GameStop's stock.
</p>
<p align="justify">
Through an analysis of Tesla's and GameStop's profit data and stock prices, this repository will provide insights into how fundamental factors and market sentiment can influence stock price movements. Additionally, the repository will present data visualizations in the form of an interactive dashboard to facilitate understanding and comparison between the two cases.
</p>

## Data source
<p align="justify">
The financial data analyzed in this repository spans the maximum available period for Tesla and GameStop stocks, as obtained from the yfinance library. For Tesla, the data covers its historical stock prices, dividends, and other relevant financial information from the company's initial public offering (IPO) in June 2010 up until the most recent trading day. Similarly, for GameStop, the data encompasses the entire period since the company's stock became publicly traded, dating back to its IPO in February 2002, and extends to the latest available data point. By leveraging the extensive historical data provided by yfinance, this repository aims to conduct a comprehensive analysis, capturing the full scope of stock price movements and their relationship with company profits and other factors throughout the lifespan of these two companies in the public markets.
</p>

**Source :** [yfinance](https://pypi.org/project/yfinance/)

## Visualizations
<p align="justify">
The visualizations showcasing the historical trajectories of stock prices and revenue for Tesla and GameStop are presented in the following illustrations:
</p>

### 1). Tesla

<p align="center">
    <img width="1000" src="https://github.com/AlvinOctaH/Stock-Price-and-Profit-Analysis/blob/main/assets/result_tesla.png" alt="TESLA">
</p>
<p align="justify">
The top chart illustrates Tesla's historical share price. Initially, the share price remained relatively low but experienced a significant upward trend starting around 2019. This rapid increase in share price coincides with the company's growing profitability and positive market sentiment, as mentioned in the background information.
</p>
<p align="justify">
The bottom chart depicts Tesla's historical revenue. The revenue data shows a steady upward trajectory over time, with a more pronounced increase in recent years. This trend reflects Tesla's expanding operations and growing sales of its electric vehicles.
</p>

### 2). Gamestop

<p align="center">
    <img width="1000" src="https://github.com/AlvinOctaH/Stock-Price-and-Profit-Analysis/blob/main/assets/result_gamestop.png" alt="TESLA">
</p>
<p align="justify">
The top chart displays the historical share price of GameStop stock. It is evident that the share price remained relatively low and stable for an extended period until a sudden and massive spike occurred towards the end of the data range. This spike likely corresponds to the Reddit-driven trading frenzy mentioned in the background information.
</p>
<p align="justify">
The bottom chart shows GameStop's historical revenue over the years. The revenue exhibits a cyclical pattern, with peaks occurring around the holiday season (typically the fourth quarter of each year) and dips during other periods. The overall revenue trend appears to be declining gradually over time, which aligns with the company's reported financial struggles.
</p>
