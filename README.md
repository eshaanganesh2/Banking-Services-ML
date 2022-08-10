# Predicting Banking Services Availabilty using Machine Learning 

The project consists of 3 models:
* **Loan Repayment prediction model**: Through this model, if a customer applies for a loan, banks would be able to determine if it is profitable to provide the requested loan, i.e.
a prediction would be made whether the customer would be able to successfully repay the loan.

* **Customer Satisfaction prediction model**: Through this model, it is identified if a particular customer is satisfied by the bank's services or not. For this, various behavioural details of the customer are given as input to the Customer Satisfaction Prediction Model (eg Credit score, number of bank products owned, frequency of service utilization, etc.)

* **Credit Default prediction model**: Through the Customer Satisfaction prediction model, if it is obtained that the customer is unsatisfied, we then feed the customer’s past credit card bill details to the Credit Default Prediction Model. These details mainly include the user’s credit card statements for the past six months. If the model's output is that the customer will not default in credit card payments, the bank can look forward to retaining the customer by offering more competitive offers/schemes.  

**Shapely Additive Explanations (SHAP) analysis** has also been performed for each of the models, in order to help identify the direction and extent of a particular feature in impacting the final decision of the respective models.
