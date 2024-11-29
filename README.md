# Market Analysis and Prediction :closed_book:

This is my self projest , I have intrest in Share Market and Data  Analytics so I choose this project , I think this project is best beacause of I explore in both feild.
I choose india's most valuable companies for analysis and prediction . Companies are
* **Reliance** : Most valuable companies in Oil & Gas
* **TCS (Tata Consultancy Service)** : Most valuable in IT service
* **SBIN (State Bank of India)** : Most Valuable Banking Brand
* **Hindustan Unilever** : One of India's top fast-moving consumer goods (FMCG) company

>Prediction of stocks is difficult and complex because it depends on various factors like market inflation, gdp, govvt. Policies and company performance.
So in this model predicted stocks taking the factor of closing price.

I can divide the whole project in three parts
* Data Scrapping :page_with_curl:
* Market Analysis :computer:
* Market Prediction :chart_with_downwards_trend:

**1 :Data Scraping :** Extract the data from **Yahoo Finance**
* Use 1 year historical data for Market Analysis Purpose
* Use 5 year historical data for Market Prediction

Store the data in **Pandas Dataframe.**

**2 :Market Analysis**
* Plotting the Closing Price of each company :chart_with_upwards_trend:
*  Plotting the Volume of Sales :chart_with_upwards_trend:
*  Plot 10 days, 20 days, 30 days Moving Average of Stocks :chart_with_upwards_trend:
*  Plot percentage of **Daily Return** of the shares :chart:
*  Plot Correlation between stocks closing price :chart_with_upwards_trend:
*  Risk Analysis : Calculate coefficient of variabilty (risk/reward) :chart:

**3 :Market Prediction**
* Get data from yahoo finance
* Scaling the Dataset
* Divide into train and test data
* Creating Train dataset
* Train LSTM model
* Test the Model
* Plot the prediction value

> [!TIP]
>**LSTM Model :** A time series forcast method  to predict the value. This model used sigmoid activation function for the scaling of data and we minimised the errors using loss function that is mean square error. We used lstm because it is a better version of rnn (recurrent neural network). It assigns some weightage to the important and not important data. It also assigns some weightage to some important older data or insight that might be very useful in the future. This thing cant be done in RNN model. RNN model gives more weightage to the recent data. RNN has Gradient vanishing problem.
>* LSTM model using keras import library.

> [!IMPORTANT]
>**Data Scalling :** In dataset has datapoints far from each other, Scaling is a technique to mske them Closer to each other, SO ML model easily understand and interprete the data.
* Standard Scaler :  Follow Normal Distribution.
* MinMax Scaler : Substract minimum value from each value and divide by range of data. It converts range [0-1]

<a href="https://www.github.com/Saurabh251000" target="_blank" rel="noreferrer"><img src="https://img.freepik.com/premium-vector/stock-market-graph-forex-trading-chart-business-financial-concepts-abstract-finance-background-investment-economic-trends-business-idea-stock-market-data_208588-149.jpg?w=900" /></a> 


### Contact Me

<p align="left">
    <a href="https://www.github.com/Saurabh251000" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=github" width="32" height="32" /></a> 
    <a href="https://www.instagram.com/_restart__art/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=instagram" width="32" height="32" /></a>
    <a href="https://www.linkedin.com/in/saurabh-kushwaha-064017212/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=linkedin" width="32" height="32" /></a>
    <a href="https://www.instagram.com/saurabh_25100/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=instagram" width="32" height="32" /></a>
    <a href="https://twitter.com/i/flow/login?redirect_after_login=%2FSaurabh25100" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=twitter" width="32" height="32" /></a>
</p>


