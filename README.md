# Code-the-Market-Predicting-Stocks-with-ML
This project involves building a machine learning model to predict future stock prices using historical stock market data. The focus is on using a Long Short-Term Memory (LSTM) network, a type of Recurrent Neural Network (RNN), which is well-suited for time series forecasting.  
🎯 Objective:
To develop a predictive model that can forecast stock prices based on historical data using LSTM deep learning architecture.

🧰 Tools & Technologies:
Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Keras (TensorFlow backend)

Model: LSTM Neural Network

Data Source: Yahoo Finance / Kaggle (e.g., Apple, Google, Tesla stock data)

🔧 Workflow:
Data Collection: Download historical stock price data (Open, High, Low, Close, Volume).

Preprocessing:

Handle missing values using .dropna().

Normalize the data using MinMaxScaler.

Training Data Preparation:

Create sequences of past 100 days to predict the next day’s price.

Split data into training and testing sets.

Model Building:

Use Keras to build an LSTM-based model.

Layers: LSTM, Dropout, Dense.

Model Training:

Train using MSE (Mean Squared Error) as loss function and Adam optimizer.

Evaluation & Prediction:

Predict on test data.

Plot actual vs predicted prices for visual evaluation.

📈 Outcome:
The model successfully learns stock price trends and provides close predictions.

Visual comparison between actual vs predicted values shows good alignment for short-term forecasting.

Made by Rohan A M
