# btc-USM2-regression-analysis
An OLS time series regression, BTCs price on the increase of M2

A log-log model linear regression model on first differences.

 Δlog(BTCt) = α + β * Δlog(M2t) + ε

After seeing a chart of the price of Bitcoin correlate with the increase of M2, I decided to investigate. Using Fred and Stooq data, and monthly intervals 2020-2025. 

Δlog(BTCₜ) = α + β * Δlog(M2ₜ) + εₜ

Log-log linear regression model in first differences, regressing the monthly log return of Bitcoin on the monthly log growth rate of U.S. M2. This is a constant elasticity model commonly used in macro-financial time series analysis.

Indeed, a 1%  increase in the USM2 money supply results in a 1.73% increase in the price of bitcoin, on average, within the same month. 

BTC Log returns are weakly dependent; however, the USM2 suffers from high autocorrelation, but can be explained by the fact that the M2 grows cumulatively and smoothly. 
