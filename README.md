# Profitability-of-Cryptocurrency-Pump-and-Dump-Schemes
Taro Tsuchiya (Keio University Faculty of Economics)

## Abstract

One of the price manipulation schemes achieved by artificially increasing the trading volume of the target asset, Pump \& Dump (P\&D) schemes, has a long history in the stock market and is usually considered unlawful. In cryptocurrency markets, however, this scheme has not been well-regulated and uniquely coordinated through a new type of social media platform such as Telegram. Because there have been few investigations on P\&D schemes in the cryptocurrency market so far, this paper aims to examine P\&D's features organized through Telegram and identify the profitability of these activities. This research forms a regression model in a Bayesian hierarchical framework to clarify variables that contribute to the profitability of P\&D attempts, paying a closer attention to each exchange and Telegram channel. It is revealed that a pump's timing is significant to make the pump successful, while the effect of trading volume significantly differs across exchanges. Furthermore, this paper builds a classification model to detect a successful and unsuccessful pump and achieved more than 75\% accuracy using tree-based ensemble models, given the information before the pump. This paper provides the first detailed analysis of P\&D schemes using a novel statistical approach in a Bayesian framework while particularly focusing on the effect of exchanges and Telegram channels, suggesting a way to avoid malicious pump activities.

## Notebook

+ `eda.ipynb`: Explanatory Data Analysis, Data Visualsization
+ `preprocessing.ipynb`: Preprocessing 
+ `regression.ipynb`: Regression model (Bayesian regression model through MCMC sampling)
+ `classification.ipynb`: Classification model (Random Forest, XGBoost, LightGBM)

 ## Dataset 

Main dataset is proprietary and derived from [PumpOlymp](https://pumpolymp.com/).  

