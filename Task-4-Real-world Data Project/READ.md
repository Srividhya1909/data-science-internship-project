# Task 4: Real-World Data Project (Finance)

## Project Title
Apple Stock Price Prediction Using Machine Learning

## Project Overview

This project focuses on analyzing historical Apple stock market data and building a machine learning model to predict future stock prices. The project demonstrates how data science techniques can be applied to real-world financial datasets for predictive analysis.

## Dataset Description

The dataset contains historical Apple stock market information, including:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close Price
- Volume

## Project Objectives

- Analyze historical stock market trends
- Visualize stock price movements
- Identify relationships between stock market features
- Build a machine learning model for stock price prediction
- Evaluate model performance using regression metrics

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded and explored the dataset
- Checked for missing values
- Converted date column into datetime format
- Removed or handled missing records
- Created a target variable for future stock price prediction

## Exploratory Data Analysis (EDA)

The following analyses were performed:

### Stock Closing Price Trend
Visualized the movement of Apple's closing stock price over time.

### Trading Volume Analysis
Analyzed fluctuations in trading volume.

### High vs Low Price Analysis
Compared daily high and low stock prices.

### Correlation Analysis
Examined relationships between stock market features using a correlation matrix.

## Machine Learning Model

### Algorithm Used
Random Forest Regressor

### Features Used

- Open Price
- High Price
- Low Price
- Volume

### Target Variable

- Next Day Closing Price

## Model Training

The dataset was split into:

- Training Data (80%)
- Testing Data (20%)

The model was trained using historical stock market data.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Visualizations

The project includes:

1. Closing Price Trend
2. Trading Volume Trend
3. High vs Low Price Chart
4. Correlation Matrix
5. Actual vs Predicted Stock Price Comparison

## Key Findings

- Apple stock prices show long-term growth trends.
- High and Low prices strongly influence future closing prices.
- Trading volume contributes to stock market movements.
- The Random Forest model effectively captures patterns in historical stock data.
- Machine learning can be used to estimate future stock prices with reasonable accuracy.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Skills Demonstrated

- Data Cleaning
- Data Visualization
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Regression Modeling
- Model Evaluation

## Conclusion

This project demonstrates the application of machine learning techniques to financial market data. By analyzing historical Apple stock prices and training a Random Forest Regression model, meaningful insights and future price predictions were generated. The project highlights how data science can support decision-making in finance and investment analysis.
