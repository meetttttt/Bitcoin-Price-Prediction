# Bitcoin-Price-Prediction

In this project, as the name suggest we are basically going to predict the bitcoin price prediction / Time series Analysis 

What is LSTM
Long short-term memory is an artificial recurrent neural network architecture used in the field of deep learning. Unlike standard feedforward neural networks, LSTM has feedback connections. It can process not only single data points, but also entire sequences of data.
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems. This is a behavior required in complex problem domains like machine translation, speech recognition, and more. LSTMs are a complex area of deep learning.
LSTMs are often referred to as fancy RNNs. Vanilla RNNs do not have a cell state. They only have hidden states and those hidden states serve as the memory for RNNs. Meanwhile, LSTM has both cell states and a hidden states.

Steps for performing Bitcoin-Price-Prediction :
- Import necessary Library
- load dataset
- explore data check for null values or missing value(handle them by removing them or replacing the null values by the mean of that column)
- Visualize the data to explore the trend in the data.
- Split the dataset into training and testing data.(Here we are just considering 1 year data for training data, Since Bitcoin price has drastically flucated from 200 dollar in year 2014 to 15000 dollar in year 2018 to 3000 dollar in year 2019 theses values are apporx so we will just consider 1 Year to avoid this type of flucation in the data.
As we want to predict Close Price of the Bitcoin so we are just Considering Close aand Date.
- Building LSTM Model
- Fiting the training data
- Prediction on testing data
- Model Evaluation(Calculate RMSE,MSE,R2 score) 
- Hyperparameter tunning
- Prediction for n days(where n is any real number)

Conclusion:
We Have created LSTM model for predicting Bitcoin Price.
