📊 Customer Churn Prediction & Risk Analysis Engine
👤 Author

Shalet John Chinnaraja

📌 Project Overview

Customer churn is a critical challenge in the telecom industry, as losing customers directly impacts revenue and long-term growth.

This project develops a Machine Learning–based system to predict whether a customer is likely to leave the company. In addition to prediction, the system functions as a Risk Analysis Engine by assigning a churn probability score to each customer.

This helps businesses take preventive actions to retain high-risk customers.

🎯 Objectives

Predict customer churn using Machine Learning

Analyze churn risk using probability scores

Evaluate model performance using standard metrics

Provide actionable business insights for retention strategies

🗂 Dataset Used

Telco Customer Churn Dataset

The dataset includes:

Gender

Senior Citizen

Tenure

Monthly Charges

Total Charges

Contract Type

Payment Method

Internet Service

Churn (Target Variable)

Target Variable:

0 → Customer stays

1 → Customer churns

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Google Colab

🔄 Methodology / Workflow

Data Loading

Data Cleaning

Handling missing values

Converting categorical variables to numeric

Feature Scaling

Train-Test Split (70% training, 30% testing)

Model Training using Logistic Regression

Model Evaluation

Visualization (Confusion Matrix & ROC Curve)

🤖 Model Used
Logistic Regression

Logistic Regression is a supervised learning algorithm used for binary classification problems.

It predicts the probability of customer churn and classifies customers into churn or non-churn categories.

📊 Model Performance

Accuracy: ~81%

Precision (Churn Class): ~0.69

Recall (Churn Class): ~0.58

F1-Score: ~0.63

ROC-AUC Score: ~0.74

The model performs well overall and provides reliable churn predictions.

📈 Risk Analysis Engine

The system calculates churn probability using:

model.predict_proba()

This probability represents the customer’s risk level:

0.00 – 0.30 → Low Risk

0.30 – 0.70 → Medium Risk

0.70 – 1.00 → High Risk

This allows businesses to:

Identify high-risk customers

Offer retention strategies

Improve customer satisfaction

Reduce revenue loss

📉 Visualizations Included

Confusion Matrix

ROC Curve

These visual tools help in evaluating classification performance.

🚀 Conclusion

The Customer Churn Prediction & Risk Analysis Engine successfully predicts customer churn with approximately 81% accuracy and a ROC-AUC score of 0.74.

By leveraging predicted churn probabilities, companies can proactively reduce customer attrition and improve long-term profitability.

This project demonstrates the practical application of Machine Learning in solving real-world business problems.
