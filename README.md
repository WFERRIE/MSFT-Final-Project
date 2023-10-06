# MSFT-Final-Project

This was done as a final project for a Machine Learning in Finance course I took as part of my Master's. The project goal was to extend the Regression model Tatsat propsed in [their book](https://www.amazon.ca/Machine-Learning-Science-Blueprints-Finance/dp/1492073059) for stock price prediction, in particular, the prediction of MSFT. Accurately predicting the future price of a stock is somewhat of a holy grail problem in finance, so the likelihood of being able to do so is very low. Rather than aiming to have a functioning model that can make me a lot of money, the actual aim of the project was to learn more about machine learning techniques in the financial domain.

The data used was intraday data courtesy of [Wharton Research Data Services](https://wrds-www.wharton.upenn.edu/), and included stock data, currency data, index data, and various sentiment indicators.

In the project, the data was imported, cleaned, and explored. Then, pipelines were created for encoding, smoothing, and feature selection. 14 models were trained and evaluated using pipelines, and the two best models were then chosen to proceed and receive hyperparameter tuning. The final model was chosen, and its trading strategy was evaluated for its cumulative returns across the training set, and the test set. Finally, the CAGR, Phi K, Sharpe Ratio were all calculated to evaluate the model. 

In the end (as expected), the final model was not able to consistently earn positive returns. However, through this process I learned a lot about financial modelling, and machine learning / statistical techniques within the world of finance. I also got an A+!

![TestCumulative](https://github.com/WFERRIE/MSFT-Final-Project/assets/58156317/8b3a061e-ec7f-4ccd-a9ee-a395ad065d0a)

