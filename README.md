# Big-Mart-Sales-Prediction
## Big Mart Case
In thes case we have the train.csv & test.csv file. In the train.csv file consisit of different columns, from that we have to predict the sales value for the test.csv file.

## Train.csv File Columns Name
1. **Item_Identifier:** Code given to items
2. **Item_Weight:** Weight of an item
3. **Item_Fat_Content:** Fat content of the item like low, high etc
4. **Item_Visibility:** A continuous value indicating the visibility of the item for a customer
5. **Item_Type:** Type of the item like dairy, vegetables etc
6. **Item_MRP:** Maximum retail price of the item
7. **Outlet_Identifier:** Code given to outlets
8. **Outlet_Establishment_Year:** Year of establishment of an outlet
9. **Outlet_Size:** Size of an outlet like medium, high etc.
10. **Outlet_Location_Type:** Location of the outlet in a city like Tier1, 2 etc.
11. **Outlet_Type:** Type of the outlet like supermarket, grocery shop etc.
12. **Item_Outlet_Sales:** Sale value of an item in outlet. It is a target variable.

## Test.csv File Columns Name
All the columnes that are present in the train.csv file are presenr in test.csv file. Expect the **Item_Outlet_sales** column.

## Tasks
* Use the Train.csv file for fitting the models (Divide this file into training set and testing set)
* Treat the missing values appropriately
* Convert the categorical data into numerical data appropriately, if necessary.
* Normalize the data, if required.
* Fit linear regression model and compute RMSE and R-Square.
* Apply regularization techniques on the data to check whether they are better than the basic linear model. Loop through various regularization parameters to display and compare     R-Square.
* Fit the residual plots in all cases.
* Give your analysis on which of the independent variables have significant impact on the Sales of an outlet. Call it as a best model.
* Using this best model, predict the values of sales for the data given in the file Test.csv and compute RMSE and R-Square

## Models & Their Accuracy
1. **Linear Regression:**
   * **R2_Score = 75.70%**
   * **RMSE = 0.519**
   
2. **Lasso Regression:**
   * **R2_Score = 74.68%**
   * **RMSE = 0.53**
   
3. **Ridge Regression:**
   * **R2_Score = 75.57%**
   * **RMSE = 0.519**
   
   ## Predicted Column
   
   ![Output Big Mart](https://user-images.githubusercontent.com/62636740/93588077-7f230b80-f9c8-11ea-9769-2f1af0085962.PNG)
