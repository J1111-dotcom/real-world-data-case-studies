# Ford Car Resale Price Analysis and Prediction

This project simulates a real-world case study where a data analyst supports an automotive resale dealership in optimizing its Ford vehicle pricing strategy. Using historical sales data, we clean, explore, and model the factors influencing resale value, culminating in a predictive Ridge Regression model.

## Project Scenario
The dealership wants to leverage historical Ford car sales data to predict optimal resale prices, improve inventory turnover, and enhance pricing consistency. Specific client requests include analyzing sales trends by fuel type and identifying price outliers by transmission type.

## Dataset Overview
The dataset contains Ford resale listings, with features such as:
- Model
- Year (converted to Age)
- Transmission type
- Mileage
- Fuel type
- Tax
- MPG (miles per gallon)
- Engine size
- Sale price

## Folder Structure

```
automotive/
│
├── data/ # Raw dataset (.xlsx)
├── notebooks/ # Final project notebook
├── images/ # Visuals used in analysis
└── README.md # Project documentation
└── requirements.txt # Dependencies
```

## Analysis and Modeling Steps
- Data cleaning: Handling duplicates and missing values
- Exploratory Data Analysis (EDA): Univariate and bivariate exploration
- Feature engineering: Creating "Age" feature, one-hot encoding categorical variables
- Model building: Linear Regression, Polynomial Regression (degree 2), Ridge Regression
- Hyperparameter tuning: Grid search to find the best Ridge α value
- Final model selection: Ridge Regression (α=0.1) based on RMSE and R² performance

![Price Distribution](automotive/images/price_distribution.png)

## Key Results
- Linear and Ridge Regression achieved the best performance (Test R² ≈ 0.71, RMSE ≈ \$2,559)
- Polynomial Regression underperformed due to overfitting
- Business insights provided for pricing strategies by transmission type, age, mileage, and fuel type

## Deliverables
- Final Ridge model for predictive pricing
- Business recommendations to optimize pricing and operations

  This project is part of a broader portfolio showcasing real-world data analysis. Visit [My GitHub Portfolio](https://github.com/dataworksbyj) to explore more.

