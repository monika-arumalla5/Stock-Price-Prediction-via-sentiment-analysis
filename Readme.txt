Assumptions: 
Please ensure that your computer has PySPark (spark-3.1.1-bin-hadoop2.7) installed. Additionally, you need to install Mongo DB, PyMongo, Tweepy, Jupyter Notebook for this project.

Below are the steps that should be followed for the execution of the project:

1] Create a Twitter developer account and create an application. Then, store the access token, access key, consumer key and consumer secret in a secure location.

2] Create a MongoDB in local computer and create a stock_tweets db. Then, open another terminal and start the Mongo DB.

3] Then, add the Twitter access details to the Collect_Tweets.ipynb jupyter notebook and execute the notebook step by step. Now, the Tweets for the stocks under study are collected and stored in MongoDB. Please note that the data collected during the period March 12 - May 5, 2021 has been provided as a csv file.

4] To create a Sentiment Analyser to classify a Tweet as positive or negative, run the Sentiment_Analyzer.ipynb jupyter notebook. Additionally, the same model is provided as Sentiment_Analyzer.model.

5] Create an account with eodhistoricaldata.com and store the api key.

6] Once the tweets are collected, execute the Analysis_of_stock_tweet_sentiments_and_forecasting_stock_price.ipynb step by step. Then, it will create the model that predicts the stock price for each stock considered for this study.

