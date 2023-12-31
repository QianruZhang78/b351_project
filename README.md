# csci-b351-project

Author: HanQing Wei, Qianru Zhang, Zhong Zhang

Abstract:
In the era of big data, various mathematical and engineering techniques have been utilized in solving financial problems. In the realm of quantitative finance, volatility estimation plays an essential role in predicting future stock prices. In this research, we aim to evaluate the effectiveness of using Machine Learning and Deep Learning models in predicting stock volatility of an organization. We collected 20 years of 5 different stock prices and selected key financial indicators as our training dataset. Three algorithms were selected and implemented after a comprehensive review of AI models. The output of each algorithm is a boolean variable indicating whether the stock return in the next 5 days will be more volatile than the previous 5 days. The presumption of this methodology design is that past stock price and indexes are good indicators to predict future price volatility. Our results were not very optimistic as accuracy rates were much lower than our expectation. It is evident that the Efficient Market Hypothesis cannot be disproven statistically significantly. Another finding is that deep learning algorithms prove to be a better model than conventional machine learning models. 

This repository contains 5 data sets, 1 program for dataset formulation, and 3 algorithm implementations.
The data sets we are using including AAPL, AMZN, FB, Googl, and NFLX, where they are formed by the program we included in Volatility Forecast Dataset file. Then we have the implementations for SVM, DeepLearning, and Random Forest, where we have created two version of random forest implementations, one is developed by hand, and the other was developed using third party tool sklearn.
