# Car Price Prediction

## PROBLEM STATEMENT¶

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

* Which variables are significant in predicting the price of a car
* How well those variables describe the price of a car

## BUSINESS GOAL

We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## APPROACH

* Analyzed 20+ features of a car like fuel type, door number, drive wheel, engine location etc.<br>
* Vizualized the different features and their effect on the price of the car.
* Observed the VIF and p values of the features to select the ones important for price prediction and evaluated the accuracy of multiple models.

![carbody price](https://user-images.githubusercontent.com/24591039/219856077-c87db345-a655-4811-8a1d-c5b8bae4c519.png)

[Fig above] Average price of cars with different body types

![CarCount](https://user-images.githubusercontent.com/24591039/219856104-08138d9c-f7e8-4973-9cca-dd238d8b53bd.png)
 
[Fig above] Count of cars of different companies

![CarNameAvgPrice](https://user-images.githubusercontent.com/24591039/219856151-1fe65d01-577a-4462-aced-64cf051b10a3.png)

[Fig above] Average car prices - Company wise

![carPriceDist](https://user-images.githubusercontent.com/24591039/219856170-3075d04b-4e97-442e-aa1c-842104a605e8.png)

[Fig above] Overall car price distribution

![ModelTrainingError](https://user-images.githubusercontent.com/24591039/219856181-2acdc0f1-4872-4016-8435-f6f795de9e2c.png)

[Fig above] Model performance on training set

![ModelTest](https://user-images.githubusercontent.com/24591039/219856194-5ae21ee8-5b4c-486f-b0e4-3451ad2d56c9.png)

[Fig above] Model performance on test set

Multiple models were trained and analyzed to fine tune and eliminate the variables which were not required. Recursive Feature Elimination and p-values were observed to remove unwanted features

