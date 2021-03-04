## FinTech • Unit 4 • Pandas & NumPy
#### Columbia University • Fu Foundation School of Engineering & Applied Science
##### Contributor:  Lisa Esberger
##### Published:  March 1, 2021

### A Whale off the Port(folio)

#### Quantitative Analysis 
##### Performance Analysis (Cumulative Returns)
* *Do any of the portfolios outperform the S&P 500 (38.56%) from 3/3/2015 to 4/23/2019?*
  * Soros Fund Management LLC: 16.46%
  * Paulson & Co Inc: -22.04%
  * Tiger Global Management LLC: -13.88%
  * Berkshire Hathaway Inc: 55.34%
  * Algo 1: 93.47%
  * Algo 2: 26.92%
* *Berkshire Hathaway Inc and Algo 1 outperformed the S&P 500 during this period.*
![Cumulative-Returns](https://github.com/1monalisa1/04-Pandas-NumPy/blob/05e5c55e528ba606a2284fad5fa4cbe869a551e4/Resources/04-Cumulative-Returns.png)

##### Risk Analysis (Standard Deviation)
* *Which portfolios are riskier than the S&P 500 (0.008554)?*
  * Soros Fund Management LLC: 0.007895
  * Paulson & Co Inc: 0.007023
  * Tiger Global Management LLC: 0.010894
  * Berkshire Hathaway Inc: 0.012919
  * Algo 1: 0.007620
  * Algo 2: 0.008342
* *Berkshire Hathaway Inc and Tiger Global Management LLC had been riskier than the S&P 500.*
![Standard-Deviation](https://github.com/1monalisa1/04-Pandas-NumPy/blob/d34c63dd5074812253a7c8c0969aa5340bf745cb/Resources/04-Standard-Deviation.png)

##### Risk-to-Return (Sharpe Ratio)
* *Does either of the algorithmic strategies outperform the "whales" or S&P 500?*
  * Soros Fund Management LLC: 0.178680
  * Paulson & Co Inc: -0.214392
  * Tiger Global Management LLC: -0.044777
  * Berkshire Hathaway Inc: 0.283963
  * S&P 500: 0.295976
  ------------------------------------------------
  * Algo 1: 0.546686
  * Algo 2: 0.206491
* *Algorithmic Strategy 1 outperformed all 4 whales and the S&P 500, for its risk adjusted return is the greatest*
![Sharpe Ratio](https://github.com/1monalisa1/04-Pandas-NumPy/blob/3775097a0fada12672d48a45e5fe426a9f4c928c/Resources/04-Sharpe-Ratio.png)

### Grocery Store Portfolio Returns
* *25% Target (TGT) • 25% Walmart (WMT) • 25% Kroger (KR) • 25% Albertsons (ACI)*
* *Benchmark: S&P 60 TSX (TX60)

##### Asset Correlation  
  * All grocery stocks were positively correlated; some more than others:
 ![Correlation](https://github.com/1monalisa1/04-Pandas-NumPy/blob/324c4974042733c973e9a7ab5c7f91fd08a6e27b/Resources/04-Correlation.png)
 
##### Risk (Standard Deviation)
  * Grocery Store Portfolio: 0.011039
    * Target:  0.016184
    * Walmart: 0.014167
    * Kroger: 0.015290
    * Albertsons: 0.018980
* *The Grocery Store Portfolio during 2020 is quite risky and is closest to the level of risk experienced by Tiger Global Management LLC during its earlier time period. This likely has to do with the heightened volatility in the market overall in 2020, so additional analysis would need to be done for a true 'apples-to-apples' comparison*
![Grocery-sd](https://github.com/1monalisa1/04-Pandas-NumPy/blob/2d8a56826e9b3e08dd358d6d34fc4414373d5b46/Resources/04-Grocery-sd.png)

##### Risk-to-Return (Sharpe Ratio)
  * Grocery Store Portfolio: 0.125176
    * Target:  0.197725
    * Walmart: 0.115167
    * Kroger: -0.010188
    * Albertsons: 0.125176

![Grocery-Sharpe](https://github.com/1monalisa1/04-Pandas-NumPy/blob/df5c57c9190c4ac9845f6d2045f1a588a8ef7dab/Resources/04-Grocery-Sharpe.png)




