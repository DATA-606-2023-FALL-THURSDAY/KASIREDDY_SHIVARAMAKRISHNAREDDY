# Price Performance Prediction

**Prepared for**: UMBC Data Science Master's Capstone by Dr. Chaoji (Jay) Wang - SPRING 2024  
**Author**: Shivaramakrishna Reddy Kasireddy  

## Background

### 1. What is it about?
The report is centered on "Price Performance Prediction," specifically analyzing Microsoft (MSFT) and JP Morgan (JPM) stocks within the S&P 500 framework. It explores the relationship between these stocks and the S&P 500 index, examining their historical performance over the past decade. Using financial modeling techniques, the analysis uncovers correlations, calculates beta coefficients, and compares Sharpe Ratios for both stocks against the S&P 500.

### 2. Why does it matter?
Accurate stock price prediction is crucial in finance, helping investors, traders, and institutions make better decisions. Understanding future price movements supports risk management, optimizes investment strategies, and minimizes losses. Insights into Microsoft, JP Morgan, and the S&P 500 help stakeholders navigate financial markets more strategically.

### 3. What are your research questions?
1. How strongly are Microsoft and JP Morgan correlated with the S&P 500 index, and what does that imply about their performance?
2. How do Microsoft and JP Morgan compare in terms of beta coefficients, and what does this indicate regarding their volatility and market sensitivity?
3. What are the Sharpe Ratios of these two stocks compared to the S&P 500, and what does this suggest about their risk-adjusted returns?
4. How well do different machine learning models predict and compare the performance of these stocks?

### 4. Why is it relevant?
This analysis offers practical insights for stakeholders to maximize returns while minimizing risks in today's market. Comparative studies help investors choose stocks based on risk appetite and strategy. Financial models like ARIMA and LSTM provide a comprehensive perspective on market trends.

## Dataset

- **Source**: Yahoo Finance  
- **Time Span**: Past 10 years  
- **Size**: 25-65 MB  
- **Rows**: 2516  
- **Columns**: 6  
- **Link**: [Yahoo Finance - S&P 500 (^GSPC) Historical Data](https://finance.yahoo.com/quote/%5EGSPC/history?period1=1550188800&period2=1707955200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true)  

## Exploratory Data Analysis (EDA)

### Data Overview
EDA provides critical insights into dataset structure, distribution, and relationships between variables.

### Data Cleansing
- **Missing Values**: None detected, ensuring completeness.
- **Duplicate Rows**: None found, maintaining data consistency.

### Data Visualization
- Data visualization and cleansing help identify outliers and feature relationships.

## Analysis

### Key Insights
- **Correlation**:  
  - Microsoft & S&P 500: 0.98  
  - JP Morgan & S&P 500: 0.74  

- **Beta Coefficient**:  
  - Microsoft: 1.21  
  - JP Morgan: 1.12  

- **Sharpe Ratio**:  
  - Microsoft: 0.06  
  - JP Morgan: 0.56  
  - S&P 500: 0.52  

### Models Used for Prediction
1. **Linear Regression**: Evaluates relationships.
2. **Moving Averages**: Smoothens data.
3. **ARIMA**: Forecasts non-stationary data.
4. **Random Forest Regression**: Ensemble learning.
5. **LSTM**: Sequential data handling.
6. **SVM**: Non-linear relationships.
7. **PCA**: Dimensionality reduction.

## Conclusion
- Microsoft aligns closely with the S&P 500, providing market predictability.
- JP Morgan has superior risk-adjusted returns, ideal for risk-averse investors.

**Benefits**:  
- Predicts stock prices, factors, and trends.  
- Enhances risk management and portfolio optimization.

**Thank you!**

