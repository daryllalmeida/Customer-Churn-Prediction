Problem Statement

- In today’s competitive banking industry, retaining customers is as critical as acquiring them. This project aims to build a predictive analytics model that can estimate the probability of customer churn based on demographic, financial, and behavioral variables.

Business Problem 

- Customer attrition directly impacts the bank’s profitability, brand loyalty, and long-term growth. By leveraging this customer data including credit scores, account balances, tenure, product usage, and activity levels the model will identify key drivers of churn. The insights will help the bank design targeted retention campaigns, improve customer experience, and optimize resource allocation for customer relationship management.

Conclusion:

- This project predicts customer churn for a bank using advanced machine learning models. After performing extensive EDA, feature engineering, and model experimentation (Logistic Regression, Random Forest, LightGBM, XGBoost), XGBoost delivered the strongest performance with a ROC-AUC of 0.866.

- To improve recall—the primary metric for churn—the model was optimized using threshold tuning, lowering the decision cutoff from 0.50 to 0.35. This increased churn recall from 62.7% → 73.2%, meaning the model successfully identifies nearly three-quarters of all customers likely to leave.

- The final model balances precision, recall, accuracy, and business impact while reducing false negatives significantly. Key churn drivers include inactive membership, number of products, zero account balance, and age groups. 
