# Phase_3_Project

Overview

The main focus of this project is to build a classifier to predict whether a customer will soon stop doing business with SyriaTel, a telecommunications company. The data set which was downloaded from Kaggle consists of 21 features and 3333 rows containing SyriaTel’s churn metrics.The process outline initiates by identifying the top attributes of churn and then creating a final machine learning model to predict whether or not a customer will soon churn. Several machine-learning models were created and their performances were compared to decide on a final predictive model that the stakeholder can use on their current database.

Business Understanding. 
Objectives

SyriaTel is among the biggest telecommunications companies in Damascus, Syria that supplies mobile phones services. Being a big company, customer shurn could be a big problem since there is a possible loss of customers in the market to similar competitors. It will be less costful for SyriaTel to retain its custmers than to acquire new ones. Therefore to increase its revenue on customer retention it’s important to seek and develop means to predict potential customer to churn. Therefore, finding factors that increase customer churn is important to take necessary actions to reduce this churn and position the company in a favourable competitive edge. The main contribution of this project is to develop a churn prediction model that will assist the company to predict customers who are most likely subject to churn.

Method
The objective will be achieved by first assessing the feature importance on the below attributes and determining which tend to be the strongest predictors of churn. Then apply these attributes to several classification machine learning models to classify at risk customers in the present and in the future.

Method Outline
After analyzing the data the project is identified as a classification problem. The target variable ‘churn’ creates a binary classification. For this instance the balance of the target variable will be investigated Since the target variable is imbalanced, the Accuracy score will not be used, instead the Recall score will be more important due to the problem at hand.

Type Errors
The nature of this problem is framed by the fact that losing current customers is less expensive than gaining new customers. Therefore, it is much better to retain the customers that the company currently has rather than to acquire new customers.
Incorrectly classifying a false negative would pose a higher threat than a false positive because a false negative would mean that the reality of a customer canceling would have been overlooked. The occurrence of the false-negative occurring is referred to as a type two error. In order to rank the classifiers on how well they minimized false negatives, measurement of recall has been utilized.

Conclusions
The importance of this type of research in the telecom market is to help companies make more profit. It has become known that predicting churn is one of the most important sources of income to telecom companies. Hence, this research aimed to build a system that predicts the churn of customers in SyriaTel Telecom Company. Three seperate models were created; 
1.	Logistic Regression 
2.	Decision Tree models
3.	Gradient Boosting
   
Recommendations
Based on the feature analysis and the results from the final model it is clear that customer service calls and day call charges have the strongest impact on customer churn. 
SyriaTel can do the following to reduce churn:
Customers who called customer service more than three times should be reviewed with more importance. Track metrics from customer service calls. Are clients calling about the same issues? Once we know why these clients are calling, we can better alleviate their pain by addressing and correcting these issues.
Re-evaluate pricing structure for day calls. Consider a tiered pricing structure past a certain dollar amount.



