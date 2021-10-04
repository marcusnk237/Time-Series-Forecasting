# Time-Series-Forecasting
This program allows to perform a prediction of one-variable time series using recursive neural networks (LSTM).
First, the data are loaded with Pandas.
Then, the KNN Imputer is used to completely reconstruct the data in case they are corrupted.
The reconstructed data are then resized, before being trained by a recursive neural network.
