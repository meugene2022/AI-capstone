# Used Car Predtion Project

## Goal

This project aims to predict car prices using the cravana used car dataset found [here.](https://www.kaggle.com/datasets/ravishah1/carvana-predict-car-prices) 


# Overview


* Using Data, we want to predict the price of used cars in the currently declining car market. With used car Giants on the brink of bankruptcy we can used ML to capitalize on a volitile market.


# Business Understanding


* Understanding the market- The online used car market is struggling post pandemic
* Utilizing Carvana’s Inventory- The Dataset Utilizes Carvana's Used Car inventory to get a understanding of the state of the market
* We are going to use Machine learning to analyze and understand the inventory listed above to predict car prices

# Data Understanding 


* Carvana Used Car Inventory
* The dataset contained 4 columns I used 3 for analysis 
* Contains over 20 thousand used cars
* Ranging from  1995 to 2022
* The average price of a car in their inventory is 20k
* The average amount of miles on their cars are 54k
* There are some older antic cars as well some new high-end cars We will not be focusing on those 


# Data Analysis
* There is a positive corelation between the year of the car and the price
![Correlation between price and year](Images\Correlation between year and price.png "Correlation between year and price")
* There is a negative corelation between the price of the car and the amount of miles it had
![Correlation between price and miles](Images\Correlation between price and mile.png "Correlation between price and mile")
* The most popular cars in the inventory were mid-small size sedan such as Toyota Corolla and Honda CR-V
![most popular cars](Images\most popular cars.png "most popular cars")
* The most popular model years in the inventory were 2015 and 2019 
![most popular model years](Images\model years.png "most popular model years)


# Model Prediction 


Three models were tested to find the most accurate one to use for prediction.
* Linear Regression had an error of 3000
* XB Boost had an error of 2500
* Decision Tree Regressor had the lowest amount error of around 1600


# Conclusion 

The model predicted that the company should spend 18500$ on a used car which is 1500$ below the average price. 
There is room for imporve especially in the dataset that will help contribtue to the accuracy of the model.
The dataset had year/miles/price/ make and model, variables such as mpg,fuel type, and interest rate would contribute to the accuracy.


# Navigating this Repository


The presentation about this project can be found [here.](https://github.com/meugene2022/AI-capstone/blob/main/AI_Capatone_Powerpoint.pdf) it contains a brief summary of the data and the prediction.

The final notebook can be found in the file can be found [here](https://github.com/meugene2022/AI-capstone/blob/main/Capstone%20Project%20Notebook.ipynb) contains the data exploration, cleaning and analysis that supported our final recommendations for used car Predction.

The data used in this analysis is located in the carvana dataset [here](https://github.com/meugene2022/AI-capstone/blob/main/carvana.csv)

