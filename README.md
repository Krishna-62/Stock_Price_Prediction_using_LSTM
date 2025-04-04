# Stock_Price_Prediction_using_LSTM
**#Stock_Price_Prediction_using_LSTM**   Used LSTM neural networks to predict stock prices by learning patterns from historical time series data. Preprocessed data, trained the model, and evaluated performance using metrics like RMSE for accuracy.
Step-by-Step Process Followed
Data Collection

Collected historical stock price data (Open, High, Low, Close, Volume) using Yahoo Finance API or CSV files.

Data Cleaning & Preprocessing

Handled missing values.

Scaled the data using MinMaxScaler to bring values between 0 and 1.

Created time series sequences (X, y) suitable for LSTM input.

Split the data into training and testing sets.

LSTM Model Design

Built a Sequential model using LSTM layers and Dense output layer.

Added dropout layers to reduce overfitting.

Compiled model using loss function (MSE) and optimizer (Adam).

Model Training

Trained the model with proper batch size and epochs.

Monitored training/validation loss to avoid overfitting.

Prediction & Evaluation

Made predictions on the test set.

Inverted the scaling to get actual price values.

Calculated error metrics like RMSE or MAE.

Visualization

Plotted actual vs predicted stock prices for comparison.

Analyzed trend-following capability of the model.

Model Tuning (Optional)

Adjusted window size, number of LSTM units, epochs, or added more layers to improve accuracy.

Saving & Deployment (Optional)

Saved the model using .h5 format.

Loaded model for future use or integrated into a dashboard/app.
