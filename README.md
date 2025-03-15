# Sentiment-Analysis-of-Twitter-Data-for-Predicting-Stock-Market-Movements
This project uses Twitter sentiment and machine learning (LSTM, Random Forest, XGBoost) to predict stock prices. LSTM achieves the best results, demonstrating the power of social media data in financial forecasting. Explore the code and results to see how sentiment analysis enhances stock market predictions.

## Overview
This project aims to predict stock market movements using sentiment analysis of Twitter data. The study integrates Twitter sentiment with historical stock market data to build predictive models using machine learning techniques such as **LSTM**, **Random Forest**, and **XGBoost**. The project is implemented in a single Jupyter notebook, which covers data preprocessing, sentiment analysis, model training, and evaluation.

## Key Features
- **Sentiment Analysis**: Using **VADER** to analyze Twitter sentiment.
- **Predictive Models**: Implementation of **LSTM**, **Random Forest**, **XGBoost**, and hybrid models.
- **Data Sources**: Twitter data from **Kaggle** and stock market data from **Yahoo Finance**.
- **Evaluation Metrics**: **MSE**, **RMSE**, and **R²** for model performance.


## Results
The **LSTM model** achieved the best performance with an **MSE of 87.94** and an **R² score of 0.55**, outperforming other models like Random Forest and XGBoost. Below is a summary of the model performance:

| Model                     | Mean Squared Error (MSE) | R² Score |
|---------------------------|--------------------------|----------|
| Random Forest Regressor    | 119.82                  | 0.39     |
| LSTM (Long Short-Term Memory) | 87.94                  | 0.55     |
| XGBoost Regressor          | 186.83                  | 0.05     |
| Stacking Model (RF + XGBoost) | 147.15                | 0.25     |
| Hybrid Stacking Model      | 642.01                  | 0.75     |

Visualizations of actual vs. predicted stock prices are available in the folder.

## Future Work
- Real-time sentiment integration.
- Advanced models like Transformers and BERT.
- Incorporate macroeconomic and news data.
- Reinforcement learning for dynamic market adaptation.
