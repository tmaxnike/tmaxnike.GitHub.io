
### Introduction

 Customer churn is the most important factor for banks and other financial institutions. The main reason for this is retaining the existing customer is more cost-effective and more profitable. 
 The rapid advancement in technology and the invention of new banking services have also made it more important for banks to understand which factors influence customer churn and develop effective strategies to minimize it. 
 In this context, the applications of Artificial Intelligence (AI) and machine learning can be used to predict customer churn and can provide valuable insights and help banks take proactive steps to retain a maximum number of their customers.
 The main purpose of this object is to develop a classification model that can predict whether a bank customer will churn or not with the highest accuracy. The dataset used in this task is obtained from Kaggle.
 The dataset contains information about various customer attributes such as demographics, and financial and account-related activities. 
 We can find factors that influence customer churn by analyzing this dataset and can provide recommendations for the bank to reduce customer churn and improve customer retention rate and satisfaction.


### Data Preparation

o	Drop unnecessary columns.

o	Replace age variable with log of age.

o	split data into train and test data

o	Create dummy variables for train and test data.


### Observations

o	Highest proportion of customers from Germany have churned out.

o	Second highest proportion of customers from Spain have churned out.

o	Proportion of churned customers varied by geographical location.

o	This could play an important role for predicting whether the customer will churn out or not.

o	Female customers are more likely to churn out as compared to male customers.

o	Non-Active customers are more likely to churn out as compared to active customers. 


### Conclusions

o	Geography and Age plays an important role for predicting if a customer churned out or not.

o	Decision Tree model predicts customers churn with approximately 80% accuracy.

o	Classification Report and ROC curve suggests that model has strong predictive power.

o	Age, Has Credit Card, Geography, Balance, and Number of Products been useful for predicting whether the customer will churn or not.


### Dataset 

o	Churn Modelling

https://www.kaggle.com/datasets/santoshd3/bank-customers
