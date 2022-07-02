# **GuruStock**

## Introduction
----------------
Stock Prices prediction using sentiment analysis of tweets from [Twitter](https://twitter.com/home) (Using Tweepy module) regarding the stock of the particular company, along with a comparative study of the predictions made using different ML/DL models.
The models used for predictions of the stocks, whose data is web scraped from [Yahoo Finance](https://finance.yahoo.com/) using the module yfinance are [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html), [Random Forest Regressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html?highlight=random%20forest%20regressor#sklearn.ensemble.RandomForestRegressor) and [LSTM](https://www.tutorialspoint.com/time_series/time_series_lstm_model.htm#:~:text=It%20is%20special%20kind%20of,layers%20interacting%20with%20each%20other.) - [TLBO](https://medium.com/analytics-vidhya/what-is-teaching-learning-based-optimization-tlbo-algorithm-b368098339e8) neural network based models.
The project has been made using [Python 3.10](https://www.python.org/downloads/release/python-390/) on [Jupyter Notebook](https://jupyter.org/) using the [Anaconda Navigator](https://docs.anaconda.com/anaconda/navigator/). Although the optimisation of the LSTM model is yet to be performed using TLBO as the procedure for linking of the results of the two is not available on any platform and in the near future after further research, the suitable changes will be made in the code to fulfill the same.


## Modules Used
---------------
* [TextBlob](https://textblob.readthedocs.io/en/dev/)
* [Tweepy](https://docs.tweepy.org/en/stable/)
* [OS](https://docs.python.org/3/library/os.html)
* [Sys](https://docs.python.org/3/library/sys.html?highlight=sys#module-sys)
* [Pandas](https://pandas.pydata.org/docs/getting_started/overview.html)
* [Numpy](https://numpy.org/doc/stable/user/whatisnumpy.html)
* [Math](https://docs.python.org/3/library/math.html)
* [Matplotlib](https://matplotlib.org/)
* [Yfinance](https://pypi.org/project/yfinance/)
* [Sklearn](https://scikit-learn.org/stable/)
* [Tensorflow](https://www.tensorflow.org/learn)
* [Keras](https://keras.io/)
* [Mealpy](https://pypi.org/project/mealpy/)

## Prerequisites
----------------
* A developer account on [Twitter Developers](https://developer.twitter.com/en/portal/dashboard) to get the keys and ID for authentication and using the Twitter API. Secondly, apply for the [elevated access](https://developer.twitter.com/en/portal/products/elevated) on the portal for the particular project.
* Install all the modules required.

#### THE UPDATES WILL BE MADE AS SOON AS POSSIBLE
----------------
