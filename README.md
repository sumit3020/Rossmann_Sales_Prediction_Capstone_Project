# Rossmann_Sales_Prediction_Capstone_Project

Rossmann is a European drug distributor that operates over 3,000 drug stores across seven European countries. Since a lot of drugs come with a short shelf life, i.e., they do not have a long expiry date, it becomes imperative for Rossmann to accurately forecast sales at their individual stores. Currently, the forecasting is taken care of by the store managers, who are tasked with forecasting daily sales for the next six weeks.

As expected, store sales are influenced by many factors, including promotional campaigns, competition, state holidays, seasonality, and locality.

With thousands of individual managers predicting sales based on their unique circumstances and intuitions, the accuracy of the forecasts is quite varied. To overcome this problem, the company has hired you as a data scientist to work on the forecasting problem. As part of your job role, you are tasked with building a forecasting model to forecast the daily sales for the next six weeks. To help you with the same, you have been provided with historical sales data for 1,115 Rossmann stores.


💾Appraoch Pipeline

Data Preprocessing

Data Exploration

Model Prediction




💾 Project Files Description

This Project includes 1 colab notebook and 1 Pdf of presentation.

Executable Files:
Credit-Card-Default-Prediction - Includes Exploratory Data Analysis and all algorithms which are used in this project.


📋Algorithms

XG Boosting
Gradient Boosting
Support Vector Machine
Random Forest Classifier
Decision Tree Classifier
Logistic Regression



📋Conclusions

1. From all baseline models, the Random Forest classifier shows the highest test accuracy, F1 score, and AUC.

2. The baseline model of Random Forest and decision tree shows huge difference in train and test accuracy which shows overfitting.

3. After cross validation and hyperparameter tunning, XG Boost shows highest test accuracy score of 87% and AUC is 0.873.

4. Cross-validation and hyperparameter tunning certainly reduces chances of overfitting and also increases performance of model.
