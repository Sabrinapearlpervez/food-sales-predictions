# food-sales-predictions
Sales prediction for food items sold at various stores.

**Sabrina Pearl**

#Predictions of sales based of the products and outlets.

#The data given includes the item identifier, item weight, item fat content, item visibility, item type, item mrp, outlet identifier, outlet establishment year, outlet size, outlet location type, outlet type, and item outlet sales.

#The pre-preparation steps included getting rid of duplicated values, getting rid of missing values and nans, dropping columns that have no relation. I also created some graphs and visualizations for the outlet establishment year, item visibility, item mrp, and item outlet sales. I only did graphs on the columns that had more relavance to the prediction. 

![Screenshot](Outlet Item Sales)
#Histogram of the outlet item sales.

![Screenshot](Outlet Establishment Year)
#Histogram of the outlet establishment year.

#I made pipelines to OneHotEncode all the categorical columns and to scale all the numeric columns. Got the MAE, MSE, R2, and RMSE for the linear regression model and for the decision tree model. 
#Overall, I think that the decision tree model would be the best fit. The MAE on both is very high, it will have the same amount of errors. The MSE in the linear regression model, on the training set it is very high yet on the testing set it is low, the testing set will do better than the training. The MSE in the decision tree model, on both the training and testing set is very high, it will do poorly. On the linear regression model the R2 has high bias and variance, a model with high bias is consistently unable to make good predictions using any set of features. The R2 on the decision tree model only has high variance, although they both would cause errors, the right way to go would be the decision tree model.

#For any additional questions, please contact **sabrinnapearl@gmail.com**
