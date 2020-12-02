##ELO MERCHANT CATEGORY RECOMMENDATION COMPETITION
Help understand customer loyalty

This machine learning competition was hosted by Kaggle where we need to develop a regression model that will predict the loyality scores given for each card_id. 

##Competition: https://www.kaggle.com/c/elo-merchant-category-recommendation

##Dataset source: https://www.kaggle.com/c/elo-merchant-category-recommendation/data

##Required Python Libraries:
Numpy, Pandas,Matplotlib,Seaborn,Scikit-learn, lightgbm, xgboost, datetime, gc, Optuna, Keras, Flask.

##How to Run
Please execute notebook-elo-prediction.ipynb for complete execution. To check the loyalty score for a particular customer execute the Final.ipynb and update the parameters as required.
In order to run it as a web app in your localhost please execute app.py and access the URL as <localhost>:Port/index
        
##Best Model
LGBM Regressor with stratified K-fold gives us the lowest RMSE, optuna is used for hyper parameter tuning.

##License
Distributed under the MIT License.

Pull requests are welcome, for major changes 

Please visit the blog https://raisulhazari.medium.com/elo-predicting-customer-loyalty-score-4e0ddd73c468 for step by step approach and  
https://loyaltyscore.herokuapp.com/index to access the deployed web app
