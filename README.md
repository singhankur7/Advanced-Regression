# Advanced Regression Assignment
> Project by Ankur Singh 
>
> This project uses Regularisation to build a advanced regression model for the prediction of the actual value of the prospective properties and decide whether to invest in them or not.
> - Which variables are significant in predicting the price of a house
> - How well the variables describe the price of a house
>
> The project contains:
> - Data Analysis notebook
> - The data set `train.csv`
> - The data dictionary `datainfo.txt`
> - Answers to the Subjective Questions in pdf format `Advanced_Regression_Subjective_Question_Assignment.pdf`


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


  
## General Information

- **General information:** 
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario

- **Business problem:**
Aim is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Assignment Steps performed in the notebook

## Data visualisations
- perform EDA to understand various variables
- check correlation between the variables 

## Data preparation
- clean the data structure
- drop unneccessary variables
- create dummy variables for all categorical features
- divide the data to train and test
- perform scaling
- divide data into dependent and independent variables

## Data modelling and evaluation
- create linear regression model with no Regularisation
- create models using Ridge and Lasso Regularisation
- create additional models model using mixed approach and apply Ridge and Lasso Regularisation
- report the final model



## Conclusions
Please see the notebook for more detailed insights.
1. `GrLivArea` is by far the most important predictor
2. The top variables are intuitive.
3. Lasso is the chosen model for the final model, because it creates a simple model with the top features.





## Technologies Used

![Python]
![NumPy]
![Pandas]
![Matplotlib]
![Seaborn]
![sklearn]
![statsmodels]
![scipy]



## Contact
Created by [Ankur Singh](https://github.com/singhankur7) - feel free to contact me! 
Student at UpGrad: *Master of Science in ML and AI* <br>



