# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
  Aim is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
  
  The company wants to know:

  Which variables are significant in predicting the price of a house, and

  How well those variables describe the price of a house.

  Also, determine the optimal value of lambda for ridge and lasso regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

1) Optimum Value in case of Ridge and Lasso are :

   Ridge - 5

   Lasso - 0.0004

2) Mean Square error are :

   Ridge - 0.01363

   Lasso - 0.01346

3) Mean Square error of lasso is slightly less than Ridge Also, since Lasso helps in feature reduction, Lasso has a better edge over Ridge.

4) As per the Lasso the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house,    Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet and the Basement finished square feet area.

Below Variable are significant in predicting the Value of house price.

1) MSZoning_RL	
2) GrLivArea
3) MSZoning_RM
4) OverallQual
5) MSZoning_FV
6) TotalBsmtSF
7) OverallCond
8) Foundation_PConc
9) GarageCars	
10) BsmtFinSF1

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.0
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project was created to explore and apply our Advance regression learning.


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
