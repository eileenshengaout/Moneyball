## MoneyBall Baseball Analytics 
In this project, my teammates and I took a dataset containing baseball statistics from Major League Baseball and used this dataset to find the best possible model that predicts the amount of games won by each team. 

### Dataset
Here is link to the dataset: 
https://www.kaggle.com/datasets/wduckett/moneyball-mlb-stats-19622012 

### Markdown File & Code 
***Final Project STAT 4230.Rmd*** contains the R code, where we ran simple regression and multiple regression models, tested assumptions (constant variance, independence, normally distributed, linearity), and selected variables to find a model that predicts the amount of games won the best.   

### Downloaded PDF File of Report 
***STAT 4230 Final Project .pdf*** is our final report which explains our process in detail. We found that when running simple regression models for each independent variable against the amount of games won, each model has atleast one condition that is violated. Furthermore, the R^2 values are low for plotting one predictor against the dependent variable. When testing the multiple linear regression models, we found that the conditions were satisfied. Not all variables were useful in determining the best model when using R^2 and AIC as the criteria. Using cook's distance to determine highly influential points, we found our final two models based on these two different criterias. One model had two predictors with an R^2 of 88.62 and adjusted R^2 of 88.6, and the other model had 6 predictors with an R^2 of 89.32 and adjusted R^2 of 89.27. Given that the adjusted R^2 was higher in the model with 6 predictors, we concluded that the model with 6 predictors is the best possible model due to this higher score. When running both models using the dataset  ***2013MLB.csv***,  we found that our final model predicts the total number of wins as a team very well. 












