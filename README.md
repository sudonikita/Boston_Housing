# Boston_Housing

This analysis is about Boston Housing Data. The medv variable is the target variable.

Number of Cases: The dataset contains a total of 506 cases.

-There are 14 attributes in each case of the dataset. They are:
CRIM - per capita crime rate by town
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's

-The method of analysis will include following stages:

	Exploratory Data Analysis 
	Randomly sampling the data into test and training data, in the ratio of 70:30
	Fitting various models using different variable selection methods and finding the best model using: 
	Stepwise, Forward, Bakward, LASSO
	Testing the model on out-of-sample data on the final model and stating the MSE.
	Repeat the steps above for the regression tree (CART) model.
