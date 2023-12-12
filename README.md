# Stock-portfolio-selection-optimization-and-comparison

Hello! Welcome to our project on Stock portfolio selection, optimization and comparison.

In this project we aim to guide you on our project, while showing you our code and results in a well documented manner. Below is the gist of our work:

  In this project, we select 30 stocks from 2017-2021, 10 from each sector of Financials, Materials and Consumer Discretionary ; as assigned to us by our mentor.

  Following this, we perform momentum trading (strategy where we stay invested only if the 8 day moving average of the stock is higher than the 21 day moving average of the stock) on these stocks to identify three best performing stocks for each sector mentioned above. (Total of 9)

  Upon choosing the 9 stocks, we optimize these stocks using pyomo and ipopt by maximizing the stock returns for various levels of risk.

  From this we choose an appropriate risk level containing proportions from 3 stocks as our MPT portfolio.

  To benchmark the performance of the portfolio, we used the well-known S&P 500 stock for the year 2022 to which we perform buy-and-hold strategy (Buy the stocks and check stock value over time) as well as momentum trading strategy. Correspondingly, we compare Buy-and-hold and momentum trading strategies for our MPT portfolio (for the same year) as well and compare the performance.

  Finally, we provided the conclusions and inferences from this analysis to gain some insights and experience on stock portfolio optimization.

We hope the rest of the project files provide a detailed account of what we've accomplished.
