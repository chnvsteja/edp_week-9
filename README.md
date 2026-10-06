Final Scope
The scope of this project is to develop a machine learning-based Credit Card Fraud Detection System that can distinguish between fraudulent and genuine transactions using transaction-related data. The primary focus of the system is to address the class imbalance issue, in which fraudulent transactions occur much less frequently than legitimate transactions.
The project covers various stages of data preparation, including data cleaning, handling missing values, encoding categorical attributes, analyzing the distribution of transaction classes, and applying SMOTE (Synthetic Minority Over-sampling Technique) to increase the representation of fraudulent transactions. Two machine learning algorithms, Random Forest and XGBoost, are implemented and compared based on Accuracy, Precision, Recall, F1-Score, ROC-AUC, PR-AUC, and Confusion Matrix.
After evaluating both models, XGBoost is chosen as the final model because it provides better performance in detecting fraudulent transactions. Hyperparameter optimization is carried out to further enhance its performance, and the final trained model is stored for future deployment and prediction purposes.
Scope Includes
- Cleaning and preprocessing transaction-related data
- Examining and addressing the class imbalance problem
- Processing both categorical and numerical attributes
- Applying SMOTE for balancing the minority fraud class
- Training and comparing Random Forest and XGBoost algorithms
- Performing hyperparameter optimization for the XGBoost model
- Assessing model performance using Accuracy, Precision, Recall, F1-Score, ROC-AUC, PR-AUC, and Confusion Matrix
- Identifying and selecting the most effective fraud detection model
- Saving the trained model for future use and deployment
- Predicting transactions as Fraudulent or Legitimate
Final Output
The developed system produces a machine learning-based fraud detection model that examines transaction features and determines whether a transaction is fraudulent or legitimate. The system particularly emphasizes improving the identification of fraudulent transactions, which represent the minority class in the dataset.