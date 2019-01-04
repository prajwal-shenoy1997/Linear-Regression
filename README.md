Implementation of a Multiple Linear Regression Model  which predicts the profit earned by startups based on features like its spending on R&D,Market and Administration and also the state in which it is located.
Analysed the financial reports of startups and developed a multiple linear regression model which was optimized using Backward Elimination
to determine which independent variables were statistically significant to the company's earnings.
The program uses LinearRegression class from sklearn.linear_model library to perform Linear Regression.
It also uses the statsmodels.formula.api library to get the P values of the independent variables which is used for feature selection in Backward Elimination.
