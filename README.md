# Gold Price Forecasting using Machine Learning

## Overview

This project focuses on predicting gold prices using historical data and machine learning techniques. The dataset is retrieved from Yahoo Finance, and various technical indicators are calculated to enhance predictive accuracy. The model is trained using the k-Nearest Neighbors (k-NN) algorithm with multiple time-step forecasting.

## Table of Contents
- [Overview](#overview)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

## Project Workflow

1. **Data Collection and Preprocessing** - Fetching historical gold price data and cleaning it.
2. **Exploratory Data Analysis (EDA)** - Understanding trends and correlations.
3. **Feature Engineering** - Creating additional features for better model accuracy.
4. **Time Series Splitting** - Splitting data into training and testing sets.
5. **Model Training and Optimization** - Using k-NN with hyperparameter tuning.
6. **Forecast Evaluation** - Assessing the performance of the model.
7. **Visualization of Predictions** - Plotting results for better insights.

## Results

- The model was evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²).
- Multi-step forecasting allows prediction of gold prices for future days.
- The visualization provides insights into how the model performs over time.

## Future Improvements

- Implementing deep learning models (LSTMs, transformers) for better predictions.
- Incorporating additional features such as macroeconomic indicators.
- Enhancing feature engineering techniques for improved model performance.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

