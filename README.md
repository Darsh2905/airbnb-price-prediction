# Airbnb Price Prediction

## Overview
This project predicts Airbnb listing prices in New York City using machine learning techniques.  
The goal was to understand how different features affect listing prices and to build predictive models.

## Dataset
- Source: Airbnb NYC 2019 dataset
- Contains information about listing location, room type, reviews, availability, and pricing.

## Project Steps
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
3. Baseline model using Linear Regression
4. Random Forest model
5. Feature engineering using detailed location data
6. Improved models and performance comparison

## Model Performance

| Model | RMSE | R² |
|------|------|----|
| Linear Regression (basic features) | ~72 | 0.38 |
| Random Forest (basic features) | ~71.6 | 0.38 |
| Linear Regression (improved features) | ~68.4 | 0.44 |
| Random Forest (improved features) | ~64.2 | 0.50 |

## Key Insights
- Location is the strongest predictor of price.
- Feature engineering improved performance more than changing models.
- Random Forest outperformed Linear Regression after adding location features.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn