# House Price Prediction : Advanced Regression
> A US-based housing company named Surprise Housing has decided to enter the Australian market.
> The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

>



- Objective of the Project?
> Model the price of houses with the available independent variables.
> This model will then be used by the management to understand how exactly the prices vary with the variables.
> They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
> Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- Approach to solve this business problem
> Step 1 : Data Understanding and Exploratory Data Analysis ( EDA )
> Step 2 : Data Preperation
> Step 3 : Training the model
> Step 4 : Model Prediction and Evaluation
> Step 5 : Ridge and Lasso Regularization
> Step 6 : Conclusions and Results

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimal value of LAMBDA we got in case of Ridge and Lasso is :

>Ridge - 4.0 (lowest MSE value)

>Lasso - 0.0002

>The r2 value for Ridge and Lasso is:

>Ridge - Train = 0.947 , Test = 0.869

>Lasso - Train = 0.945 , Test = 0.866

>The Mean Squared error for Ridge and Lasso is:

>Ridge - 0.00379

>Lasso - 0.00392

>Proceeding with lasso as coefficients are closer to 0

>LASSO Regularization the TOP 5 Predicted variables

>GrLivArea
>OverallQual
>YearBuilt
>BsmtQual_Ex
>BsmtExposure_Gd

