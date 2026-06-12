
# Kerala House Price Predictor

A machine learning model that predicts house prices in Kerala, India
using Random Forest Regression.

## Dataset
- Source: Kerala House Prices and Data (Kaggle)
- 5270 houses scraped from makaan.com
- 12 features including area, bathrooms, location distances

## Results
- Model: Random Forest (100 trees)
- MAE: ₹8,52,467
- Average house price: ₹61,27,222
- Error rate: 13.9%

## Key Steps
1. Exploratory Data Analysis
2. Outlier removal (area > 10,000 sqft)
3. Train/validation split (75/25)
4. Random Forest model with hyperparameter tuning
5. Evaluated using Mean Absolute Error

## What I Learned
- Data cleaning has more impact than model tuning
- Removing 86 outlier rows cut MAE from 17.5L to 8.5L
- More trees doesn't always mean better results

## Tech Stack
- Python, Pandas, Scikit-learn
- Kaggle Notebooks
