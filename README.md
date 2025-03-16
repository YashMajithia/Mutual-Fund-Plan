# Mutual-Fund-Plan

# Mutual Fund Plan - NIFTY 50 Stock Analysis

## Project Overview
This project analyzes the **NIFTY 50 stock index** to identify high-growth and high-risk investment opportunities. 
The analysis is performed using historical stock closing prices, allowing investors to assess trends and make informed decisions.


## Dataset
- The dataset consists of closing prices of NIFTY 50 companies.
- It spans multiple years and includes stock price fluctuations.
- The dataset is cleaned to handle missing values before analysis.


## Steps in the analysis
### **1. Data Import and Cleaning:**
- The dataset is loaded into a Pandas DataFrame.
- Missing values are handled using forward-fill techniques.
- The date column is converted into a proper datetime format.

### **2. Stock Price Trend Visualization:**
- Interactive Plotly charts are used to visualize stock price trends.
- Users can observe price movements over time for each stock.

### **3. High-Risk Investment Identification:**
- Volatility (standard deviation of stock prices) is calculated for each stock.
- The top 10 most volatile stocks are identified as high-risk investments.

### **4. High-Growth Investment Opportunities:**
- Percentage change in stock prices is calculated.
- The top 10 highest growth stocks are identified as potential investment opportunities.


## Findings
- Some stocks exhibit high volatility, making them risky but potentially profitable.
- Other stocks show steady high growth, indicating strong investment potential.
- The visualization helps in understanding market trends for better decision-making.

## Tools and libraries used
- Python (Pandas, NumPy, Plotly, Matplotlib, Seaborn)
- Data Visualization: Interactive charts for stock trends
- Statistical Analysis: Standard deviation & percentage growth calculations


## Conclusion
This project provides insights into the NIFTY 50 stock market, helping investors analyze stocks based on risk and growth factors. 
The interactive visualizations and data-driven insights make it easier to evaluate investment opportunities.
