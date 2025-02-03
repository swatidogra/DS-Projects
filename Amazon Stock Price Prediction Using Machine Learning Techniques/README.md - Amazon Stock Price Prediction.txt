# Amazon Stock Price Prediction Using Machine Learning Techniques

## Overview
This project aims to develop predictive models to predict Amazon stock price based on past 5 years of data downloaded from NASDAQ website. By leveraging machine learning algorithms, we can provide accurate price predictions to assist investors.


## Project Details
- **Project Title**: Amazon Stock Price Prediction Using Machine Learning Techniques
- **Author**: Swati Dogra
- **Date**: 12/21/2024

## Objectives
- To analyze and preprocess the dataset containing Amazon historic stock prices.
- To build and evaluate regression models for predicting Amazon Stock prices.
- To compare the performance of different models and select the best one.

## Data Source
The dataset used in this project was sourced from NASDAQ. It contains information for past 5 years of Amazon stock and its performance with High, Low, Close price for a particular day. 

## Tools and Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow
- Keras
- Matplotlib
- Seaborn

## Methodology
1. Data Preprocessing: Cleaning the data, handling missing values, and encoding categorical variables.
2. Exploratory Data Analysis (EDA): Analyzing the data to uncover patterns and relationships.
3. Model Building: Developing regression models including Linear Regression, ARIMA, and LSTM.
4. Model Evaluation: Evaluating the models using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE).
5. Model Selection: Comparing the models and selecting the one with the best performance.

## Results
The analysis of Amazon stock price prediction revealed that the Linear Regression model demonstrated a consistent performance without significant overfitting or underfitting. The ARIMA and LSTM models, while powerful, showed signs of overfitting, indicating a need for regularization techniques. Specifically, Linear Regression achieved a Test MAE of 26.96, whereas ARIMA and LSTM had higher disparities between their training and test errors, highlighting their sensitivity to the data's complexity. These findings emphasize the importance of selecting and fine-tuning the right model for accurate stock price forecasting.

## Conclusion
This project successfully developed predictive models for estimating Amazon stock prices. The Linear Regression model showed a good fit without significant overfitting or underfitting. However, the ARIMA and LSTM models exhibited overfitting, indicating a need for regularization techniques. These results can be valuable for various stakeholders.

## Future Work
- Extending the analysis to other stocks and financial instruments.
- Implementing real-time prediction models for intraday trading.
- Integrating additional data sources (e.g., social media sentiment, economic indicators) for more 
comprehensive predictions. 

## Contact
For questions or support, please open an issue on this repository or contact [sdogra@my365.bellevue.edu].

