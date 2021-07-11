# Loan-Default-Prediction
Data set: 
The set was taken from kaggel.com for educational purposes. Data consists of 1500 row representing bank customers and 12 columns representing various customer information.

Objective:
Build a prediction model to establish whether a customer will default on loan payments.

Process:
Logistic Regression model was chosen to predict default customers. 
Backward substitution was used to filter out the columns with no statistical significance with Gretl aiding in finding p-values of the coefficients.
4 coefficients were chosen for an optimal solution: age of the borrower, number of years in the job, debt to income ratio, credit card debt
Model was implemented using sklearn library from Python.

Solution: 
Logistic Regression Model was built for prediction with accuracy given in the report

