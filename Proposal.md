# GROUP: *ROBINTRACK*
## **Analysis: Effect of Number of Individual Robinhood Accounts on Stocks & Cryptocurrency**
 


### By Andrew Blemel, Gonzalo Garcia, Jexi Amaris, and Jack Fazzone


### _Questions:_
1. How does the number of individual Robinhood accounts holding a given security affect its price?
2. How does this affect implied volatility?
3. What is the correlation between price and volatility?
4. For which stocks does the effect of Robinhood popularity have the greatest impact, and what insights do this offer on Robinhood's user base?

### _Datasets:_
1. Robintrack
2. Yahoo Finance

### _Roles:_
Jack: Data Collection, Cleaning, Preparation

Jexi: Dashboarding

Gonzalo & Andrew: Data Analysis

### _Tasks (in order):_

1. Data Collection
2. Data Analysis 
    
    A. How does the number of individual Robinhood accounts holding a given security affect the strike price of the underlying? How does this affect implied volatility?

    B. What is the correlation between price and volatility? For which stocks does the effect of Robinhood popularity have the greatest impact, and what insights do this offer on Robinhood's user base?
3. Visualizations & Dashboard Preparation
4. Presentation:
    
    A. **Jack**: Introduction establishing the scope of our project and its current relevance. Outline the sources from which we drew our data and why we chose those sources and the period of time we chose to analyze. 
    
    _What does our project analyze, and why should anyone care about our analysis?_

    **1. Brief familiarization with the "Robinhood Effect" and the scope of our analysis**

      - During the pandemic lockdown, a flood of new traders have entered the market. Many of these new traders chose stock-trading applications like Robinhood, which individually saw an increase of three million funded accounts between January and April, as Forbes reports [1]. According an April SEC filing, Robinhood's Q2 order flow revenue was nearly twice that of Q1 [2][3].

    - Some previous analyses have suggested that this influx of retail trading has appreciably affected portions of the aggregate market, significantly contributing to -- or even leading --  the market's recovery rallies earlier this year [5]. This proposed phenomenon has appropriately been dubbed the "Robinhood Effect."

    - Our analysis will evaluate the extent of the Robinhood Effect on the greater US securities market. Additionally, we will highight patterns in the characteristics of the securities Robinhood investors tend to favor. If these patterns are anomolous within the overall market (or at least recognizably distinct from those of traders using other brokerages), we believe they will provide a more precise determination of _where_ in the market the Robinhood Effect may be more pronounced.

    **2. Explaination of our chosen data sources and analysed time period**

     - We used data beginning in January of this year in order to capture the earliest stages of the economic impact of COVID-19, which is a widely proposed catalyst of the Robinhood Effect [6]. We used the API's offered by Robinhood and Alpaca, as well as Yahoo Finance's website to assemble our historical prices of securities data. To incorporate Robinhood user statistics, we used a website called Robintrack, which kept a daily record of the number individual Robinhood accounts holding different securities until the site shut down in mid-August (which is therefore when our analysis period ends). Robintrack's data up to the point of its shutting down was still available for download.

    - We will begin by examining four stocks, one of which each of us chose from a different sector, and the number of Robinhood users holding those stocks over our analysis period in order to establish a baseline analysis of four semi-randomly chosen securities. We will then move into our analysis of the top 10 most popular securities among Robinhood users, a sample which we believe is fairly representative of the presence of Robinhood users in the aggregate market. We will evaluate the hypothesis of the Robinhood Effect based on the relationships between movements in prices, numbers of accounts holding, and volatilities of the two aforementioned measures for the stocks in this sample.
    
    - Finally, in light of the fact that Robinhood saw the registration of over 1 million new accounts in the days following its announcement of the addition of cryptocurrency trading [7], we will examine the relationship between the number of users on Robinhood and the price of the cryptocurrencies available to trade on the app, namely, Bitcoin and Ethereum.
    
    _**Citations:**_
   

    1, 2 https://www.forbes.com/sites/jeffkauflin/2020/08/03/robinhood-doubles-its-second-quarter-trading-revenue-reaching-180-million/?sh=55395bd9768c

    3 https://cdn.robinhood.com/assets/robinhood/legal/RHS%20SEC%20Rule%20606a%20and%20607%20Disclosure%20Report%20Q2%202020.pdf

    4 https://www.axios.com/robinhood-effect-young-investors-c4acb5e8-ecc3-4d0d-a193-d125fdf075e4.html

    5, 6 https://financhill.com/blog/investing/robinhood-effect-on-stock-market

    7 https://www.investopedia.com/news/robinhood-app-thrives-bitcoin/



    B. **Gonzalo:** How does the number of individual Robinhood accounts affect volatility of our four stocks?
    
    C. **Gonzalo** What are the top ten most popular stocks on Robinhood? How do price and number of Robinhood accounts holding a stock affect each other for these stocks?

    D. **Jexi:** Volatility Rolling Average of Top 10 most popular stocks? 
    
    E. **Andrew:** Does the number of Robinhood users correlate with crypto prices? Stronger correlation between Ethereum than Bitcoin, we speculate that it could be due to lower price and/or higher volatility, like we saw with TSLA.
                
                For volatile stocks, the prices of those stocks tend to have a greater effect on the number of users holding them than the number of users have on the price (TSLA).

                We disproved the Robinhood Effect. There is little connection between the number of users holding a given security and the fundamental value (balance sheet). This leads us to conclude that much of Robinhood trading is based on speculation.

   

    