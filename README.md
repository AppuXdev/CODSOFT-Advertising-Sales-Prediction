# CODSOFT Task 4 - Advertising Sales Prediction

## Objective
Predict product sales based on advertising spend across TV, Radio, and Newspaper channels using Linear Regression.

## Dataset
Advertising dataset with 200 samples. Features: TV, Radio, Newspaper advertising budgets. Target: Sales.

## Model Used
Multiple Linear Regression

## Final Results
- **R2 Score**: 0.9059
- **RMSE**: 1.7052
- **MAE**: 1.2748

## Key Insights
R² of 0.906 indicates advertising budget is a very strong predictor of sales. TV and Radio spend show high positive correlation with Sales, while Newspaper has weaker impact. The model predicts sales within ±1.27 units on average.

## Actual vs Predicted
The scatter plot shows predicted values closely follow actual sales, confirming good model fit with minimal bias.

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Files
1. `advertising.ipynb` - Complete analysis with EDA and model outputs
2. `advertising.py` - Python script version
3. `advertising.csv` - Dataset used
