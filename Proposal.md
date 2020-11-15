# GROUP: *ROBINTRACK*
## **Analysis: Effect of Number of Individual Robinhood Accounts on Stocks & Cryptocurrency**
 


### By Andrew Blemel, Gonzalo Garcia, Jexi Amaris, and Jack Fazzone


### _Questions:_
1. How does the number of individual Robinhood accounts holding a given security affect its price?
2. How does this affect volatility?
3. What is the correlation between number of holders volatility and price volatility?
4. For which stocks does the effect of Robinhood popularity have the greatest impact, or other relationship, and what insights do this offer on Robinhood's user base?
5. Is there a strong correlation between the number of Robinhood accounts and the price of the cryptocurrencies available for trade on Robinhood?

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
    
    A. How does the number of individual Robinhood accounts holding a given security affect its price? How does this affect volatility?

    B. What is the correlation between price and volatility? For which stocks does the effect of Robinhood popularity have the greatest impact, and what insights do this offer on Robinhood's user base?
3. Visualizations & Dashboard Preparation
4. Presentation:
    
    A. **Jack**: Introduction establishing the scope of our project and its current relevance. Outline the sources from which we drew our data and why we chose those sources and the period of time we chose to analyze. 

    ## _Introduction_
- The economic retraction and uncertainty which accompanied the pandemic lockdown has lent itself to rapid growth in FinTech companies which afford clients greater control over personal finances. For instance, personal portfolio management has grown significantly, to the benefit of stock-trading applications like Robinhood, which saw an increase of three million funded accounts between January and April, as Forbes reports [1]. According to its Q2 SEC regulatory filing, Robinhood's monthly order flow revenue largely trended upward throughout the quarter, which totaled nearly twice that of Q1 [2][3].

- Previous analyses have suggested that this surge in personal trading has significantly affected portions of the aggregate market and perhaps leading the market's recovery rallies earlier this year [5]. This proposed phenomenon has appropriately been dubbed the "Robinhood Effect."

- Our analysis will evaluate the extent of the Robinhood Effect on the greater US securities market. Additionally, we will highight patterns in the characteristics of the securities Robinhood investors tend to favor, which we believe  will provide a more precise determination of _where_ in the market the Robinhood Effect may be more pronounced.

## _Selection of Data and Period of Analysis_
 - Our analysis begins in January of this year in order to capture the earliest upticks in user growth in companies like Robinhood [6]. We used the API's offered by Robinhood and Alpaca, as well as Yahoo Finance's website to assemble our historical securities prices data. To incorporate Robinhood user statistics, we used a website called Robintrack, which published a daily record of the number individual Robinhood accounts holding different securities until the site shut down in mid-August (which is therefore when our analysis period ends). Robintrack's data up to the point of shutting down was still available for download.

- We will begin by examining four stocks, one of which each of us chose from a different sector, and the number of Robinhood users holding those stocks over our analysis period in order to establish a baseline analysis of four semi-randomly chosen securities. We will then move into our analysis of the top 10 most popular securities among Robinhood users, a sample which we believe is fairly representative of the greatest presence of Robinhood users in the aggregate market. We will evaluate the hypothesis of the Robinhood Effect based on the relationships between movements in prices, numbers of accounts holding, and volatilities of the two aforementioned values for the stocks in this sample.
    
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
    
    E. **Andrew:** Does the number of Robinhood users correlate with crypto prices? 
        
        Stronger correlation between Ethereum than Bitcoin, we speculate that it could be due to lower price and/or higher volatility, like we saw with TSLA. speaking of Elon Musk, We noticied an odd spike in the cryptocurrency Dogecoin
                
                For volatile stocks like TSLA, the prices tend to have a greater effect on the number of users holding them than the number of users have on the price (TSLA). we found that the number of users holding TSLA would sharply increase shortly after the increase in price

                We believe we disproved the Robinhood Effect. There is little connection between the number of users holding a given security and the fundamental value (balance sheet). This leads us to conclude that much of Robinhood trading is based on speculation, and that trading on robinhood in general has little to no effect on the markets.

   

    