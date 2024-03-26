# Advanced Regression Assignment - Surprise Housing
> An Advanced Regression Assignment with Lasso and Ridge Regularisation


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Advanced Regression performed on Surprise housing dataset 
- There we performed regulairation for tackling overfitting
- We have two methods for regularisation - Lasso and Ridge
- This assignment is part of UpGrad AIML Course

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
    - Here, We can clearly observe that the Mean Squared Error of Lasso is slightly lower than that of Ridge.
    - Since Lasso helps in feature reduction and helps to increase model interpretation by taking the magnitude of the coefficients thus Lasso has a better edge over Ridge
    - Thus based LASSO Regularization the TOP 5 Predicted variables are :
        1. OverallQual - With the increase of the overall material and finish of the house, the house price also increases.
        2. GrLivArea - With the increase of size of the living area square feet, the house price also increases.
        3. YearBuild - With the increase of age of the house, the price gradually increases. 
        4. Total_sqr_footage - With the increase of the overall square feet of the house, the house price also increases.
        5. Neighborhood_StoneBr - Depending upon the Stone Brook location, the house price also increases


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib
- statsmodels
- scikit learn

## Contact
Created by [@AdiR1308] - feel free to contact me.