Trading Signal Scanner and Visualization

This Python project analyzes and visualizes stock data for the BIST 500 index, computes technical indicators, draws interactive charts, and scans for buy signals for the next trading day.

Features
	- Data Loading: Reads historical CSV files for each ticker under ./data/.
	•	Technical Indicators:
	•	RSI (14-period)
	•	MACD, Signal Line, and Histogram
	•	Stochastic Oscillator (%K, %D)
	•	Exponential Moving Averages (5, 8, 13, 34 periods)
	•	All-Time High/Low over the last 60 bars
	•	Missing Dates: Detects and filters out non-trading days when plotting.
	•	Upper Limit Filter: Flags when a stock has reached a 9.5% intraday increase (potential limit-up).
	•	Interactive Visualization: Uses Plotly to generate candlestick charts with overlays for indicators and buy markers.
 
- **Backtesting & Reporting**: A Jupyter notebook `backtest.ipynb` demonstrates historical strategy performance and includes a QuantStats report boasting a **Sharpe ratio of 4.2**.
