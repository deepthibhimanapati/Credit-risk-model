**Credit Scoring Model**
**Project Overview**
This project focuses on developing a credit scoring model using historical customer data. The goal of the project is to predict the likelihood of a customer defaulting on a loan, allowing for more informed lending decisions by financial institutions. We applied data preprocessing techniques to handle missing values and built a logistic regression model to predict loan defaults. The project includes a comprehensive analysis of the dataset and the application of machine learning techniques to derive meaningful insights.

**Dataset Description**

The dataset used in this project contains customer credit information, which includes various financial attributes. Key features include:

TARGET: The binary target variable where 1 represents a customer defaulting on the loan and 0 represents no default.
DerogCnt: Count of derogatory records on file.
CollectCnt: Number of collection records.
BanruptcyInd: Indicator for whether the customer has filed for bankruptcy.
InqCnt06: Number of credit inquiries in the last 6 months.
TLDel3060Cnt24: Count of 30-60 days delinquent payments over the last 24 months.
TLDel90Cnt24: Count of 90+ days delinquent payments in the last 24 months.
The dataset consists of several additional features related to customer credit behavior and history, which are crucial for predicting creditworthiness.

**Methods Applied**

1. Data Preprocessing
Handling Missing Data: Missing values in the dataset were handled by filling them with the mean of the respective columns to ensure the integrity of the dataset.
Feature Selection: The customer ID column was dropped as it does not contribute to the predictive capabilities of the model.
2. Model Building
The primary model used in this project is Logistic Regression, a classification algorithm well-suited for binary classification tasks such as predicting loan defaults. This model was chosen for its simplicity and effectiveness in scenarios where the target variable is binary.

3. Model Evaluation
To assess the performance of the logistic regression model, the following evaluation metrics were used:

Accuracy Score: The percentage of correctly predicted instances.
Confusion Matrix: A matrix that highlights true positives, true negatives, false positives, and false negatives.
Classification Report: A detailed breakdown of precision, recall, and F1-score to provide insights into the model's performance.
Findings

Model Performance: The logistic regression model provided a good baseline for predicting loan defaults. Accuracy and other metrics from the confusion matrix and classification report indicated that the model performs adequately in distinguishing between defaulters and non-defaulters.
Data Insights: Features such as the number of derogatory records and credit inquiries in the last six months played a significant role in predicting the likelihood of default.

**Conclusion**

The project successfully demonstrates how logistic regression can be used to predict customer loan defaults based on historical data. By preprocessing the data and applying logistic regression, the model provides financial institutions with a predictive tool to assess the risk of lending.
