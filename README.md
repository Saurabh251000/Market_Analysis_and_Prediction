# Market Analysis and Prediction

This is my self projest , I have intrest in Share Market and Data  Analytics so I choose this project , I think this project is best beacause of I explore in both feild.
I choose india's most valuable companies for analysis and prediction . Companies are
* **Reliance** : Most valuable companies in Oil & Gas
* **TCS (Tata Consultancy Service)** : Most valuable in IT service
* **SBIN (State Bank of India)** : Most Valuable Banking Brand
* **Hindustan Unilever** : One of India's top fast-moving consumer goods (FMCG) company

>Prediction of stocks is difficult and complex because it depends on various factors like market inflation, gdp, govvt. Policies and company performance.
So in this model predicted stocks taking the factor of closing price.

I can divide the whole project in three parts
* Data Scrapping
* Market Analysis
* Market Production

**1 :Data Scraping :** Extract the data from **Yahoo Finance**
* Use 1 year historical data for Market Analysis Puspose
* Use 5 year historical data for Market Prediction

Store the data in **Pandas Dataframe.**

**2 :Market Analysis**
* Plotting the Closing Price of each company
*  Plotting the Volume of Sales
*  Plot 10 days, 20 days, 30 days Moving Average of Stocks
*  Plot percentage of **Daily Return** of the shares
*  Plot Correlation between stocks closing price 
*  Risk Analysis : Calculate coefficient of variabilty (risk/reward)

**3 :Market Prediction**
* Get data from yahoo finance
* Scaling the Dataset
* Divide into train and test data
* Creating Train dataset
* Train LSTM model
* Test the Model
* Plot the prediction value

> [!NOTE]
>**LSTM Model :** A time series forcast method  to predict the value. This model used sigmoid activation function for the scaling of data and we minimised the errors using loss function that is mean square error. We used lstm because it is a better version of rnn (recurrent neural network). It assigns some weightage to the important and not important data. It also assigns some weightage to some important older data or insight that might be very useful in the future. This thing cant be done in RNN model. RNN model gives more weightage to the recent data. RNN has Gradient vanishing problem.
>* LSTM model using keras import library.

> [!NOTE]
>**Data Scalling :** 

