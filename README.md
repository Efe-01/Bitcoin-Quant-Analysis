🧠 Bitcoin Market Analysis Project – Classic Technical Analysis Focus
📌 Project Overview
In this project, I will analyze the effectiveness of classical technical indicators—specifically EMA 50, EMA 100, and RSI—in predicting Bitcoin price movements. The primary goal is to determine whether these indicators offer reliable signals for market direction and can be effectively used in trading strategies.

By collecting historical Bitcoin data using the yfinance library, I aim to examine whether traditional technical analysis holds predictive value or if its perceived effectiveness is overstated. The project will explore the statistical relationships between these indicators and actual price movements over time.

🔍 Hypothesis & Thesis
Hypothesis:
The core hypothesis of this study is that classical technical indicators, such as EMA 50, EMA 100, and RSI, do not have a statistically significant relationship with future Bitcoin price movements. In other words, their signals are assumed to be lagging, non-predictive, and comparable to randomness. This view challenges the widespread belief in the predictive strength of technical analysis.

Alternative Hypothesis:
There exists a measurable and statistically significant relationship between one or more of the indicators (EMA 50, EMA 100, RSI) and the direction of Bitcoin prices. These indicators could potentially be used as reliable inputs for decision-making in trading strategies.

Thesis Statement:
This project aims to critically examine the predictive power of widely used classical technical indicators—EMA 50, EMA 100, and RSI—within the context of Bitcoin trading. Through statistical testing, data visualization, and backtesting strategy performance, the research seeks to uncover whether these tools truly provide an informational edge or simply reflect market behavior in hindsight. The results of this analysis may either support or refute the merit of traditional technical analysis in high-volatility, data-driven markets like cryptocurrency.

🎯 Objectives

Evaluate the Effectiveness of Classic Technical Indicators
Assess how well EMA 50, EMA 100, and RSI correlate with future Bitcoin price direction.

Test the Validity of Technical Analysis
Determine whether technical indicators offer meaningful insights or produce results no better than random chance.

Analyze Indicator-Based Strategy Performance
Simulate and evaluate the success rate of strategies based solely on these indicators.

Challenge Conventional Assumptions
Investigate whether traders can reliably use RSI and EMAs to gain an edge in the market.

💡 Motivation
Technical analysis is widely used among retail traders and investors. However, its actual effectiveness—especially in volatile markets like cryptocurrency—is often debated. This project aims to assess whether common indicators like EMA and RSI offer genuine predictive power or are largely reactive to past price movements. By applying a data-driven approach, I hope to provide clear insights into the value of technical analysis in Bitcoin trading.

📁 Dataset
All data will be retrieved using the yfinance Python library, and will include:

Bitcoin Price Data: Historical OHLCV (Open, High, Low, Close, Volume) data.

Technical Indicators:

EMA 50 (50-period Exponential Moving Average)

EMA 100 (100-period Exponential Moving Average)

RSI (Relative Strength Index)

The data will be structured and cleaned for time series and correlation analysis.

🛠️ Tools and Technologies

Python: Core programming language for analysis

Pandas: Data manipulation and preprocessing

NumPy & SciPy: Statistical testing and numerical operations

Matplotlib & Seaborn: Data visualization (line plots, histograms, correlation heatmaps)

📊 Analysis Plan

Data Collection & Preprocessing
Use yfinance to extract historical BTC-USD data
Calculate EMA 50, EMA 100, and RSI values
Align indicator values with price movement data

Visualization & Correlation Analysis
Visualize indicators overlaid on price charts
Create heatmaps and scatter plots to identify relationships between indicators and price direction

Hypothesis Testing

Null Hypothesis (H₀): Classical technical indicators do not offer statistically significant signals for price direction

Alternative Hypothesis (Hₐ): Technical indicators provide statistically meaningful signals for price movement
Perform correlation analysis and statistical significance testing

Strategy Simulation & Performance Evaluation
Define basic trading rules based on RSI and EMA crossovers
Backtest these strategies over historical data
Measure success rates, risk/reward ratios, and drawdowns

📈 Example Analysis

EMA Cross Strategy
Compare price performance following EMA 50 / EMA 100 crossovers
Analyze frequency of accurate trend signals vs. false positives

RSI Overbought/Oversold Zones
Evaluate how price behaves after entering extreme RSI levels (>70 or <30)
Track short-term returns after these signals

Combined Signal Analysis
Combine RSI and EMA rules to generate confluence signals
Assess whether multi-indicator signals improve accuracy

🧩 Expected Insights
By the end of this project, I aim to answer the following:

Do classical technical indicators reliably predict Bitcoin price direction?

Are strategies based on RSI and EMAs profitable or prone to false signals?

Does traditional technical analysis have merit, or is it mostly hindsight bias?

Can a simplified, data-backed strategy be formed using just these indicators?

This project will help clarify the real-world utility of technical analysis in Bitcoin trading and provide insights that can inform more rational, evidence-based trading decisions.
