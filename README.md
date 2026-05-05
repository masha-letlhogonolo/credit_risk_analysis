# Credit Risk Analysis:Predicting Loan Default 
# Overview 
This project predicts whether a customer is likely to default on their loan based on demographic and financial data, using machine learning.

# Key Steps:
-Data cleaning and preprocessing. 
-Handling categorical data using one-hot encoding. 
-Developing a Logistic Regression model. 
-Model evaluation using confusion matrix and classification metrics. 

# Tools used:
-Python (pandas, matplotlib) 
-Scikit-learn

# Key results:
-Accuracy:74‰
-Recall(default):85%
-Recall(non default):50%

# Key insight:
The model is effective at identifying customers who will default(high-risk customers), which is important in financial risk management. However,it tends to wrongly classify some low-risk customers indicating a trade-off between risk detection and customer approval. 

# Business recommendation:
This model can be used by financial institutions to improve credit risk assessment, by prioritizing the identification of high-risk customers, while further improvement can help reduce false positives. 
