# Analyzed Data to create a Machine Learning Model for Food Sales Predictions 
## Business Problem:
In this project I used historical food sales data to predict the future demand of food at a grocery chain. I used various features like store size, store type, Item Sales etc. to gain insights into how these features can affect an Outlets' sales of food items. 
# Author: Abdelhamead Ibrahim
# Data:

The Data conisited of a total of 12 columns with various information. This included the following: 

1. Item_Identifier 8523 non-null object
2. Item_Weight 7060 non-null float64
3. Item_Fat_Content 8523 non-null object
4. Item_Visibility 8523 non-null float64
5. Item_Type 8523 non-null object
6. Item_MRP 8523 non-null float64
7. Outlet_Identifier 8523 non-null object
8. Outlet_Establishment_Year 8523 non-null int64
9. Outlet_Size 6113 non-null object
10. Outlet_Location_Type 8523 non-null object
11. Outlet_Type 8523 non-null object
12. Item_Outlet_Sales 

### Methods
The Data preparation steps I used were to first explore the Dataset using pandas as well as data visualization tools like matplotlib and seaborn to explore the Dataset. After my initial exploration I determined that total outlet sales was my target for prediction. I used the other features to predict the future data by using the sklearn tool. After throughly analyzing the data I realized that the hyperparameters needed to be tuned in order to improve the models' accuracy.



### Results:
For the first model there was a large variance of R2 scores which is the measure of the coefficent for the difference between the two models the Training model and the Testing model. 

For the second model the R2 score was better but the R2 score was .60 for our Training model and .59



![download](https://user-images.githubusercontent.com/4527669/181692531-5906e4a0-961c-4351-8eb7-6470eb4033a7.png)


This heatmap displays the correlation between price and other features in the dataset. There is only one feature with a strong correlation to price


# Model
![download-2](https://user-images.githubusercontent.com/4527669/181692823-6348513e-6d24-4d01-9bd3-c6ace0ab050b.png)


Report the most important metrics
For the first model there was a large variance of R2 scores which is the measure of the coefficent for the difference between the two models the Training model and the Testing model. 
# Linear Regression Model (Model 1) 
- Model Training R2:0.6315530896792858
- Model Testing R2:-8.656163822130806e+20

For the second model the R2 score was better but the R2 score was .60 for our Training model and .59 this means that the difference between the Train and test scores was significantly reduced. This makes our model much more accurate. 
# Decision Tree Model (Model 2) 
- Train Model Score:0.6042066848171654
- Test Model Score:0.5960564372160062

### Recommendations:
My Recommendation is that we use this model to predict Item Outlet Sales

### Limitations & Next Steps:
The Limitations that I see is that that this data covers the sales of outlets within a specific region. We may need more data to accurately predict Item outlet sales on a National or Statewide level. 


For further information
For any additional questions, please contact me by email @ abdelhameadibrahim@gmail.com 
