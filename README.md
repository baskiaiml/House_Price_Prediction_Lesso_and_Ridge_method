# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house.
How well those variables describe the price of a house.
Finally, determine the optimal value of lambda for ridge and lasso regression.


## Conclusions
- The optimal lambda value in case of Ridge and Lasso is as below:
    - Ridge - 10
    - Lasso - 0.4
    
- The Mean Squared error in case of Ridge and Lasso are:
    - Ridge - 0.117382
    - Lasso - 0.119098
    
- Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

- Hence based on Lasso, the factors that generally affect the price are Lasso Important predictor variables are listed below: 'LotFrontage', 'BsmtUnfSF', 'OverallCond', 'OverallQual', 'BsmtFullBath', 'LotArea'

- Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.



## Contact
Created by [@baskiaiml] - feel free to contact me!
