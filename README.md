# How to use Lasso Regression in Python

As we know, regression is a modeling task that involves predicting a numeric value given an input.
Linear regression is the standard algorithm for regression that assumes a linear relationship between inputs and the target variable.


Lasso Regression is a popular type of regular linear regression. This has the effect of shrinking
the coefficients for the input variables that do little to contribute to the prediction task.
It allows some coefficient values ​​to be zero, allows input variables to be effectively removed
from the model, provides a type of automatic feature selection.

## Conclussion

From Lasso Regression, we know the boston data frame have 13 independent variable’s and 1 dependend variable.
But from the results of the method that was run, it turned out that 2 variables did not match the model to be run.
Therefore, these variables must be excluded from the model, so that the model obtained from the regression lasso is as follows:


Medv = 25.86 – 0.057 crim + 0.021 zn   – 0.028 indus + 0.000 chas  – 0.000 nox + 2.466 rm  + 0.023 age - 0.558 dis - 0.717 ptratio  + 0.012 black - 0.720 lstat

Besides that, from this model, we can see that some automatic variables have been excluded from the model which is has a coefficient of zero.
![image](https://user-images.githubusercontent.com/68943747/171617268-25165ee6-6abe-4f32-9e05-0c8c98e7ad29.png)


