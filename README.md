# E-exercise

The dataset contains observations collected for different devices through WiFi access point and physical locations. Each observation is characterized by device_id, time and location_id. To find the relationship between devices, each record contain some unknown features and information for a pair of device. 

This project uses three different machine learning model to train a classifier to predict whether any two devices are related. The models include: Logistic Regression, Random Forest and XGBoost. AUC score is selected as the metric for comparision and evaluation. For XGBoost, the parameters are optimized using grid search to improve the performance of auc.

It is an exercise of feature engineering and optimization. The performance can be further improved by feature selection and model optimization.
