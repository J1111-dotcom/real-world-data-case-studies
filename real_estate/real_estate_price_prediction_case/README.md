# Predicting Housing Prices for a Real Estate Investment Trust (REIT)

This project simulates a real-world scenario for a data analyst working with a real estate client. A Real Estate Investment Trust (REIT) is exploring opportunities in the residential housing market and wants to estimate the market value of properties based on structural, geographic, and quality-based features. The goal is to build a predictive model that can support investment and pricing decisions.


## Project Overview

- **Business Context**: A REIT is looking to invest in residential real estate and needs a reliable way to estimate home prices based on available property features.
- **Objective**: Build a regression model that predicts the log-transformed sale price of a home using housing attributes.
- **Dataset**: Historical housing data (refined from a Kaggle dataset) including features like square footage, number of bedrooms, location indicators, and construction quality.
- **Tech Stack**: Python, Pandas, Seaborn, scikit-learn, Matplotlib, NumPy


## Repository Structure

```
real_estate_price_prediction/ │ ├── data/ # Housing dataset ├── notebooks/ # Main analysis notebook │ └── real_estate_analysis.ipynb ├── images/ # Visualizations for README/docs (optional) ├── requirements.txt # Project dependencies └── README.md
```

## Key Highlights

- Performed exploratory data analysis to identify price-driving features
- Applied log transformation to stabilize target variable
- Built and evaluated multiple regression models (simple, multivariable, polynomial)
- Final model achieved ~76% R² on test data, with interpretability and business-focused recommendations
- Business insights and limitations clearly documented


## Key Results

- Strongest predictors: square footage, grade, number of bathrooms
- Polynomial regression model with pipeline achieved best performance
- RMSE in log-scale translated to ~$60K–$80K margin of error on mid-range homes
- Model effective for market-level insights, not intended for standalone decision-making

## For More Projects

This project is part of a broader portfolio showcasing practical applications of data science across analytics, visualization, and machine learning.
[My GitHub Portfolio](https://github.com/J1111-dotcom)

