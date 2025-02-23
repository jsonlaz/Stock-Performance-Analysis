# Stock Performance Analysis

This project uses Python and Tableau to analyze and visualize 7 tech stock data over 5 years (2020-2024).

## Data

**Stocks:** AAPL, AMZN, GOOGL, META, MSFT, NVDA, and TSLA

The `export/` directory contains the following CSV files:

* `stock_data.csv`: Raw stock data from Yahoo Finance.
* `daily_returns.csv`: Daily percentage changes in stock prices.
* `cumulative_returns.csv`: Cumulative returns over time.
* `volatility.csv`: Rolling annualized volatility.

## Code

The `src/` directory contains the Python Jupyter notebook `Tech Stock Analysis.ipynb`, which performs the data analysis and calculations.

## Analysis

The exploratory data analysis is performed in Python using Pandas, Matplotlib, and Seaborn libraries. It consists of the following:

* Extracted data for AAPL, AMZN, GOOGL, META, MSFT, NVDA, and TSLA from Yahoo Finance using yfinance.
* Calculated the stocks' daily, cumulative, and annual returns using numpy.
* Calculated and visualized the correlation matrix of daily returns using numpy and seaborn to understand how the stocks' prices move together.
* calculated the stocks' volatility and annualized volatility using numpy.
* Exported and saved the relevant datasets as CSV files.

## Visualizations

The visualizations are available on Tableau Public:

**Dashboard 1:** [Visualizations Using Tableau](https://public.tableau.com/app/profile/john.lazarus/viz/StockMarketTrends_17402629786650/Dashboard1)

* Stock Prices Over Time (Line Chart)
* Cumulative Return by Year (Bar Chart)
* Annual Volatility (Bar Chart)

**Dashboard 2:** [Visualizations Using Tableau](https://public.tableau.com/app/profile/john.lazarus/viz/StockMarketTrends_17402629786650/Dashboard2)

* Cumulative Returns Over Time (Line Chart)
* Cumulative Return Table
* Average Annual Returns (Bar Chart)

## Results:

* NVDA has been the standout performer, exhibiting the most significant growth in stock price and cumulative returns, especially in 2023 and 2024. It also shows high volatility, indicating significant price swings.
* TSLA has also delivered high returns, particularly in 2020 and 2021, but with even greater volatility than NVDA.
* AAPL, MSFT, GOOGL, and AMZN have demonstrated consistent and steady growth in stock prices and cumulative returns. Their volatility is generally lower compared to NVDA and TSLA, suggesting more stable price movements.﻿﻿ 
* The COVID-19 pandemic caused a noticeable market downturn in early 2020, impacting all stocks. This is reflected in lower cumulative returns and higher volatility in 2020.
* The market has shown strong positive returns in 2023 and 2024, with most stocks exhibiting significant growth.

## Contributing

Feel free to contribute to this project by submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
