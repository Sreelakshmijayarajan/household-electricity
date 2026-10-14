# Household Electricity Consumption Forecasting using LSTM

## Project Overview
This project uses a Long Short-Term Memory (LSTM) deep learning model to forecast household electricity consumption using historical electricity measurements.

## Objectives
- Preprocess household electricity consumption data.
- Handle missing values and normalize numerical features.
- Generate sequences using the previous 60 minutes of data.
- Train an LSTM model to predict next-minute electricity consumption.
- Evaluate model performance using MAE and RMSE.
- Visualize actual and predicted consumption.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow and Keras

## Dataset
Household Electric Power Consumption dataset from Kaggle.

## Model
The model uses an LSTM layer with 64 units, dropout, and dense layers to predict Global Active Power.

## Results
- Test MAE: 0.5268 kW
- Test RMSE: 0.7077 kW
- Example next-minute prediction: 4.299 kW


## Author
SREELAKSHMI J
