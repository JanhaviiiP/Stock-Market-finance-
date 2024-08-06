# Stock Market Portfolio Optimization and Anomaly Detection


**Objective**

The primary objective of this project is to demonstrate how to leverage statistical analysis and data visualization techniques to optimize stock market portfolios and detect market anomalies. By employing Python and various libraries, we aim to provide actionable insights into:

- Building portfolios that maximize returns for a given level of risk using Modern Portfolio Theory (MPT).
- Identifying and interpreting stock market anomalies that could impact investment decisions.


  
**Overview**

- This repository contains a Jupyter notebook that demonstrates the process of stock market portfolio optimization and anomaly detection.
  
- The notebook includes statistical analysis and visualizations to help understand stock price trends, expected returns, volatilities, and correlations among different stocks.

- The aim is to construct an efficient portfolio using Modern Portfolio Theory (MPT), highlighting the optimal trade-off between risk and return, and to detect anomalies that could signal significant investment opportunities or risks.



**Technologies Used**
- Python: Primary programming language for analysis.
  
- Pandas & Numpy: For data manipulation and numerical computations.
  
- Matplotlib & Seaborn: For data visualization.

- yfinance: To fetch real-time stock data.



**Key Features**


**Portfolio Optimization:**

- Analyze trends and compute expected returns, volatilities, and correlations.
  
- Use Modern Portfolio Theory to determine the efficient frontier.
  
- Identify the portfolio with the highest Sharpe ratio for optimal risk-adjusted returns.

  
**Anomaly Detection:**

- Detect and analyze unusual patterns and behaviors in stock data.

- Interpret these anomalies to understand potential opportunities or risks.


  
**Visualization**

Visualizations are included to illustrate:

- Trends in stock prices over time.
  
- Adjusted close prices across different stocks.
  
- Correlations among stocks to aid in diversification.



![image](https://github.com/user-attachments/assets/2cc762e5-7d49-43f6-8d85-e664f62d89ed)

**Observation**
-TCS: Has the highest risk rating at 1.00. It indicates that TCS is the most risky among these stocks, with the most frequent and largest anomalies detected.

-INFY : With a risk rating of around 0.06, INFY appears to be less risky compared to TCS. It indicates fewer or less significant anomalies in its trading data.

-HDFCBANK: Shows a risk rating of 0.00, indicating the least risk among the stocks listed. It suggests that HDFCBANK had the fewest and smallest anomalies in its price and volume data.

-RELIANCE: The NaN value suggests that it did not have detectable anomalies in the period analyzed.



  
**Conclusion**


This notebook provides a comprehensive guide to constructing a well-optimized stock portfolio and detecting anomalies in the market, using robust statistical methods and visualizations. It serves as an educational tool for anyone interested in advanced financial analysis.
