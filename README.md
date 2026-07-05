 you will build a linear regression model to predict fuel efficiency (miles per gallon) of automobiles. Download the auto-mpg.csv dataset from: Auto-mpg dataset. 

Load the data as a Pandas data frame and ensure that it imported correctly.
Begin by prepping the data for modeling:
Remove the car name column.
The horsepower column values likely imported as a string data type. Figure out why and replace any strings with the column mean.
Create dummy variables for the origin column.
Create a correlation coefficient matrix and/or visualization. Are there features highly correlated with mpg?
Plot mpg versus weight. Analyze this graph and explain how it relates to the corresponding correlation coefficient.
Randomly split the data into 80% training data and 20% test data, where your target is mpg.
Train an ordinary linear regression on the training data.
Calculate R2, RMSE, and MAE on both the training and test sets and interpret your results.
Pick another regression model and repeat the previous two steps. Note: Do NOT choose logistic regression as it is more like a classification model.
