# Predicting sales revenue with scikit learn
To build both simple linear regression model and multiple linear regression model.

With a given advertising data set we need to predict the sales revenue based on advertising spent through mediums such as TV, radio, and newspaper.

# Libraries used:
1.Scikit learn for calculating linear regression model.

2.Pandas for data management.

3.Numpy for mathematical calculations.

4.Seaborn for plotting data.

# Tasks evolved to build a simple linear regression model:
1.Datas were loaded and libraries where imported.

2.The data's were cleaned and pre-processed for further analysis removing unwanted columns.

3.Vizualised the data for model building using plots and looked at the disrtibutions of the predictors - TV ,Radio and newspaper.

4.Vizualised the correlation between predictor and response and created a heat map for corresponding correlation matrix.

5.The best feature is selected after predicting the relationship between the sales revenue and the expenditure on the various advertisment channels.

6.Creating a simple linear regression model using scikit learn ,With one predictor as X and response as y , a train_test_split module was used for sliting the data sets into train and test sets.

7.Intercept and coeffecients of the best fit line is predicted.

8.Determing y_pred and Plotting the best fit line.

9.Evaluating performance of algorithm.

# Tasks evoloved to build a multiple linear regression model:
1.Datas were loaded and libraries where imported.

2.Vizualise the data for analysis and for model building.Seaborn library was used to create scatter plots for each of the three features and the target. This is done to make qualitative observations about the linear or non-linear relationships between the features and the target.

3.To calculate  multiple regression coefficient estimate.

4.Feature selection : To determine if all the features helps to determine target. R^2 score was used for feature selection.

5.Data split into training and test data. Two models where built one excluding the newspaper feature and the other model including all the predictors.Model fit and accuracy are determined for the two models using R^2 and RMSE and verify which model satisfy the condition :Maximum R^2 and minimum RMSE for best fit model.

6.To vizualize the residual error and prediction error Yellowbricks a scikit learn API was used.

7.From the previous analysis of the residuals, we concluded that we need to incorporate interaction terms due to the non-additive relationship between the features and target.  Interaction effects is used to include a third feature by taking the product of the other two features in our model. This effect gives a better fit model with a minimum RMSE  value.


