# Creating strategies on Nazca
## Ready?
On Nazca, everything has been simplified to let you build, check and manage your portfolio with ease. The creation of the strategy happens in 3 simple steps through the wizard.

***

## Step 1: assets and distribution model

### Choosing **distribution model** and **rebalance period**

Here you can choose how to allocate your assets and how often Nazca should rebalance them for you. Each one will give your portfolio specific alignments and different levels of risk: make sure to check the **Distribution Models** section of this wiki to learn more about them.

![nazca_model](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_model.png)

### Selecting **assets**

Here is where you decide how your portfolio should be **diversified**. Pick your desired assets manually, or let Nazca dynamically choose them basing on specific criteria.

![nazca_assets](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_assets.png)

Once you are convinced about the strategy you just created, click on `Run Backtest` to proceed to the next step.
***
## Step 2: Backtest
### Measuring performances and risks

In this second step, you can run a simulation to see how your portfolio strategy would have performed over a given time frame and get a glimpse about its potential returns and risk levels.

![nazca_backtest](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_backtest.png)

The bold blue line indicates your portfolio, compared to the other colored lines (respectively Total Market Cap, Altcoins Market Cap, and the top three assets by Market Cap) and your assets weights can be seen by simply hovering the mouse over the chart. Learn more about metrics in the **Backtest Metrics** section.

The default backtest is ran over 365 days, but you can change it by clicking on the dates:

![nazca_backtest_dates](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_bt_dates.png)

**Need to revise your strategy configuration?** No worries! Go back to the first step and run the backtest again until you are comfortable with the changes. 

![nazca_goback](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_goback.png)

***
## Step 3: Review and execute
### Adding API keys
In this last step you can link Nazca to your Binance account thought the API Keys [you previously generated](binance.md#Generating_API_keys).

![nazca_api](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_api.png)

Make sure your keys are working by clicking on `Validate API keys`.

### Selecting your subscription and executing the strategy
You are almost done! Just select the subscription type you would like to start with, and proceed with the payment.

![nazca_execute](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_execute.png)

You will be redirected to Coinbase commerce, where you can complete the payment. Nazca will execute your strategy as soon as the purchase is confirmed.

![nazca_payent](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazc_payment.png)

***

## The Dashboard
**Congratulations!** Your strategy has been executed and you can now follow its progress from the Dashboard.

![nazca_dashboard](https://github.com/NazcaBot/nazcawiki/raw/master/res/dashb.png)

From the Dashboard you can also manage your strategy. You have three options:
1. **Pause** - _pause your strategy and not rebalance it, or delete it_

![nazca_pause](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_pause.png)

2. **Edit** - _edit your strategy and go back to the Wizard_

3. **Rebalance Now** - _trigger a manual rebalance at any moment_

![nazca_rebalance](https://github.com/NazcaBot/nazcawiki/raw/master/res/nazca_rebalance.png)







