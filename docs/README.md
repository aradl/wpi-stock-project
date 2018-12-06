## Making Money from the News

This is a demo-based project which uses a time series dataset of financial market information (stock prices) and a news dataset consisting of information about the sentiment of the news as it relates to the stocks. From this information we will predict stock trends.

This is a competition that is hosted on [Kaggle](https://www.kaggle.com/c/two-sigma-financial-news).

### Goals

The goal of our project is to explore the use of [Ensemble Methods](https://en.wikipedia.org/wiki/Ensemble_learning) with the intricacies of time series data.

### Corpus collection

The data is stored and retrieved as Pandas dataframes in the Kernels environment. Prediction of future stock price returns based on two sources of data:
Market data (2007 to present)- contains financial market information such as opening price, closing price, trading volume, calculated returns, etc.
News data (2007 to present) - contains information about news articles/alerts published about assets, such as article details, sentiment, and other commentary. 
Details of the data can be found here: https://www.kaggle.com/c/two-sigma-financial-news/data

### Big Question

The big question here is simply; how well will this work? The stock market is a tricky [random process](https://www.quora.com/How-are-stochastic-processes-represented-in-the-stock-market) making its behavior difficult to predict. What is easier to predict is how people will react to the news related to a particular stock. This process is typically done by humans and here we seek to find a way to automate it and it is no easy feat.

### Code Breakdown

Looking through the src/ folder located in this repository you will see four python notebooks:
1. Analytical model - finds the relation between the market data and the target
2. News model - finds the relation between the news and the target value
3. Relation model - finds the relation between the news and the market
4. Ensemble model - a combination of the above three

### Implementation Results

To see the latest results please visit the [Ensemble Kernel](https://www.kaggle.com/aradlbeck/vote-lrnews-lgball-anasvc) hosted on Kaggle

### Other Results

Please see the PowerPoint report provided in the docs sections

### Take Away

In this project we looked at many different aspects of the stock market and attempted to take everything we learned and apply it in one project. Overall we have discovered the power of ensemble methods and the difficulty in working with large datasets. They can be flawed, misleading and incomplete.

### About the Team
- [Andrew](https://www.linkedin.com/in/andrew-radlbeck-21140838/) (aradl)
- [Yang](https://www.linkedin.com/in/alexfuyang) (ilovemanu)
- Ankit
- Meghana

