# Advanced Regression Assignment
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know —
-- Which variables are significant in predicting the price of a house, and
-- How well those variables describe the price of a house.

## Table of Contents
- [Advanced Regression Assignment](#advanced-regression-assignment)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Conclusions](#conclusions)
  - [Technologies Used](#technologies-used)
  - [Acknowledgements](#acknowledgements)
  - [Created By](#created-by)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- You are required to model the price of houses with the available independent variables. 
- This model will then be used by the management to understand how exactly the prices vary with the variables.
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
- Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- High values of +ve coeeficients suggest a high sale value, some of features are top 5:
-- GrLivArea, OverallQual, OverallCond, TotalBsmtSF, BsmtFinSF1
- High values of -ve coeeficients suggest a decrease in sale value, some of  features are top 5:
-- KitchenQual_TA, KitchenAbvGr, BsmtQual_TA, EnclosedPorch, MSSubClass
- Market value of the property is less than the Predicted Sale Price then time to buy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python - Version 3.9.7](https://www.python.org/download/releases/3.0/)
- [numpy - Version 1.20.3](https://github.com/numpy)
- [pandas - Version 1.3.4](https://github.com/pandas-dev/pandas)
- [matplotlib - Version 3.5.1](https://github.com/matplotlib)
- [seaborn - Version 0.11.2](https://github.com/seaborn)
- [Jupyter Notebook - Version 6.4.5]
- [Anaconda - Version 2.2.0]
- [sklearn]
- [statsmodels]

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- The project reference course details from upGrads .
- PI session and Live presention about the brief of the project [Manish] 


## Created By 
- [Manoj Bisht](https://www.linkedin.com/in/manoj-bisht-b293a657/)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->