# Stock-Prediction-using-LSTM
This project uses Long Short-Term Memory (LSTM) neural networks to predict stock market prices. The model is trained on historical stock data to forecast future prices, leveraging the sequential nature of time series data for accurate predictions.
Description
The project involves the following steps:

Data Collection:

Using pandas_datareader to fetch historical stock data.
Libraries used: pandas, numpy, pandas_datareader, quandl.
Data Preprocessing:

Scaling the data using MinMaxScaler from sklearn to normalize the feature values.
Libraries used: pandas, numpy, sklearn.preprocessing.
Building the LSTM Model:

Creating an LSTM model using Keras.
The model consists of sequential layers: LSTM and Dense layers.
Libraries used: keras.models.Sequential, keras.layers.Dense, keras.layers.LSTM.
Training the Model:

Splitting the data into training and testing sets.
Training the LSTM model on the training data.
Model Evaluation:

Making predictions on the test data.
Visualizing the results using matplotlib.
