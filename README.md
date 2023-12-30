# Project Overview: Machine Learning for Interview Status Prediction
## Introduction
This project focuses on predicting the status of job interviews using machine learning techniques. The goal is to create models that effectively determine whether a candidate would be considered, might be considered, or wouldn't be considered post an interview.

### Data Preprocessing
Data Cleaning: Removed missing values, filled nulls using mode/mean, and dropped redundant columns.
Exploratory Data Analysis (EDA): Explored data distribution, identified outliers, and checked correlations between features.
### Feature Engineering
Label Encoding: Converted categorical variables into numerical representations for model compatibility.
Feature Selection: Selected relevant features for training the models based on their impact on interview status prediction.
### Model Building and Evaluation
Decision Tree, Random Forest, AdaBoost, Gradient Boosting: Implemented and evaluated various ensemble models for prediction accuracy.
Model Comparison: Evaluated models based on confusion matrices, classification reports, and accuracy scores to identify the best-performing model.
### Model Deployment
Model Selection: Chose the best-performing model (AdaBoost) for final predictions.
Prediction on Test Data: Utilized the selected model to predict interview statuses on unseen test data.
Submission Creation: Generated a CSV file containing the interview IDs and predicted status for submission.
### Conclusion
Results: AdaBoost performed the best among the tested models for interview status prediction.
GitHub Repository: The complete code, data, and model files are available in this repository for reference and replication.
### Next Steps
Improvement Strategies: Consider further feature engineering, hyperparameter tuning, or ensemble methods to enhance model performance.
Feedback and Collaboration: Welcome contributions, feedback, and collaboration to improve the predictive model and its applications.
