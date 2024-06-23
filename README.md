# Portfolio Selection, Optimization and Comparison
Hello! Welcome to my notebook on Stock portfolio selection, optimization and comparison.

In this notebook I aim to guide you on my project, while showing you my code and results in a well documented manner. Below is the gist of our work:


In this project, I will select 30 stocks from 2017-2021, 10 from each sector of Financials, Materials and Consumer Discretionary ; as assigned to us by our mentor.

Following this, I will perform momentum trading (strategy where we stay invested only if the 8 day moving average of the stock is higher than the 21 day moving average of the stock) on these stocks to identify three best performing stocks for each sector mentioned above. (Total of 9)

Upon choosing the 9 stocks, I will optimize these stocks using pyomo and ipopt by maximizing the stock returns for various levels of risk.

From this I will choose an appropriate risk level containing proportions from 3 stocks as our MPT portfolio.

To benchmark the performance of the portfolio, I have used the well-known S&P 500 stock for the year 2022 to which I perform buy-and-hold strategy (Buy the stocks and check stock value over time) as well as momentum trading strategy. Correspondingly, I will compare Buy-and-hold and momentum trading strategies for our MPT portfolio (for the same year) as well and compare the performance.

Finally, I provided the conclusions and inferences from this analysis to gain some insights and experience on stock portfolio optimization.

I hope the rest of the notebook provides detailed account of what I've accomplished.

P.S. Please use the Table of contents on the left tab to quickly navigate to any section of our notebook
