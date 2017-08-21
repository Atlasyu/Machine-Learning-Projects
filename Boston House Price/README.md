# Boston House Price

Regression:
1. LinearRegression()
2. Lasso()
3. ElasticNet()
4. KNeighborsRegressor()
5. DecisionTreeRegressor(random_state=seed)
6. SVR()

Ensembles:
1. AdaBoostRegressor(random_state=seed)
2. GradientBoostingRegressor(random_state=seed)
3. BaggingRegressor(random_state=seed)
4. RandomForestRegressor(random_state=seed)
5. ExtraTreesRegressor(random_state=seed)

Dataset:
* USI doesn't house this dataset any more. 
* SKlearn has stored the dataset, read directly from Sklearn

Mulicollinearity:
* Didn't ust it in this dataset. Just happen to run into a lot of collinearity in this dataset.
* [Handling Multicollinearity in Regression Analysis](http://blog.minitab.com/blog/understanding-statistics/handling-multicollinearity-in-regression-analysis)
* One way to measure multicollinearity is the variance inflation factor (VIF), which assesses how much the variance of an estimated regression coefficient increases if your predictors are correlated.  If no factors are correlated, the VIFs will all be 1.
* A VIF between 5 and 10 indicates high correlation that may be problematic. And if the VIF goes above 10, you can assume that the regression coefficients are poorly estimated due to multicollinearity.
