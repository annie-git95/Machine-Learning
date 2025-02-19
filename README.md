# Loan Interest Rate Prediction
This project aims at predicting the loan rate any loan application would get given certain variables. The metadata and the holdout set is provided. 

Step 1:
Cleaning and Data Preparation: There are several entries where values have been deleted to simulate dirty data. 
Note that some of the missing values are truly blank (unknown answers) and thus were impossible to clean; I used my discretion.

Step 2:
Model Building: Build Machine Learning/Statistical models in Python to predict the interest rate assigned to a loan.
When writing the code associated with each model, the first part produces and saves the model, 
followed by a second part that loads and applies the model.

Step 3:
Testing: Model were tested using data found within the "Holdout" file. 

For this exercise, I used 3 Regression models: Decision Trees, Ridge CV and XGBoost. The data was grouped into categories where required, and fit transformed using label encoder.The first technique used was Ridge CV, which has inbuilt cross validation based on ridge regression. Its results were also comparable to decision trees. Out of the three XGBoost was the most powerful technique which has gradiant boosted decision trees - it is used widely to improve accuracy of structured data. It tests the data on several iterations, accounts for multicollinearity, performs cross validation and suggests the most accurate model.
