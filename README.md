# MACDynamo
MACDynamo is a bot that does Forex trading for you! Stop spending hours
researching and analysing, just use MACDynamo!

# Set up
1. You need to set up python in your computer. You can use any interpreter but I recommend [Anaconda](https://www.anaconda.com/download).
2. Either create a new environment or in your base environment, install the necessary packages. You can find the full list of necessary packages below.
3. Clone the project into a local directory.
4. In order to use MACDynamo you must download [MetaTrader5](https://www.metatrader5.com/en/download) trading platform as that is an accessible platform which API it uses.
5. Under Accounts in the Navigator, create a new account.
6. In the inbox of the platform you will receive an email with your login details.
7. Create a new file called key.txt in the root of the project.
8. Use the ordering you find in key_template.txt to fill in your login details and server in the newly created key.txt. You can find the server of your account by double clicking your account in the navigator. The default server is MetaQuotes-Demo.

# Customisation
In bot_vars.py, you can set the number of hours you want the bot to run for along with whether you want all open orders to be closed at the end of life.

Note that you need to have your computer running for that amount of time else the bot will stop and likely leave open orders.

# Warning
I cannot guarantee high or even positive returns. From my testing, the returns I have gotten have been more positive than negative but I have a very small sample size and even then it makes very little. You would likely earn more investing in S&P.

There are much more consistent and reliable methods than using solely MACD and renko charts, perhaps this can serve as a template for an ambitious person to build into something amazing.

# Python Packages install commands
* pip install metatrader5
* pip install matplotlib
* pip install pandas
* pip install openssl
* pip install ipykernel

# 8 hour returns
![cum_return_8hr](https://github.com/Arif-Khalid/MACDynamo/assets/88131400/521c3922-c067-4ca1-9981-d8b58156243b)
![ret_8hr](https://github.com/Arif-Khalid/MACDynamo/assets/88131400/25e572a8-4c8a-4ffb-a8ee-46470d589098)
