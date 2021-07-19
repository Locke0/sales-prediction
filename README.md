# Sales Prediction
This is a sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.

### Data Dictionary
|Variable Name|Description|
|-------------|-----------|
|Item_Identifier|Unique product ID|
|Item_Weight	|Weight of product|
|Item_Fat_Content	|Whether the product is low fat or regular|
|Item_Visibility	|The percentage of total display area of all products in a store allocated to the particular product|
|Item_Type	|The category to which the product belongs|
|Item_MRP	|Maximum Retail Price (list price) of the product|
|Outlet_Identifier	|Unique store ID|
|Outlet_Establishment_Year	|The year in which store was established|
|Outlet_Size	|The size of the store in terms of ground area covered|
|Outlet_Location_Type	|The type of area in which the store is located|
|Outlet_Type	|Whether the outlet is a grocery store or some sort of supermarket|
|Item_Outlet_Sales	|Sales of the product in the particular store. This is the target variable to be predicted.|

### Data Visualization

![image](https://user-images.githubusercontent.com/47510557/126090838-4c27d7cc-aad2-4c74-9d37-695f5643dc38.png)

This bar plot shows that the type of items have little effect on the sales.

![image](https://user-images.githubusercontent.com/47510557/126091200-1561378d-0c64-403b-8d54-7ea499c1bc5c.png)

In this histogram, item with low fat content drops off much faster compared to items with regular content. Especially at higher sales, items with regular fat content is also as high as items with low fat content. This implies that although more items with low fat content have high sales, regular items are more popular.

![image](https://user-images.githubusercontent.com/47510557/126091780-b4566aa5-db55-4fef-a13a-4fdd100326c2.png)

This boxplot shows that items with low fat content has a bigger range of sales and both types of items have similar median sales.

![image](https://user-images.githubusercontent.com/47510557/126091991-1021034b-5240-4290-a6cf-9a7aad9722a8.png)

This confusion matrix shows that Maximum Retail Price of the product (Item_MRP) has the most influence on sales of the products.


### KNN Regression
Predictions:

![image](https://user-images.githubusercontent.com/47510557/126095472-e1907bd5-1faa-468d-acc0-51e6cc8a5b7d.png)

RSME is 1202.2196980371232 and the score is  0.47613479504302514
