William Anderson:
# AI-ML-Assignment-2-Linear-Regression
King county housing market older homes data set with (Linear-Regression).

Data set description: date	price	bedrooms	bathrooms	sqft_living	sqft_lot	floors	waterfront	view	...	sqft_basement	yr_built	yr_renovated	zipcode	lat	long	sqft_living15	sqft_lot15	sale_year	house_age

Target variables: Predictor (X)
house_age
How old the house is (years) 
Target (y)
price
Sale price of the house (dollars)

Data cleaning and feature engineering steps:run data set then check for missing values then run df.describe(), next:  Identify outliers in the chosen feature ('yr_built').  Remove unrealistic construction years (before 1900), then new updated data set with year built and house age. Run code for X = df[['house_age']] # Predictor(s)
y = df['price']  # Target for gragh y_price horizontal x_house_age vertical. 
 Split the data: 80% training, 20% testing, next: Initialize the model then # Train the model.
 "Mean Squared Error (MSE):", mse)
"Root Mean Squared Error (RMSE):", np.sqrt(mse))
"R-squared (R²):", r2)
Lastly, Scatter plot + regression line,
Scatter of actual test data and Finally Sort X_test for a smooth regression line.


 
