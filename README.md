# Investment Analysis

## Quantitative Analysis

*Lists are presented in order.*

### Performance Analysis

Over the ~4-year time horion tracked in the data, two portfolios outperformed the S&P 500:

1. Algo 1
2. Berkshire Hathaway Inc.

### Risk Analysis

Looking at a box plot of the returns data, the portfolios with the tightest spreads were:

1. Paulson & Co. Inc. 
2. Algo 1

The portfolios with the widest spreads were:

1. Berkshire Hathaway Inc. 
2. Tiger Global Management LLC

This is reflected in both the daily and annualized standard deviations for both of these portfolios. 

Of all the portfolios, only the Berkshire and Tiger Global are riskier than the S&P 500. The **Paulson & Co.** portfolio is the safest. 

### Rolling Statistics

Considering correlation of rolling 21-day standard deviations for each portfolio, risk generally increases at the same time as the S&P 500 for the following portfolios (correlation > 0.75):

1. Soros Fund Management LLC
2. Algo 2
3. Berkshire Hathaway Inc.

The **Tiger Global** portfolio least correlated with the S&P 500, with risk spiking at unrelated times. 

In terms of returns, the following portfolios were most correlated with the S&P 500 (correlation > 0.75):

1. Algo 2
2. Soros Fund Management LLC
3. Berkshire Hathaway Inc. 

The least correlated portfolio was **Algo 1**. Looking further into this portfolio, we can observe a rolling 60-day beta that rarely breaches 0.5 and occasionally goes negative vs. the S&P 500, further demonstrating the lack of correlation between this portfolio and the US stock market. 

## Sharpe Ratios

Considering the Sharpe ratios for each of these portfolios, we can see that the algorithmic portfolios generally offer a better return for the amount of risk. The **Algo 1** portfolio sits on top with an impressive Sharpe ratio of 1.38. The Berkshire Hathaway portfolio has the next highest, but generally the whale portfolios do not have great Sharpe ratios - both the Paulson & Co. and Tiger Global portfolios have negative Sharpe ratios. 

## Custom Portfolio

### Performance Analysis

Over a time horizon of ~4 years, my custom portfolio (equally weighted between the stocks of Apple, Facebook, and Disney), slightly outperformed the S&P 500. However, only right at the end of the time period - for the entire time up until this point, it was underperforming. 

### Risk Analysis

A box plot between this portfolio, all other portfolios, and the S&P 500 show a significantly wider spread. Both the normal and annualized standard deviations were extremely high, indicating much higher volatility in terms of returns. 

### Rolling Statistics

Generally the standard deviations did not correlate with the S&P 500 in a consistent manner, and had much greater swings. Occasionally they would display an inverse relationship. 

Returns generally seem extremely related to the market, however, with a rolling 60-day beta that would occasionally exceed 1 and for a short time exceeded 2. For a while in 2017 and 2018, the beta was negative, but I would need to dig deeper into this to explain why. 

### Sharpe Ratios

Despite the risk involved with this portfolio (high-volatility and low diversification), the phenomenal returns that it produced landed this portfolio with a Sharpe ratio that exceeded all other portfolios except **Algo 1**.


