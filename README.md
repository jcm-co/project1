# Project 1

![FIRE_analysis.png](images/FIRE_analysis.PNG)

## Summary
____
James is keen to retire early, based on the FIRE principle. He’d like to assess based on his age, savings and lifestyle what that would look like. Unfortunately, James will have to work a long time to reach Financially Independent Retire Early status. 

A wise person suggests James to invest on the stock exchange, to speed up the process. James would like to see some proof of what that would look like. A brilliant tool is shown to James, which has  10, 20 and 30 year return simulations including risk assessment. 

James, is also thinking that if he could save a bit of money on cost living, he would end up with more and having a good retirement life. So for that, James would like to analysis the cost living expenses in different countries and see if he better off moving into another country.


## Questions:

1. What does James his personal financial situation looks like? 
2. Does he have a chance of achieving FIRE status? 
3. What would be the impact of compounded investments? 
4. The hypothesis supports that investing would be a wise decision. What investment strategy would we recommend for James based on investment duration (10y / 20y / 30y). 
5. What is the risk on these investment? 
6. What would be an alternative investment strategy for retirement plan?
7. If James would relocate, given the savings he would have at the time of what would be a an interesting location for James?
8. Are there other factors that influence where to move to? 

## Data:

### - FIRE Calculator
* In this section the tool gathers information from the end user, to make a FIRE assessment  

### - Market Analysis & Retirement Tool Data: 
We used yfinance to fetch historical data of 5 major Indexes market. We used then https://au.finance.yahoo.com/ and collected the data history of S&P500, NASDAQ Composite, S&P/ASX 200, Dow Jones Commodity & BTC.

### Indexes:

1. S&P500 (GSPC). 
2. NASDAQ Composite (IXIC). 
3. S&P/ASX 200 (ASX). 
4. DJCI (Dow Jones Commodity)
5. BTC.


### - Cost of living analysis Data:  (Raj) 


## Analysis
___

### - FIRE Calculator:
* The calculator creates a DF with simulations on how the road to FIRE status could be shortened
* The calculator assesses the impact of investing vs. the duration to get to FIRE status

#### Current Path to FIRE:
![Current Path to FIRE](images/Current_Path_to_FIRE.PNG)

#### FIRE Path if invested:

![FIRE Path if invested](images/FIRE_Path_if_invested.PNG)

#### Suggested FIRE path:
![Suggested FIRE path](images/Suggested_FIRE_path.PNG)


### - Market Analysis: 

#### We have analysed these major indexes to determine their performance in multiple areas: volatility, returns, risk, and Sharpe ratios 

#### Initial Data:

![Initial_Data.png](images/Initial_Data.PNG)

#### Daily Returns: 

![Daily_Returns.png](images/Daily_Returns.PNG)

#### Cumulative Returns:
![Cumulative_Returns.png](images/Cumulative_Returns.PNG)

#### Risk Analysis -> Standard Deviation:
![Std.png](images/Std.PNG)

#### Sharpe Ratios:
![Sharpe_Ratios.png](images/Sharpe_Ratios.PNG)

### Retirement Plan Tool Analysis:

#### We have used Monte Carlo simulations to project our 5 Indexes Market in 10-, 20- & 30-years.

#### Then, we analysed the statistics from the simulated daily returns in 10-, 20- & 30-years to determine the returns based on an innitial investment of $20,000 and annual investment of $10,000.


![Simulated_Statistics_Returns10.png](images/Simulated_Statistics_Returns10.PNG)
![Simulated_Statistics_Returns20.png](images/Simulated_Statistics_Returns20.PNG)
![Simulated_Statistics_Returns30.png](images/Simulated_Statistics_Returns30.PNG)

### Final Returns:
![Final_Returns.png](images/Final_Returns.PNG)

![Proyected_Portfolio_Returns.png](images/Proyected_Portfolio_Returns.PNG)



## Cost of Living Analysis:
___


