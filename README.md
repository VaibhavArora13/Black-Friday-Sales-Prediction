# Black-Friday-Sales-Prediction

![image](https://user-images.githubusercontent.com/110373742/218309362-83ca962b-2803-419c-84c9-565cfc64242c.png)

## Dataset:
This dataset comprises of sales transactions captured at a retail store. This is a regression problem. The dataset has 550,069 rows and 12 columns.
Problem: Predict purchase amount.
Dataset has 537577 rows (transactions) and 12 columns (features) as described below:
1. User_ID: Unique ID of the user.
2. Product_ID: Unique ID of the product.
3. Gender: indicates the gender of the person making the transaction.
4. Age: indicates the age group of the person making the transaction.
5. Occupation: shows the occupation of the user, already labeled with numbers 0 to 20.
6. City_Category: User's living city category. Cities are categorized into 3 different categories 'A', 'B' and 'C'.
7. Stay_In_Current_City_Years: Indicates how long the users has lived in this city.
8. Marital_Status: is 0 if the user is not married and 1 otherwise.
9. Product_Category_1 to _3: Category of the product. All 3 are already labaled with numbers.
10. Purchase: Purchase amount.

## Problem Statement:
Retailis the sale of goods and services from individuals or businesses to the end user The retail industry provides consumers with goods and services for their everyday needs In retail one of crucial part is to understand the consumer behavior and make various arrangements for the sales of the company A retail company “ABC Private Limited” wants to understand the customer purchase behavior ( purchase amount) against various products of different categories They have shared purchase summary of various customers for selected high volume products from last month

## Objective:
I have done EDA in pyMongo and Modelling on pySpark
Objective is to predict Black Friday Sales

## Conclusion:
In this project, we tried to build a model using various algorithms such as Linear regression, Random forest and GB regressor to get the best possible prediction.
The hyperparameter tuned GB regressor gives us the best rmse value and r2 score for this problem.
