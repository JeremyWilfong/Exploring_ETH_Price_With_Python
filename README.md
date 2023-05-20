# Exploring Ethereum's Price with Python

**Download the Exploring ETH Price.html to view the code and it's outputs quickly.**

**Purpose**
Practicing Python by exploring the price of Ethereum, a decentralized cryptocurrency.

**Methodology**
1. Manipulate the imported yfinance data(creating new columns) to feed the Machine Learning Model and Scenario Exploration.
2. Explore the data by trying to find certain candle structure scenarios that have an above average chance of being profitable.
3. Create 3 different types of machine learning models, test their accuracy, and try to improve their accuracy.

**Skills Used**
* Python (pandas, sklearn, matplotlib)
* Data Manipulation
* Data Exploration
* Machine Learning
    * Linear Regression
    * Random Forest Classifier
    * XGBoost
* Functions

**Hypotheses**
- For the Machine Learning Models: 
    - The models will be more accurate predicting tomorrow's price direction vs next week's price direction.
    - The Random Forest Model will give us the best accuracy out of all the Machine Learning models.
    - We will be able to train a model with predictors good enough to predict 60% of next day's price.
- For Scenario Exploration: 
    - We will find at least 3 scenarios where price goes up 60% of the time a week after the trade scenario happens. 

**Interesting Results**
- For the Machine Learning Models: 
    - It was more accurate predicting next week's price direction vs tomorrow's for Random Forest and XGBoost, but not for logistic regression.
    - Each Machine Learning Model achieved more than 60% accuracy when predicting just the last 100 days. 
- For Scenario Exploration:
    - We found more than 3 scenarios where the odds of it being profitable a week later were greater than 60%.

***Suggested next steps***
- *Create a profitable trade management model in another Jupyter Notebook using the data we explored.*
- *Create and deploy a bot trading algorithm to trade based on your data in this notebook and in the trade management model*.
- *Create additional predictors for the machine learning model. For example using rolling averages or other technical indicators.*
