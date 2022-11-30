# Project Name  SURPRISE HOUSING ASSIGNMENT
> Outline a brief description of your project.
    A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
    The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)  A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
* [Technologies Used](#technologies-used)  Sklearn,Seaborn,numpy,pandas
* [Conclusions](#conclusions) The R2 Score of Ridge is 0.89 in training set where as nearly 0.86 in  test set and the difference is not more than 4.
* [Acknowledgements](#acknowledgements) 
   Advanced linear regression using Ridge and Lasso
<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.  
   A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- What is the background of your project?
  The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
   
- What is the business probem that your project is trying to solve?
    
    The company wants to know:

    Which variables are significant in predicting the price of a house, and
    How well those variables describe the price of a house.

    Also, we need to determine the optimal value of lambda for ridge and lasso regression.

- What is the dataset that is being used?
    train.csv


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
     Ridge Regression is showing better than Lasso Regression as R2 Score(Test) is higher,RSS and MSE is comparatively lower than Lasso.
- Conclusion 2 from the analysis
    The R2 Score of Ridge is 0.89 in training set where as nearly 0.86 in test set and the difference is not more than 4.
- Conclusion 3 from the analysis
    The optimum value of hyperparamete is 0.8
- Conclusion 4 from the analysis
    Top 10 best predictor for Ridge are -
    overallQual
    TotalBsmtSF
    GrLivArea
    GarageArea
    MSZoning_FV
    overallCond
    1stFlrSF
    MSZoning_RL
    2ndFlrSF
    kitchenQual


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - numpy
- library - panda
- library - sklearn,statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by... Upgrad
- References if any...
-
## Contact
Created by [@githubSanghamitraa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->