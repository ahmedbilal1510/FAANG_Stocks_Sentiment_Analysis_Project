# FAANG_Stocks_Sentiment_Analysis_Project
This project will allow us to conduct sentimental analysis of stocks (I have chosen FAANG stocks) from Financial news using Finviz.com.

The following are the steps I have taken during this project:
1. Retreive the html data from Finviz.com using BeautifulSoup
2. Parce the data we got from BeautifulSoup to get the data that we need (ticker, date, time, title) and make it readable
3. Applying the data to a Pandas dataframe and calculating the sentiment analysis of the titles of articles using nltk's vader_lexicon (Vader sentiment analysis).
4. Visualize the dataset in a barchart like format to see the highlights of the sentiment of FAANG stocks over the past few days


The following are the results of this project:

The positive figures show average positive sentiment and the negative figures show average negative sentiment for the day. Some data for some stocks is missing as there was not enough news for those stocks on those days.
