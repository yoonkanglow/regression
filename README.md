# regression
As scikit learn regression model does not have the stepwise variable selection method, I wrote a piece of code in python which will build the regression model using all possible variable combination (or in my case only consider the variables that have X% or higher correlation with the target variable). Effectively, it will work the same as the stepwise selection method. The output of the code will be all models that have significant input variable and the order of the output is in the ascending order of testing data RMSE.
