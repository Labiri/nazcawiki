## Creating an account on Binance

A Binance account is required for Nazca to perform the trades. If you already have a Binance account you use for your trading or holdings, you can create a new account with a different email address, and Binance also lets you verify it by simply using a different document (e.g. main account verified with Passport, second account verified with national ID).

If you don't have an account yet, creating and funding a Binance account is very easy. Go to Binance.com and click on the `Register` button. 

Note: You can register with our referral link if you would like to support our work: https://www.binance.com/?ref=35076996

Warning: Make sure you actually are on the Binance website (and not on a phishing website) by checking the SSL certificate's validity next to the address bar.

Complete the registration form and open the registration email Binance will send you to activate your account. Once validated, it is strongly recommended to add Two Factor Authentication _(the process is very similar to Coinbase's one we covered in the section [Purchasing Cryptocurrencies](coinbase.md) of this guide)_


Now, verify your identity by following the instructions (_This step is not mandatory, but highly recommended_)

![binance_verify](https://lvena26b6e621o8sl2qkx1ql-wpengine.netdna-ssl.com/wp-content/uploads/2017/10/Binance-Verification.jpg)

It may take up to a day or two to be verified, so don't worry if doesn't happen immediately.

## Generating API keys
You will need API Keys to let Nazca run your strategy for you. After logging into your account, go to "**Account**" and click on "**API Setting**".

_Please note you must have enabled 2FA in order to generate API keys._

<p align="center">
<img src="https://github.com/NazcaBot/nazcawiki/raw/master/res/api1.png">
</p>


Enter a name for your API key and click on "**Create New Key**". Binance will now ask for your 2FA and send you a confirmation email. Confirm the email you received and your API Key will be ready.

![binance_api2](https://github.com/NazcaBot/nazcawiki/raw/master/res/api3.png)

Make sure to only have enabled **Read info** and **Enable Trading**, and to leave **Enable Widhdrawals** disabled (un-checked).

Attention: Note down the keys in a safe place, since you won't be able to see the secret key again and you would have to generate a new set.


## Adding funds to your account
Go to `Funds -> Deposits` and select the coin\token you would like to send to your Binance account. For example, if you purchased Bitcoin on Coinbase, select "BTC - Bitcoin".

![binance_fund](https://i.imgur.com/fir3B29.png)

Click on `Copy Address`. This will be the destination address to use when sending your funds:

<p align="center">
<img src="https://github.com/NazcaBot/nazcawiki/raw/master/res/bina_wall.png">
</p>


Also, make sure "Using BNB to pay for fees" is `enabled`: that will reduce the cost of your trades:
![bina_bnb](https://github.com/NazcaBot/nazcawiki/raw/master/res/bina_bnb.png)

You can now go back on Coinbase and send your funds over:

<p align="center">
<img src="https://coinatmradar.com/blog/wp-content/uploads/2017/11/coinbase1.png">
</p>

The transaction will now need to be confirmed by the network. You can refresh the Binance page to see the status of the transaction.

<p align="center">
<img width="600" height="63" border="0" src="https://github.com/NazcaBot/nazcawiki/raw/master/res/barr.png">
</p>



