# job-a-thon-Aug2022

##Problem statement-
Most organizations today rely on email campaigns for effective communication with users. Email communication is one of the popular ways to pitch products to users and build trustworthy relationships with them.


Email campaigns contain different types of CTA (Call To Action). The ultimate goal of email campaigns is to maximize the Click Through Rate (CTR).


CTR is a measure of success for email campaigns. The higher the click rate, the better your email marketing campaign is. CTR is calculated by the no. of users who clicked on at least one of the CTA divided by the total no. of users the email was delivered to.


Approach:
This is a regression problem i.e we have to predict a value.
Data Modelling and Model Selection is done in Four Steps :
• Data-Preprocessing
• Data Visualization
• Feature Engineering
• Machine Learning Algorithm (Modelling Part)

Data Preprocessing:
Perform data pre-processing wherever needed
• Check for Missing Values and Imputing it.
• Checking If there is Not Null Values and Dropping or Deleting it.
• Check for the Data Types of DataFrame. Then convert object datatypes to integer data type using ordinal encoder
• using boxplot check outlier.


Data Visualization:
• Derive some relevant insights out of the given data using different approaches
(Such as using Seaborn/Matplotlib.)
• Detecting Outliers
• Relevant Insights
• For Numerical columns plotting boxplot to Detect outlier in the dataset.
• Draw correlation matrix to chect correlated value and to visualise some of column and thus remove 'is_timer' 
• Descriptive Analysis of Dataset


Feature Engineering:
• As there are some outliers that affecting our model so we remove outlier greater than upper_values.
  and remove is_timer because it has only single value.
  
  
Model Selection :
• check Model with different method of regression machine learning.  
• Performed Model Selection according to the Model which perform best Prediction
Score.
• Thus we will select best model as random forest regressor for our model with score 0.60594
