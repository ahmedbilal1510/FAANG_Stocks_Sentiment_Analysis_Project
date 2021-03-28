# FAANG_Stocks_Sentiment_Analysis_Project
This project will allow us to conduct sentimental analysis of stocks (I have chosen FAANG stocks) from Financial news using Finviz.com
Following are the steps I have taken to do the project:
1. Retreive the html data from Finviz.com using BeautifulSoup
2. Parce the data we got from BeautifulSoup to get the data that we need (ticker, date, time, title) and make it readable
3. Applying the data to a Pandas dataframe and calculating the sentiment analysis of the titles of articles using nltk's vader_lexicon (Vader sentiment analysis).
4. Visualize the dataset in a barchart like format to see the highlights of the sentiment of FAANG stocks over the past few days

The following is the result of this project:
![Python FAANG Sentiment analysis project](https://user-images.githubusercontent.com/56721456/112744434-02a66080-8fdb-11eb-83b3-3a72c3070e26.png)
