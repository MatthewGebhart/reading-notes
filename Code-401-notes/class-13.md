# Class 13 - Linear Regressions

## Reading

### How to Run Linear Regression in Python
[Source Credit](https://www.activestate.com/resources/quick-reads/how-to-run-linear-regressions-in-python-scikit-learn/)
- Scikit-learn is a Python package that simplifies the implementation of a wide range of Machine Learning (ML) methods for predictive data analysis, including linear regression.
- Linear regression can be thought of as finding the straight line that best fits a set of scattered data points: 
- You can then project that line to predict new data points. 
- Common terminology:
- Best Fit – the straight line in a plot that minimizes the deviation between related scattered data points.
- Coefficient – also known as a parameter, is the factor a variable is multiplied by. In linear regression, a coefficient represents changes in a Response Variable (see below).
- Coefficient of Determination – the correlation coefficient denoted as 𝑅². Used to describe the precision or degree of fit in a regression. 
- Correlation – the relationship between two variables in terms of quantifiable strength and degree, often referred to as the ‘degree of correlation’.  Values range between -1.0 and 1.0. 
- Dependent Feature – a variable denoted as y in the slope equation y=ax+b. Also known as an Output, or a Response. 
- Estimated Regression Line – the straight line that best fits a set of scattered data points.
- Independent Feature – a variable denoted as x in the slope equation y=ax+b. Also known as an Input, or a predictor. 
- Intercept – the location where the Slope intercepts the Y-axis denoted b in the slope equation y=ax+b. 
- Least Squares – a method of estimating a Best Fit to data, by minimizing the sum of the squares of the differences between observed and estimated values.
- Mean – an average of a set of numbers, but in linear regression, Mean is modeled by a linear function.
- Ordinary Least Squares Regression (OLS) – more commonly known as Linear Regression. 
- Residual – vertical distance between a data point and the line of regression (see Residual in Figure 1 below).
- Regression – estimate of predictive change in a variable in relation to changes in other variables (see Predicted Response in Figure 1 below).
- Regression Model – the ideal formula for approximating a regression.
- Response Variables – includes both the Predicted Response (the value predicted by the regression) and the Actual Response, which is the actual value of the data point (see Figure 1 below).
- Slope – the steepness of a line of regression. Slope and Intercept can be used to define the linear relationship between two variables: y=ax+b.
- Simple Linear Regression – a linear regression that has a single independent variable.
- A scikit-learn linear regression script begins by importing the LinearRegression class:
```
from sklearn.linear_model import LinearRegression
sklearn.linear_model.LinearRegression()
```

### Additional Resources
[Linear Regression in Python](https://realpython.com/linear-regression-in-python/)

## Videos

### Introduction to Simple Linear Regressions
[Source Credit](https://www.youtube.com/watch?v=KsVBBJRb9TE)
- simple linear regressions is a single response variable
- multiple regression is multiple explanatory variables
- y variable is what we are testing the response variable (dependant)
- x is the explanatory variable (independent)
- we usually use the method of least squares to estimate Bo and B1


## Bookmark and review

[Train & Test Splits](https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6)

[What is Linear Regression](https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-linear-regression/)


## Things I want to know more about
- More about linear regressions.