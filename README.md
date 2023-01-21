# home-price-prediction


Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area. The dataset contains a total of 506 cases, with 13 attributes, and price as the target.

I have used and compared four approches for prediction, and Ranked their prediction performance as 1-XGB Regressor, 2-Random Forest Regressor, 3-Neural Network, 4-Linear Regression.


There are 13 attributes in each case of the dataset. They are:

1 CRIM - per capita crime rate by town

2 ZN - proportion of residential land zoned for lots over 25,000 sq.ft.

3 INDUS - proportion of non-retail business acres per town.

4 CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)

5 NOX - nitric oxides concentration (parts per 10 million)

6 RM - average number of rooms per dwelling

7 AGE - proportion of owner-occupied units built prior to 1940

8 DIS - weighted distances to five Boston employment centres

9 RAD - index of accessibility to radial highways

10 TAX - full-value property-tax rate per $10,000

11 PTRATIO - pupil-teacher ratio by town

12 B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

13 LSTAT - % lower status of the population

Target: MEDV - Median value of owner-occupied homes in $1000's


