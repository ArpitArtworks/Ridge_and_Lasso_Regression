# Ridge and Lasso Regression
A US-based housing company named Surprise Housing is looking at prospective properties to buy to enter the Australian market. 
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
Model the price of houses with the available independent variables. 
This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the background of your project?
Surprise Housing is looking at prospective properties to buy to enter the Australian market. 
Surprise Housing uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia.

- What is the business probem that your project is trying to solve?
The company wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.
3. Also, determine the optimal value of lambda for ridge and lasso regression.

- What is the dataset that is being used?
A comprehensive details about the house in 81 variables.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Keep a check on these predictors affecting the price of the house.
The higher values of positive coeeficients suggest a high sale value.
Some of those features are:-
Feature Description
TotalBsmtSF Total square feet of basement area
BsmtFullBath_3 Basement full bathrooms
KitchenQual_5 Kitchen quality
OverallQual_8 Rates the overall material and finish of the house
Neighborhood_Crawfor Physical locations within Ames city limits

The higher values of negative coeeficients suggest a decrease in sale value.
Some of those features are:-
Feature Description
BsmtUnfSF Unfinished square feet of basement area
GarageType_Other Garage location
BldgType_3 Type of dwelling
When the market value of the property is lower than the Predicted Sale Price, its the time to buy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- missingno - version 0.4.2
- sklearn - version 0.24.2
- statsmodels - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by IIIT Bangalore and Liverpool John Moores University


## Contact
Created by [@ArpitArtworks] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->