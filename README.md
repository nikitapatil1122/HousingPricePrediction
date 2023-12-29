# Housing Price Prediction

> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
> Which variables are significant in predicting the price of a house ?
> How well those variables describe the price of a house
> Also, determine the optimal value of lambda for ridge and lasso regression.

## Table of Contents

- [General Info](#general-information)
- [Techniques Used](#techniques-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Regression Machine learning models can be classified Regularized using following methods
- Lasso Regression
- Ridge Regression

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

> Which variables are significant in predicting the price of a house and how well those variables describe the price of a house?
> Features that negatively impacts house prices
- MSSubClass_DUPLEX : -0.221598
- OverallCond_Fair : -0.197726
- KitchenQual_Fa : -0.177264
- BldgType_Twnhs : -0.168710
- KitchenQual_TA : -0.165490
- PropertyAge : -0.155927
- BsmtQual_Gd : -0.145548
> Features that positively impacts house prices
- OverallQual_Very Excellent : 0.988202
- OverallQual_Excellent : 0.757556
- Neighborhood_StoneBr : 0.414192
- OverallQual_Very Good : 0.367675
- Neighborhood_Crawfor : 0.306493 :
- SaleCondition_Partial : 0.253279
- BsmtExposure_Gd : 0.232473
- Neighborhood_NoRidge : 0.231558
- Exterior1st_BrkFace : 0.229110
- GrLivArea : 0.201049
- OverallCond_Excellent : 0.200127


> Duplex type Townhouse dwellings fetches least house price
> Lower the Overall Condition, Kitchen Quality and Basement Quality of the house, lower is the sale price
> Older is the property, lesser is the price
> Higher is the overall quality of the house, more the sale price
> Properties in the neighbourhood of Stone Brook and Crawford and Northridge fetch higher sale price
> New Construction houses have higher sale prices
> Properties with good garden level walls and Brick Face exterior get sold at higher price
> Above ground living area also plays important role in fetching higher sale prices
> Company should purchase the House when the Market Price of the house is lower than the predicted price of the house

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Techniques Used

As our problem aligns with Linear Regression with regularization, we will performed following steps to build the model
- Reading and Understanding the Data
- Data Cleaning & Preparation
- Visualizing the data to check if the Linear Regression can be applied
- Creating dummy variables
- Splitting the Data into Training and Testing Sets
- Training Data Preprocessing
- Modeling on training Data
- Ridge Regularization
- Lasso Regularization
- Model Evaluation

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@nikitapatil1122] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># LendingClubCaseStudy
