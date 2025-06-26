# House-Price-Prediction-Using-Linear-Regression

## Objective
To implement and understand both simple and multiple linear regression using the `Housing.csv` dataset.

## Tools Used
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## Steps Followed

1. Data Import and Preprocessing:
   - Loaded the CSV file.
   - Converted categorical variables into numeric form using one-hot encoding.

2. Train-Test Split:
   - Divided the data into 80% training and 20% testing.

3. Model Fitting:
   - Applied `LinearRegression` from `sklearn.linear_model`.

4. Model Evaluation:
   - MAE (Mean Absolute Error): ~970043.40
   - MSE (Mean Squared Error): ~1.75e+12
   - R² Score: ~0.653

5. Visualization:
   - Plotted actual vs predicted prices.

## Output
- `actual_vs_predicted.png`: Scatter plot comparing actual and predicted housing prices.

## Conclusion
The multiple linear regression model explained ~65% of the variance in housing prices. Further tuning and feature engineering could improve results.
