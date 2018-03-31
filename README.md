# Apartment-price-prediction-with-regression


Methods & Result:
1.	We import our dependencies , for linear regression we use sklearn (built in python library) and import linear regression from it.
2.	We then initialize Linear Regression to a variable reg.
3.	Now we know that prices are to be predicted , hence we set labels (output) as price columns and we also convert dates to 1’s and 0’s so that it doesn’t influence our data much . We use 0 for houses which are new that is built after 2014.
4.	We again import another dependency to split our data into train and test.
5.	I’ve made my train data as 90% and 10% of the data to be my test data , and randomized the splitting of data by using random_state.
6.	So now , we have train data , test data and labels for both let us fit our train and test data into linear regression model.
7.	After fitting our data to the model we can check the score of our data ie , prediction. in this case the prediction is 71%
We have also used Gradient Boosting Regression:
 In this case accuracy is 84%
