# Bulldozer-Price-Prediction-Model
This model shows how well we can predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for.
Below is an end-to-end machine learning model I developed. This model shows how well we can predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for.

The dataset used for this project was gotten from an old competition hosted on Kaggle, containing more than 600,000 records of data, from a training set that contains data through the end of 2011, a validation set which contains data from January 1, 2012 - April 30, 2012, and test set which contains data from May 1, 2012 - November 2012. The dataset also contains more than 50 features. More information about the features is on this link: https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices, which is not included in the sklearn library, but manually created by me using python functions.
My model was able to achieve the following results using a random forest regressor concluded after going through intense Hyperparameter tuning: 
{'Training MAE': 2910.3969487587106,
 'Valid MAE': 5756.155735371555,
 'Training RMSLE': 0.14389636095547528,
 'Valid RMSLE': 0.23955380880022814,
 'Training R^2': 0.9594705382669589,
 'Valid R^2': 0.8677312907263242}


