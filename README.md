# Profitability of Cryptocurrency Pump and Dump Schemes
Taro Tsuchiya (Keio University Faculty of Economics)

## Abstract

One of the price manipulation schemes achieved by artificially increasing the trading volume of the target asset, Pump & Dump (P&D) schemes, has a long history in the stock market and is usually considered unlawful. In cryptocurrency markets, however, this scheme has not been well-regulated and uniquely orchestrated through a new type of social media platform such as Telegram. Because there have been few investigations on P\&D schemes in the cryptocurrency market so far, this paper aims to identify the features of P\&D organized through Telegram and examine the market resilience to these activities. This research forms a regression model in a Bayesian hierarchical framework to clarify variables that contribute to the profitability (i.e., price hike) of P\&D attempts. It is revealed that the price resilience to these activities significantly differs across each exchange market. Particularly, Yobit and Cryptopia are more sensitive to the increase in the trading volume than Binance and Bittrex while controlling other significant factors such as the timing of the pump (hourly, yearly), currency, and Telegram channel. Furthermore, this paper builds a machine learning model to identify the price hypes (successful schemes) given the information before the pump activity and achieved more than 75% accuracy using tree-based ensemble models. The contribution of this paper is to provide a detailed analysis of P&D schemes using a novel statistical approach, while particularly focusing on the effect of each exchange, therefore provides a better understanding of how the market is manipulated by the crowd of people in social media platforms.

## Notebook

+ `eda.ipynb`: Explanatory Data Analysis, Data Visualsization
+ `preprocessing.ipynb`: Preprocessing 
+ `regression.ipynb`: Regression model (Bayesian regression model through MCMC sampling)
+ `classification.ipynb`: Classification model (Random Forest, XGBoost, LightGBM)

 ## Dataset 

+ Main dataset is proprietary and derived from [PumpOlymp](https://pumpolymp.com/).  
+ Cryptocurrency data is retrieved from [CoinMarketCap](https://coinmarketcap.com/)


