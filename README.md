Advanced Regression Model for finding the predictor variables to predict the house pricing.

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem Statement : A US-based housing company named "Surprise Housing" has decided to enter the housing market of
Australian. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. The company wants to know Which variables are significant 
in predicting the price of a house and how well those variables describe the price of a house. Based on various market surveys, the consulting firm has gathered a large dataset of different types of houses across the American market.

Business Goal : Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. Determine the optimal value of lambda for ridge and lasso regression.
This model will then be used by the management to understand how exactly the prices vary with the variables They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. The model will be a good way for the management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Conclusion : The optimal lambda value in case of Ridge and Lasso is as below:

Ridge - 10 Lasso - 0.0004 The Mean Squared error in case of Ridge and Lasso are:

Ridge - 0.013743 Lasso - 0.013556 The Mean Squared Error of Lasso is slightly lower than that of Ridge

Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet and the Basement finished square feet area

Therefore, the variables predicted by Lasso in the above bar chart are significant variables for predicting the price of a house.




## Contact
Created by [Shivendu-Sharma17] - feel free to contact me!


