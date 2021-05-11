
# DeepPSX: Prediction and Simulation of PSX using Deep Learning, Sentimental and Technical Analysis

## 1. Introduction 

### 1.1 Problem Statement
The aspiration of any investor is to forecast the market behavior aiming the best
decision when it comes to buying or selling shares of stocks seeking to maximize
his profits. However, Efficient Market Hypothesis (EMH) is a back-breaker for
forecasters. In its crudest form, it effectively says that the returns from speculative
assets are unforecastable. On the contrary, according to John J.Murphy, ’traders
collectively repeat the behaviour of the traders that preceded them. We define
our problem to test the Efficient Market Hypothesis on Pakistan Stock Exchange
(PSX), to see if stock prices move only on new information and cannot be predicted
or are there some underlying patterns which can be observed in order to help in
forecasting.

### 1.2 Proposed Solution
Stock prediction has been a significant field of interest for mathematicians and specifically financial analysts over the period of time. People invest their hard earned
savings into stocks to gain profit but it has always come with significant risk. Layman entrust their investment with securities which makes them responsible to invest
strategically eliminating maximum risks. A satisfactory prediction mechanism may
not be able to provide perfect forecasts but at least meaningful insights. However,
results show that no method alone has achieved the desired success. In 2019, Gozde
Sismanoglu [3] suggested a system which is trained with some learning mechanism
incorporating a large variety of features for automating stock forecasting. Unlike
other countries, the market in Pakistan is still reluctant in adapting newer strategies
based upon models built using machine learning architectures to make predictions.
In Pakistan, stock prediction is currently done entirely on fundamental or technical analysis using financial modelling. Majority brokers or investors focus on specific
trading strategies based on technical indicators and personal comprehension of news
and announcements. This creates an investor bias and collective investor behaviour
which results in less meaningful predictions. AKD Securities is the biggest brokerage
of Pakistan which is actively adapting to digitisation and automation. They want
to extend their research in the field of Stock Forecasting using Artificial Intelligence
and Data Science. Data Science techniques and Deep Learning models are being
used globally to make predictions on stock market behaviour while the practice is
still uncommon in Pakistan. This project aims for a hybrid approach for prediction
incorporating historic data, daily news analysis, statistical analysis to see whether
Data Science techniques using Machine Learning models can predict trends in a
volatile market like Pakistan.

# Scope and Deliverables

This complete project is divided into five main modules shown below:

![image](https://user-images.githubusercontent.com/36048849/117360020-b4398b00-aed1-11eb-97fa-b2daa7a559cb.png)

## Module 1: Stock price prediction based on historical data in time series format using modern recurrent neural networks.
- Inputs: Historical prices of an individual stock in the form of daily open, close, high and low.
- Output: Numerical values estimating the open, close, high and low for the next day.

![Mod1](https://user-images.githubusercontent.com/36048849/117360537-5b1e2700-aed2-11eb-8c26-2039e887666e.png)


## Module 2: Polarity prediction of news/announcements (good/bad) using sentiment analysis and natural language processing.
- Inputs: News converted into vectors indicating investor sentiments.
- Output: Probability of the stock price to go either up or down based on investor sentiments

![Mod 2](https://user-images.githubusercontent.com/36048849/117360570-65d8bc00-aed2-11eb-83b2-954c1c47d6e4.png)


## Module 3: Generation of buy/sell signals on daily basis using data from first two modules and technical indicators along with simulation and reporting.
- Inputs: Outputs from the previous two models for a given day along with other factors such as technical indicators and global oil prices and Forex rates.
- Output: Signals to either buy or sell a commodity the next day. An extended simulator to take
decisions using this model and verify results. Lastly, generation of user friendly reports to take informed decisions.

![Mod 3](https://user-images.githubusercontent.com/36048849/117360634-77ba5f00-aed2-11eb-85bb-3a149bc76cff.png)

## Module 4: Trading Simulator is back-testing framework on our proposed hybrid solution.

- Input: Outputs from module 1 & 3 
- Output: Profit/loss made. 

![mod4](https://user-images.githubusercontent.com/36048849/117360748-97ea1e00-aed2-11eb-8135-38dd130cd3a2.png)

## Module 5: Displaying results on a dashboard

- Input: Outputs from module 1, 2 & 3.

- Output: Module 5 would be a dashboard intended for the securities indicating which equities should be bought, sold or held on a particular day with different infographics and charts so that the investor can make an informed decision every day. 

![mod5](https://user-images.githubusercontent.com/36048849/117360804-a7696700-aed2-11eb-8135-d15913f3607f.png)

# Final Product

![image](https://user-images.githubusercontent.com/36048849/117362367-9a4d7780-aed4-11eb-86d7-912eac20ed43.png)

https://deeppsx.netlify.app/
