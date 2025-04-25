# Fraud-Invoice-Prediction

## Description
This project combines unsupervised learning techniques for detecting fraudulent transactions and supervised regression methods for predicting invoice payment amounts and timings. Designed for financial analytics and business intelligence applications, the project leverages clustering and dimensionality reduction for anomaly detection in transaction behavior, and linear regression with a Mean Squared Error(MSE) score of *0.064* for forecasting invoice payment based on historical patterns. The dual-model approach delivers valuable insights into risk assessment and financial planning.

## Features
+ **Fraud Transaction Analysis**
+ **Technique:** Uses unsupervised learning methods such as K-Means Clustering, DBSCAN, and PCA to identify anomalies in transaction data without labeled fraud indicators.
+ **EDA:** Visualizes key patterns in transaction behavior including amount, time, and account activity.
+ **Detection:** Flags potentially fraudulent transactions based on cluster distance and isolation.
+ **Interpretability:** Dimensionality reduction techniques like PCA are applied for better visualization and interpretability.

+ **Invoice Payment Prediction**
+ **Technique:** Employs Linear Regression to predict the payment status or timing of invoices based on factors like:
 Invoice amount, 
 Customer payment history, 
 Due date vs. issue date, 
 Customer industry and credit score
+ **Performance:** Achieves a Mean Squared Error (MSE) of 0.064, ensuring accurate payment forecasting.
+ **Business Use Case:** Helps in cash flow forecasting, credit risk management, and customer segmentation.

## Visualizations
+ Clustering visualizations for fraud detection using PCA-reduced dimensions
+ Regression scatter plots and residuals for invoice predictions
