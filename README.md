# Stock-Market

STOCK MARKET ANALYSIS USING PYTHON AND MACHINE LEARNING

PROJECT OVERVIEW

This project focuses on analyzing and understanding the historical stock performance of four major technology companies — Apple (AAPL), Microsoft (MSFT), Netflix (NFLX), and Google (GOOG). The analysis is conducted using Python and various data science techniques, with the goal of extracting insights, identifying patterns, and exploring correlations within the stock data.

By leveraging tools such as Pandas, Seaborn, Matplotlib, and Scikit-learn, this project demonstrates an end-to-end workflow that includes data cleaning, visualization, statistical exploration, and initial modeling.


---

OBJECTIVES

Analyze and compare historical stock trends for AAPL, MSFT, NFLX, and GOOG.

Understand price distribution, volatility, and volume patterns.

Identify correlations between stock price metrics such as opening, closing, high, and low prices.

Visualize relationships between variables like volume and closing price.

Build a foundation for potential future predictive modeling.



---

TOOLS USED

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Data Profiling with Pandas Profiling

Jupyter Notebook or similar IDE

Keras (for advanced model options)



---

DATA DESCRIPTION

The dataset contains daily stock data for four major companies. The columns include:

Date – The date of trading

Ticker – The company ticker symbol (e.g., AAPL)

Open, High, Low, Close – Stock prices at various trading points

Adj Close – Adjusted closing price for corporate actions

Volume – Number of shares traded on a given day


The dataset contains 248 entries, evenly distributed across the four tickers.


---

DATA PREPARATION

No missing values were detected in the dataset.

The Date column was converted to datetime format for time-based analysis.

Categorical variables such as Ticker were prepared for grouping and comparative analysis.



---

EXPLORATORY DATA ANALYSIS

DESCRIPTIVE STATISTICS

Mean, median, and standard deviation of stock prices were computed.

Summary statistics highlighted the price range for each stock, with prices spanning from approximately $89 to over $370.


CORRELATION ANALYSIS

A correlation matrix heatmap was generated to examine the relationships between numerical variables.

Very strong positive correlations were observed among Open, High, Low, Close, and Adjusted Close prices.

Volume was weakly and negatively correlated with price, suggesting high trading volume does not directly imply higher prices.



---

VISUALIZATION INSIGHTS

1. CLOSING PRICE DISTRIBUTION

A histogram visualized the frequency distribution of closing prices, indicating how often specific price ranges occurred across all companies.

2. TOTAL VOLUME BY TICKER

A bar chart compared the total traded volume for each stock. This revealed trading activity levels and helped identify which stocks were most frequently traded during the period.

3. VOLUME VS CLOSING PRICE

A scatter plot examined the relationship between trading volume and closing price. While some clustering was observed, the relationship was not strongly linear.

4. BOX PLOT OF CLOSING PRICES

This visualization displayed the quartiles, median, and outliers in the closing prices. It helped identify stock price volatility and detect any anomalies.


---

PANDAS PROFILING REPORT

A complete profile report was generated using the pandas_profiling library. It provided a detailed summary of each column including:

Data types and distributions

Missing values

Correlation statistics

Interactions between variables



---

CONCLUSION

This project successfully demonstrates the use of Python for conducting a stock market analysis. Key insights were drawn regarding price behavior, trading activity, and inter-variable relationships. While no prediction model was developed in this phase, the groundwork has been laid for future extensions involving forecasting using time series analysis or deep learning methods.
