# Workplan

## Basic Project Description
Problem Statement
The banking industry faces a significant challenge with customer churn, where customers close their accounts to take their business elsewhere. This issue not only affects the banks' customer base but also impacts profitability since acquiring new customers is considerably more expensive than retaining existing ones.
Importance of Customer Retention

Reducing churn is crucial for maintaining a healthy customer base and ensuring the bank's profitability. Effective churn prediction and management strategies can significantly enhance customer retention efforts.



### Team members

*Michael Ashia
*Blessing Sekeramavi
*Simon Addae
*Keren Omare-Baah

### Main Goal or Research Question

*Identify key predictors of churn risk: Determine which demographic, behavioral, and    transactional attributes of customers most strongly predict churn.

*Develop a predictive model: Create a machine learning model to accurately predict the likelihood of individual customers churning.

*Optimize retention efforts: Utilize model insights to target retention strategies towards high-risk customer segments effectively.


### Data

*This Kaggle dataset contains 10,000 customers of a bank with their demographic info, product usage data, credit data, and a churn label: https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling?select=Churn_Modelling.csv*

### Methods

1. Data Preparation and Exploration:
Use libraries like Pandas for data manipulation and exploration.
Load our bank data into a Pandas DataFrame.
Explore the data using descriptive statistics, visualizations, and correlation analysis to understand the relationships between variables and identify potential predictors of churn.

2. Feature Engineering:
Based on our exploratory analysis, engineer new features or transform existing ones to better capture patterns related to churn.
This could involve creating new variables, encoding categorical features, handling missing values, scaling numerical features, etc.

3. Machine Learning Model Development:
Split our data into training and testing sets.
Select appropriate machine learning algorithms such as logistic regression, random forest, or neural networks.
Train our models on the training data and tune hyperparameters using techniques like cross-validation.
Evaluate model performance using evaluation metrics like ROC-AUC, accuracy, precision, recall, etc., on the testing data.







