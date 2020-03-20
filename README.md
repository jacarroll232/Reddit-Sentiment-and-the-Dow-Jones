# Dow Jones Project from Reddit sentiment

About this project

Data

For our project we used two data sets, "RedditNews" and "DIJA".

The RedditNews dataset consisted of 7 years worth of the top 25 news article headlines per day from Reddit's r/news channel. (Date,Title)

The DIJA data set consisted of 8 years worth of daily data from the Dow Jones Industrial Average. (Date, Open, High, Low, Close, Volume, Adj. Close)


The models

Our first model is a multiple regression analysis of the Dow Jones returns and volatility, as compared to the sentiment measured through the Vader Sentiment tool, of the top 25 articles on Reddit each day. We found that the aggregate sentiment of the top 25 Reddit articles has no influence on the outcomes and volatility of the Dow Jones, for that particular day.

The goal of the analyses is to predict Dow-Jones daily return and volatility with the daily top 25 Reddit article headlines. X variables used are the daily frequency of the words appeared in the article headlines (7000 words/ combinations in total). The method applied in general is Lasso. The first attempts were to use SkLearn Lasso default settings. Second attempts were to apply cross validation to tune the best model. Findings: the words have very limited prediction power on both return and volatility, with a better result found in volatility prediction. However, the top words that contributed to the predictions do make intuitive sense, both for return and volatility.





