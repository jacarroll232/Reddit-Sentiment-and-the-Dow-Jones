# Does the sentiment of Reddit articles influence the Dow Jones daily returns?

The goal was to see if there was any predictive power in the top 25 Reddit article's sentiment to the Dow Jones returns or volatility, each day. And how powerful. 


# Data
The data was extracted from Reddit and historical Dow Jones records. Utilizing the Vader sentiment tool, we quantified the sentiment of the Reddit articles per day based on numbers for each category:  Positive, Neutral, Negative.

The RedditNews dataset consisted of 7 years worth of the top 25 news article headlines per day from Reddit's r/news channel. (Date,Title)

The DIJA data set consisted of 8 years worth of daily data from the Dow Jones Industrial Average. (Date, Open, High, Low, Close, Volume, Adj. Close)

# Vader Sentiment

![pic](https://github.com/jacarroll232/Reddit-Sentiment-and-the-Dow-Jones/blob/master/Vadersentiment.PNG)

# Models
Multiple regression VS. Machine learning

I wanted to see how predictive the two models were, and which was a more powerful predictive model. 
Both models returned the same result.  There was no predictive value in the sentiment of the articles and the Dow Jones returns.

 

