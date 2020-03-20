# Dow Jones Project from Reddit sentiment

I wanted to see if there was any predictive power in the top 25 Reddit article's sentiment to the Dow Jones returns or volatility, each day. 



I used two data sets, "RedditNews" and "DIJA".

The RedditNews dataset consisted of 7 years worth of the top 25 news article headlines per day from Reddit's r/news channel. (Date,Title)

The DIJA data set consisted of 8 years worth of daily data from the Dow Jones Industrial Average. (Date, Open, High, Low, Close, Volume, Adj. Close)



Utilizing the Vader sentiment tool, we quantified the sentiment of the articles per day based on numbers for each category:  Positive, Neutral, Negative.



I created a multiple regression analysis model of the Dow Jones returns and volatility, as compared to the sentiment measured through the Vader Sentiment tool, of the top 25 articles on Reddit each day.  I found that the aggregate sentiment of the top 25 Reddit articles has no influence on the outcomes and volatility of the Dow Jones, for that particular day.

 

