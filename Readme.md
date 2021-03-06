This project demonstrates how to use https://github.com/TimRivoli/Stock-Price-Trade-Analyzer to evaluate a trading idea by backtesting the results with historical data.

We are all familiar with the saying "Past results are no guarantee of future returns."  While that is definitely
true, I wanted to see how well a trading model would do if it only took into consideration a stocks price performance for the past 12 months.  For my selection of stocks I am picking from the largest 70 stocks on the S&P 500.  I will pick nine stocks from that list that have had the greatest price gain in the past year, and only stocks that have increased by at least 5% in the past year.  The model will buy those stocks, hold them for 30 days, then sell them all, select another set of 9 stocks, and buy those stocks repeating until the end of the testing period.  Each testing period is one year.  Every year from 1982 to 2017 will be tested and then the results evaluated.

For a benchmark to compare my model against, I use hypothetical model of shares of the ^SPX index and which are held for the duration of the test.  My estimate is that this would yield an average annual return of 9.6% from 1982 to 2017.  In the long run, it is very hard to beat a Buy and Hold strategy of good stocks held for the long term, particularly if they are large capital stocks from the S&P 500.  

So, how does my model compare?  In the best year (1999), it makes 136% more than the benchmark, the worst year (1996) it loses 12.74% more, on average it makes 19.34% more than the benchmark of 9.6%.  If I adjust to to only hold the top 5 stocks, then it makes another 3.51% per year on average.  If I drop it to two stocks the returns go even higher.  While past returns are not an guarantee of future returns, they are a very good indicator of future returns. 

Have fun and keep programming!

-Tim
