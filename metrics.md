Attention: this page is still in development.

# Models and Backtests

***

## Available Models
### Even Distribution
An even distribution model maintains an equal USD value of each asset in the portfolio. The assets are equalized during each rebalance period to account for the profits and loses of each asset during that period. It is a contrarian investing method - meaning that when the price goes up, you sell, when the price goes down, you buy.

**Example \ Case study:**
You begin with a portfolio of 50% ETH and 50% LTC. During the first rebalance period the price of LTC doubles. Your portfolio now looks like 33.3% ETH and 66.6% LTC. To re-establish the even distribution, you must sell LTC and buy ETH.

**Pros:**
* Largely diversified, and equal reliance on each asset.
* Performs well in a volatile market.

**Cons:**
* Constantly changing prices may lead to heftier rebalances, and thus higher rebalancing fees.
* Higher exposure to relatively lower market cap assets.
* Does not perform well in a trending market.

### Market Cap Distribution
A Market Cap Distribution is a model where assets are weighted proportionally to their total market capitalization in USD, and therefore, assets with higher market capitalization carry a higher percentage weighting. The asset weightings are rebalanced during each rebalance period to align with these market capitalization.

Tip: This distribution is typically paired with the top 10 coins by market cap.

**Example \ Case study:** 
You invest $1,000 in BTC (41% of total crypto market cap), ETH (15% of total crypto market cap) and XRP (8% of total crypto market cap). Your initial asset allocation will be:

* $640.63 worth of BTC (64.063% of portfolio market cap)
* $234.37 worth of ETH (23.437% of portfolio market cap)
* $125.00 worth of XRP (12.5% of portfolio market cap)

_Rebalance period 1_ - The market caps of your chosen assets have changed. BTC (44% of total crypto market cap), ETH (16% of total crypto market cap) and XRP (7% of total crypto market cap). We will rebalance your portfolio in the optimal way, minimizing fees to arrive at the new distribution as follows:

* $656.71 worth of BTC (65.671% of portfolio market cap)
* $238.80 worth of ETH (23.880% of portfolio market cap)
* $104.47 worth of XRP (10.447% of portfolio market cap)

### Custom Distribution
You define your asset weighting, and we maintain that distribution during each rebalance period.

**Pros:**
* Human Intuition
* Flexibility

**Cons:** Emotion

**Example \ Case study:** 
You choose the following custom distribution of crypto tokens:

* EOS (EOS) - 50%
* TRX (TRON) - 25%
* VEN (VeChain) - 25%
* Rebalance period: 14 days
Every 14 days, your portfolio will be automatically rebalanced to align with your custom allocations.

***

## Backtests
### Profit and Risk metrics
* **Annualized Return:** average of amount of money earned each year over a given time frame. Shows possible earnings over a period of time if the annual return is compounded.

* ** Annualized Volatility:** measures the variance of returns over a period of time. Daily returns are calculated along with their standard deviation _(variance from the mean of a data set)_ to give daily volatility, then annualized over the course of a year.

* **Sharpe Ratio:** Measures whether the returns you are making are worth the risk you are exposing your portfolio to.

* **Max Drawdown:** Maximum loss over a given period, from the maximum value (peak) to the minimum value (trough).

* **Downside Risk:** estimates an asset's potential to suffer a decline in value if the market conditions change, or the amount of loss that could be sustained as a result of the decline.

* **Mean Est. Fee:** 

***

<p align="center">
<img width="600" height="63" border="0" src="https://github.com/NazcaBot/nazcawiki/raw/master/res/barr.png">
</p>
