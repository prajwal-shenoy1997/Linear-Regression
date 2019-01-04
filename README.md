Implementation of a Multiple Linear Regression Model  which predicts the profit earned by startups based on features like its spending on R&D,Market and Administration and also the state in which it is located.
Analysed the financial reports of startups and developed a multiple linear regression model which was optimized using Backward Elimination
to determine which independent variables were statistically significant to the company's earnings.
The program uses LinearRegression class from sklearn.linear_model library to perform Linear Regression.
It also uses the statsmodels.formula.api library to get the P values of the independent variables which is used for feature selection in Backward Elimination. The new dataset of independent variables obtained from Backward Elimination is called X_opt. 
X_opt is again split into training set and test set and the regressor is fitted with X_opt and y_train variables and the prediction for y_test (dependent variable) is then done using the regressor.predict(X_opt_test)
