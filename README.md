# Stock-Market-Prediction- 
### Task 7 : Stock Market Prediction Using Numerical Analysis and Textual Analysis
Objective: Create a hybrid model for stock price/performance prediction using numerical analysis of historical stock price,and sentimental analysis of news headlines  stock used to analyze and predict : SENSEX(S&amp;P BSE SENSEX) 
**Dataset:**
* historical stock price : https://finance.yahoo.com/
* News headlines : https://bit.ly/36fFPI6
#### CONCLUSION :
                                          MEAN_SQUARED_ERROR

* RANDOM FOREST REGRESSOR MODEL  : 0.058580517630070564
    
* DECISION TREE REGRESSOR MODEL  : 0.0977920458625032
    
* ADABOOST REGRESSOR  MODEL      : 0.05782615019672828
    
* LGBM MODEL                     : 0.06384946650767759

* XGBOOST MODEL                  : 0.0680421510332517
##### THE BEST PERFORMING MODEL IS ADABOOST REGRESSOR.

Situation: We needed to predict SENSEX (S&P BSE SENSEX) stock price performance using a hybrid model combining historical price data and sentiment analysis of news headlines.

Task: To build and evaluate different machine learning models (Random Forest, Decision Tree, AdaBoost, LGBM, XGBoost) for stock price prediction, comparing their performance using Mean Squared Error (MSE).

Action: We extracted historical stock prices from Yahoo Finance and relevant news headlines. We preprocessed the data, engineered features from the price data, and used a sentiment analysis library to extract sentiment scores from the news headlines. We combined these features and trained the specified models, optimizing their hyperparameters where appropriate. Finally, we evaluated the models using MSE on a testing dataset.

Result: The AdaBoost Regressor model demonstrated the best performance with the lowest Mean Squared Error (0.0578). This indicates that the hybrid approach, incorporating sentiment analysis with historical price data, produced a more accurate prediction model compared to the other models considered. The models' performance varied based on their ability to capture trends and sentiment-driven changes in the stock market, confirming that AdaBoost was the most effective at predicting future SENSEX values within this specific model range, dataset, and approach.
