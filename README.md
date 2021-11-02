# Regularization-models

The purpose of this project was to get familiar with Ridge, Lasso and Elastic Net Regression. In this notebook Regularization models.ipynb i have applied the Regularization models on a dataset and showed the difference between these Regularization models and which one is better to use. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Ridge, Lasso and Elastic Net Regression

In this notebook we will check if either Ridge, Lasso or Elastic Net Regression is better to use. These Regression models can be used if the current model we use for example Multiple Linear Regression (MLR) is overfitting the data. By applying Rige, Lasso or Elastic Net Regression we add a little bit bias to our model which will create a more generalized model and will overcome the problem of overfitting. 

- **Ridge Regression (L2)**
    - Ridge regression uses L2 norm
    - The shrinkage penalty has the effect of shrinking the estimates of coefficinets towards 0
    - The tuning paramter lambda serves to control the relative impact of the penalty term on the regression coefficinet estimates
    - Selecting a good Lambda (alpha) value is critical; cross-validation is used to find the most suitable Lambda(alpha)
    - It is best to apply Ridge Regression after variable standardization
\


 
- **LASSO Regression (L1)**
    - Least Absolute Shrinkage and Selection Operator
    - LASSO Regression uses L1 norm
    - LASSO eliminates the least imporant features fromt he model, it automatically performs a type of feature selection
    - Selecting a good value for Lambda(alpha) we use cross-validation
    - It is best to apply LASSO Regression after variable standardization
\


- **Elastic Net Regression**
    - In Elastic Net Regression we may be able to get the bst of both worlds by making some feature coefficinets to zero while reducing the magnitude of other features
    - Combination of L1 Norm and L2 norm
    - Overall performs good on a large dataset with allot of features
    - Overall of the time works better than Ridge and Lasso Regression
    - Reduces Collinearity
    
- **Lambda(alpha)**
     - If lambda(alpha) = 0 you will get the Linear Regression model
     - If you increase Lambda(alpha) thecoefficients are shrinking. The higher the Lambda(alpha) closer the coefficient will get close to 0
     - Makes the model less complex    
    

**Cross Validation**: you dont woant the test set to leak into your train set. However you want to come up with a performance metric which is the estimate version of the performance metric in the test set.


**Feature selection Embedded Method for linear regression**
- Lasso, Ridge and Elastic Net Regression are part of the feature selection Embedded Method

**Skewed Data**
- In Linear Regrssion models if you have skewed features you should normalize them before applying the model

**Permornce Metrics**
- Mean Absolute Error(MAE): Magnitude of difference between the prediction of an observation and the true value of that obeservation
- Mean Squared Error (MSE): The average squared difference between predicted and true values of that observation
- Root Mean Squared Error (RMSE): The standard deviation of the residuals (prediction errors)
- R2 Square: The percentage of variation explained by the relationship between two variables





