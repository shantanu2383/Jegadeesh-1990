# "Evidence of Predicatibility of Security Returns" (Jegadeesh, 1990)
https://onlinelibrary.wiley.com/doi/10.1111/j.1540-6261.1990.tb05110.x

The code attached attempts to replicate and update the results of Jegadeesh (1990) using CRSP monthly data from 1982-2022, obtained from the Wharton Data Research Services CRSP library. The code replicates the observed negative first-order serial correlation in monthly stock returns, along with significant positive serial correlation at longer lags, with the twelve-month serial correlation being particularly strong. The code also generates one-step-ahead return forecasts using the observed systematic behavior of stock returns and forms ten portfolios from these forecasts, similar to Jegadeesh's approach.

Table 1 of the replicated study shows similar results to Jegadeesh's findings on serial correlation, with a visible pattern present in the slope coefficients. However, the values for the coefficients at lags one and twelve (-.03 and 0.011, respectively) are smaller in magnitude compared to Jegadeesh's. We also observe high coefficients at lags twenty-four and thirty-six, similar to the coefficient at lag twelve. Our results reveal that coefficients a1, a2, a4, a12, a13, and a14 are all significant at the 1% level, with an adjusted r-squared of .078, akin to Jegadeesh's findings.

In table 2, we form predictive portfolios using three different strategies. Strategy S0 uses out-of-sample forecasts based on lagged returns to predict future returns, and ranks securities based on these forecasted returns. Under Strategy S1, securities are ranked based on their one-month lagged returns, while under S12, securities are ranked based on their lagged 12-month returns. 

Table 3 displays the proportion of months in which each portfolio exhibited positive abnormal returns. Our results show that the proportion of months in which the portfolios exhibit positive abnormal returns decreases as we move from portfolio P1 to P10 under all three strategies, similar to Jegadeesh's findings. 

In Table 5 we estimate the abnormal returns of the strategies under a size based factor model.  We do observe a significant drop in abnormal returns in January, compared to the market model, under Strategy S0. On the other hand, Strategy S1 yields higher returns overall and does not show a significant drop in abnormal returns in January.
