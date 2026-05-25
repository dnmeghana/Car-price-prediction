#car price prediction using linear and lasso regression


	
The environment we have used is google colab
	We have uploaded the dataset file named car.csv into google collab.
To run the programming files we have to run each cells from starting.

Steps involved to execute
1. In first cell we have imported the libraries such as pandas,seaborn,sklearn,linear regression and lasso regression models and mathplots.

2. Next we are loading the datas from csv file to pandas dataframe.

3. Then we will do certain operations like inspecting datas,dataset shape,isnull(),count of each values in fuel,seller_type,transmission rows.

4. Then we will replace the text value into integer value by function replace().

5. Assigning the data to X and Y  variables.

6. Splitting the data into training data and test data (X_train, X_test, Y_train, Y_test = train_test_split(X, Y, test_size = 0.1, random_state=2)

7. For linear regression model fitting the training data of X and Y.

8. Predicting on training data

9. R squared error calculation on Y_train data and data prediction.

10. Plotting the scatter graph to R squared value.

11. Predicting on test data.

12. Calculating R squared value on Y_test data and data prediction.

13. Plotting a scattered graph for R squared  value.

14. Same spteps (7-13) followed to Lasso regression model.
