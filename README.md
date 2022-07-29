# Need more Data to Analyze food sales 
Business Problem: 
In this project I used previous food sales data to predict the future demand of food at a grocery chain. I used various features like store size, store type, Item Sales etc. to gain insights into how these features can affect an Outlets' sales of food items. 
Author: Abdelhamead Ibrahim 
Data:
The Data conisited of a total of 12 columns with various information. This included the following: 

0 Item_Identifier 8523 non-null object

1 Item_Weight 7060 non-null float64

2 Item_Fat_Content 8523 non-null object

3 Item_Visibility 8523 non-null float64

4 Item_Type 8523 non-null object

5 Item_MRP 8523 non-null float64

6 Outlet_Identifier 8523 non-null object

7 Outlet_Establishment_Year 8523 non-null int64

8 Outlet_Size 6113 non-null object

9 Outlet_Location_Type 8523 non-null object

10 Outlet_Type 8523 non-null object

11 Item_Outlet_Sales 

Methods
The Data preparation steps I used were to first explore the Dataset using pandasas well as data visualization tools like matplotlib and seaborn to explore the Dataset. After my initial exploration I determined that total outlet sales was my target for prediction. I used the other features to predict the future data by using the sklearn tool. 



Results
For the first model there was a large variance of R2 scores which is the measure of the coefficent for the difference between the two models the Training model and the Testing model. 

For the second model the R2 score was better but the R2 score was .60 for our Training model and .59 for our testing a score for both Training and Testing that is close to .90 would be preferred. 



![download](https://user-images.githubusercontent.com/4527669/181692531-5906e4a0-961c-4351-8eb7-6470eb4033a7.png)


This heatmap displays the correlation between price and other features in the dataset. There is only one feature with a strong correlation to price


Model
![download-2](https://user-images.githubusercontent.com/4527669/181692823-6348513e-6d24-4d01-9bd3-c6ace0ab050b.png)


Report the most important metrics
For the first model there was a large variance of R2 scores which is the measure of the coefficent for the difference between the two models the Training model and the Testing model. 

Model Training R2:0.6315530896792858
Model Testing R2:-8.656163822130806e+20

For the second model the R2 score was better but the R2 score was .60 for our Training model and .59 for our testing a score for both Training and Testing that is close to .90 would be preferred. 


Recommendations:
My Recommendation is that I need more data in order to build a better model in order to predict future food sales.

Limitations & Next Steps

For further information
For any additional questions, please contact me by email @ abdelhameadibrahim@gmail.com 
