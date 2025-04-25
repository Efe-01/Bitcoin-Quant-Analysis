🧠 Bitcoin Market Analysis Project – Classical Technical Analysis Focus

📌 Project Overview
This project evaluates the predictive power of classic technical indicators—specifically EMA 50, EMA 100, and RSI—in forecasting Bitcoin price movements. By fetching hourly BTC-USD data via yfinance and computing these indicators over the most recent period, we will investigate whether their signals truly anticipate future returns or merely reflect past price action.

🔍 Hypothesis & Thesis
Null Hypothesis (H₀): EMA 50, EMA 100, and RSI do not exhibit a statistically significant relationship with subsequent Bitcoin price movements; any apparent signal is no better than random chance.

Alternative Hypothesis (Hₐ): At least one of these indicators shows measurable, statistically significant correlation with future price direction, implying genuine predictive value.

Thesis Statement: Through rigorous correlation testing, hypothesis testing, visual analysis, and backtesting, this study will determine if traditional technical tools provide a real information edge in high-volatility crypto markets or if they are simply lagging, hindsight-biased measures.

🎯 Objectives
Assess Indicator Effectiveness

Compute Pearson correlation coefficients and p-values between each indicator (EMA 50, EMA 100, RSI) and future hourly returns.

Validate Statistical Significance

Test the null hypothesis at α = 0.05, identifying which indicators—if any—carry meaningful signals.

Backtest Simple Strategies

Simulate rules such as RSI oversold/overbought and EMA crossovers; measure performance metrics (total return, Sharpe ratio, drawdown, win rate).

Visualize Relationships

Produce heatmaps, histograms + KDEs, violin + jitter plots, hourly-return box plots, and equity curves to illustrate indicator behavior and strategy outcomes.

Challenge Conventional Assumptions

Determine whether retail traders’ reliance on EMA and RSI is supported by data or driven by hindsight bias.

💡 Motivation
Technical analysis is deeply ingrained in retail trading culture, yet its actual efficacy—particularly in fast-moving markets like Bitcoin—remains debated. By applying a data-driven framework and transparent statistical methods, this project seeks to clarify whether common indicators deliver genuine foresight or simply echo price history.

📁 Dataset
Source: yfinance library, hourly BTC-USD data.

Period: Last 200 days (≈ 4,800 hourly observations).

Fields:

Close: Adjusted closing price

EMA 50: 50-period exponential moving average

EMA 100: 100-period exponential moving average

RSI: 14-period relative strength index

Return: Hourly percentage change

🛠️ Tools & Technologies
Python & Libraries:

pandas, numpy (data wrangling)

scipy.stats (Pearson correlation, p-values)

statsmodels, sklearn (regression, logistic model, AUC)

matplotlib, seaborn (advanced plotting)

yfinance (data retrieval)

Environment: Google Colab or local Jupyter Notebook

📊 Analysis Plan
Data Collection & Preprocessing

Retrieve hourly data, localize and clean index, compute indicators.

Correlation & Significance Testing

Use pearsonr to calculate r and two-tailed p-values for each indicator vs. next-hour return.

Visualization

Heatmap of all pairwise correlations

Histogram + KDE for indicator distributions

Violin + Jitter split by positive vs. negative returns

Box Plot of returns for each hour of the day

Equity Curves comparing strategies vs. buy-and-hold

Strategy Backtesting

Define simple rules (RSI thresholds, EMA crossovers), simulate trades, and compute:

Total return

Annualized Sharpe ratio

Maximum drawdown

Win rate

One-sample t-test p-value vs. zero-mean returns

Reporting & Interpretation

Summarize which indicators, if any, showed predictive value

Discuss strategy performance against buy-and-hold benchmark

Provide actionable insights on the utility of classical technical analysis in Bitcoin trading

🧩 Example Analyses
EMA Crossover Evaluation:

Measure average returns 1–5 hours after EMA 50/EMA 100 crossings; compute hit/miss rates.

RSI Extremes:

Analyze short-term returns following RSI >70 (overbought) and <30 (oversold) signals.

Combined Signals:

Test confluence strategies requiring both RSI and EMA conditions; compare accuracy against single-indicator rules.








