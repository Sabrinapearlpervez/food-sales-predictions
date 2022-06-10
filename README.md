# food-sales-predictions
Sales prediction for food items sold at various stores.

**Sabrina Pearl**

#Predictions of sales based of the products and outlets.

Description of Dataframe

#The data given includes the item identifier, item weight, item fat content, item visibility, item type, item mrp, outlet identifier, outlet establishment year, outlet size, outlet location type, outlet type, and item outlet sales.

Pre-preparation steps

#The pre-preparation steps included getting rid of duplicated values, getting rid of missing values and nans, dropping columns that have no relation. I also created some graphs and visualizations for the outlet establishment year, item visibility, item mrp, and item outlet sales. I only did graphs on the columns that had more relavance to the prediction. 

Visuals

!(<img width="394" alt="Outlet Item Sales" src="https://user-images.githubusercontent.com/103530342/172995341-51afd796-fd0e-4ed1-9453-e096e9ecd050.png">)
#This is a histogram of the outlet item sales. It is important to the predictions of sales because it shows us how many sales each item has by the outlet.

!(<img width="702" alt="Screen Shot 2022-06-09 at 10 29 56 PM" src="https://user-images.githubusercontent.com/103530342/172996775-0dae9756-10c4-43dd-99d6-b5705a2065c4.png">)
#This is a histogram of the outlet location type. This is import to the predictions of sales because it matters as to where the location of the store is. People choose convenience when it comes to the location, as we can see in the graph.

Preprocessing and Predictions

#I made pipelines to OneHotEncode all the categorical columns and to scale all the numeric columns. Got the MAE, MSE, R2, and RMSE for the linear regression model and for the decision tree model. 
#Overall, I think that the decision tree model would be the best fit. The MAE on both is very high. On the linear reg model, the testing set was 905870035782.005. On the decision tree model, the testing set was 905870035782.005. It will have the same amount of errors. The MSE on the linear regression model, on the training set it is very high, which was 972518.2236320331. Yet on the testing set it is low, which was 2.3220874901867352, the testing set will do better than the training. The MSE on the decision tree model was the same as on the linear reg model. On the linear regression model the R2 on the training set was 0.67138705375965, and on the testing set, it was 0.017597914757248718. It has high bias and variance, a model with high bias is consistently unable to make good predictions using any set of features. The R2 on the decision tree model, on the training set was 0.9999999999999998, and the testing set was 0.6198730870145426. It only has high variance, although they both would cause the same amount of errors, the right way to go would be the decision tree model. The decision tree model has a higher chance of accuracy.

#For any additional questions, please contact **sabrinnapearl@gmail.com**
