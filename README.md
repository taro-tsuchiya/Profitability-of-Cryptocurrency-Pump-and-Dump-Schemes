# Profitability of cryptocurrency Pump and Dump schemes
Taro Tsuchiya (Keio University)

This paper is published in the Journal of Digital Finance (Springer). The paper can be accessed from [here](https://link.springer.com/article/10.1007/s42521-021-00034-6). 

Springer Nature SharedIt kindly provides the publicly accessible view-only (full text) article through this [link](https://rdcu.be/cvXX0) (as of August 23rd, 2021). 

## Abstract

One of the price manipulation schemes achieved by artificially increasing the trading volume of the target asset, Pump & Dump (P&D) schemes, has a long history in the stock market and is usually considered unlawful. In cryptocurrency markets, however, this scheme has not been well-regulated and uniquely orchestrated through a new type of social media platform such as Telegram. Because there have been few investigations on P\&D schemes in the cryptocurrency market so far, this paper aims to identify the features of P\&D organized through Telegram and examine the market resilience to these activities. This research forms a regression model in a Bayesian hierarchical framework to clarify variables that contribute to the profitability (i.e., price hike) of P\&D attempts. It is revealed that the price resilience to these activities significantly differs across each exchange market. Particularly, Yobit and Cryptopia are more sensitive to the increase in the trading volume than Binance and Bittrex while controlling other significant factors such as the timing of the pump (hourly, yearly), currency, and Telegram channel. Furthermore, this paper builds a machine learning model to identify the price hypes (successful schemes) given the information before the pump activity and achieved more than 75% accuracy using tree-based ensemble models. The contribution of this paper is to provide a detailed analysis of P&D schemes using a novel statistical approach, while particularly focusing on the effect of each exchange, therefore provides a better understanding of how the market is manipulated by the crowd of people in social media platforms.

## Notebook
These notebooks are mainly to illustrate how I get the results of the paper. The main dataset is proprietary and not included in this repository.

+ `eda.ipynb`: Explanatory Data Analysis, Data Visualization
+ `preprocessing.ipynb`: Preprocessing of the data
+ `regression.ipynb`: Regression model (Bayesian regression model through MCMC sampling)
+ `classification.ipynb`: Classification model (Random Forest, XGBoost, LightGBM)

Some of the outputs (especially, the tables) in the notebook may look different when you open them on your browser. I highly recommend to look them on your local environment.

 ## Dataset

+ Main dataset is proprietary and derived from [PumpOlymp](https://pumpolymp.com/).  
+ Cryptocurrency data is retrieved from [CoinMarketCap](https://coinmarketcap.com/)

## Citation (example)

+ Plain text

```
Tsuchiya, T. Profitability of cryptocurrency Pump and Dump schemes. Digit Finance (2021). https://doi.org/10.1007/s42521-021-00034-6
```

+ BibTeX

```
@article{tsuchiya2021profitability,
  title={Profitability of cryptocurrency Pump and Dump schemes},
  author={Tsuchiya, Taro},
  journal={Digital Finance},
  pages={149–167},
  year={2021},
  publisher={Springer},
  doi={https://doi.org/10.1007/s42521-021-00034-6}
}
```

## Acknowledgement

I sincerely thank Professor Teruo Nakatsuma and the many relevant members at Keio University Faculty of Economics, as well as Professor David Farber at Cyber Civilization Research Center for their advice on the article. I also greatly appreciate the continued feedback from the editors and the reviewers in the Journal of Digital Finance (Springer) upon each submission. These were extremely helpful and critical to refining my article. 

Any inquiry should be sent to the author's email taro.f.tsuchiya\<at\>keio.jp
