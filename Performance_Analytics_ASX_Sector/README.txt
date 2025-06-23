About the Project:
--------------------------
This project analyzes the performance of 20 ASX-listed companies across 5 major sectors — Mining, Finance, Retail, Healthcare, and Technology — using real stock market data over a 12-month period.

Using Python, I built a data pipeline to collect, clean, and analyze historical stock prices. I calculated daily returns, volatility, and moving averages for each stock, then aggregated the results to compare performance at the sector level.

The analysis includes clear visualizations (bar charts and heatmaps) and an exportable sector summary file, highlighting top and bottom performers by return. Key insights were drawn to show how different sectors behave under market conditions, helping to inform smarter portfolio and risk decisions.

Tools & Skills Applied:
-------------------------
1.Python (Google Colab)
2.Pandas, NumPy – data analysis
3.yFinance – real-time data scraping
4.Matplotlib, Seaborn – data visualization
5.Financial metrics – return, volatility, correlation
6.Data storytelling – visual insights + markdown reporting

How to Run This Project:
----------------------------
Follow the steps below to run the ASX Sector Analytics notebook and reproduce the analysis.

1. Install Relevant Python Libraries:

!pip install yfinance pandas matplotlib seaborn --quiet  

2.Running the Project

Open the notebook in Google Colab (recommended) or Jupyter Notebook.

Run all cells in sequence:
-----------------------------
The script pulls real-time historical price data for 20 ASX-listed companies using the yfinance API.
It calculates financial metrics such as:

	Daily returns

	Volatility (standard deviation)

	20-day and 50-day moving averages

	Sector grouping is applied to summarize performance by industry.

Visualizations are generated:
----------------------------------

	1. Bar charts for average return and volatility by sector

	2.Correlation heatmap to visualize inter-stock relationships

The notebook exports:
------------------------

	1.sector_summary.csv – includes top & bottom performers, return, and volatility by sector

	2.all_stocks_with_moving_averages.csv – close price + moving averages for each stock

