### DETERMINING PORTFOLIO PERFORMANCE

## Applying Quantitative Techniques using Python and Pandas

I'm comparing portfolio performance across the following areas:
* Volatility
* returns
* risk
* sharpe ratio

In use analysis notebook that analyses and visualises the major metrics of portfolios across all of the above mentioned areas and determined which portfolio outperformed the others.
I use historical daily returns of several portfolios including:
* Algorithmic portfolio
* Whale investors
* S&P TSX60 index
I also include my own custom portfolio for comparison.

For comparison I read the data from the csv files and clean it by removing all nulls, indexing and remaning columns as required and joining the dataframes.

# I perform a quantitative analysis by:

* calculating a plotting daily return of all portfolios
* Calculating cumulative returns for all portfolios and determing if any outperforms the S&P TSX60

# I perform a rick analysis by:
* creating a box plot for each return
* Calculating Standard deviation for each portfolio
* I determine which portfolio is riskier than the S&P TSX 60
* I calculate the annualised standard deviation

# I calculate rolling statistics by:
* calculating and plotting rolling standard deviation for all portfolios using a 21-day window
* calculating and plotting correlation between each stock to determine which portfolios mimic the S&P TSX 60
* I choose one portfolio, BERKSHIRE HATHAWAY INC, calculate and plot the 60 day rolling beta between that BERKSHIRE HATHAWAY INC and the S&P TSX 60 

# Calculate Sharp Ratio to determin return to risk ratio.

# I use Google sheets (Google Finance) to build a custom portfolio of 3 stocks.

* I read and clean the data
* calculate standard deviation of my portfolio
* Calculate and plot rolling standard devaition with a 21 day window
* I calculate and plot correlation
* I Calculate and plot Beta to compare my portfolio to the S$P TSX 60
* I the calculate the sharp ratio and generate a bar plot.




