# Does the sentiment of Reddit articles influence the Dow Jones daily returns?

The goal was to see if there was any predictive power in the top 25 Reddit article's sentiment to the Dow Jones returns or volatility, each day. And how powerful. 


# Data
The data was extracted from Reddit and historical Dow Jones records. Utilizing the Vader sentiment tool, we quantified the sentiment of the Reddit articles per day based on numbers for each category:  Positive, Neutral, Negative.

The RedditNews dataset consisted of 7 years worth of the top 25 news article headlines per day from Reddit's r/news channel. (Date,Title)

The DIJA data set consisted of 8 years worth of daily data from the Dow Jones Industrial Average. (Date, Open, High, Low, Close, Volume, Adj. Close)


# Models
Multiple regression VS. Machine learning

I wanted to see how predictive the two models were, and which was a more powerful predictive model. 
The multiple regression analysis model was run 

 

