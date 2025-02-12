# Loan_Eligibility_Project

Main Objective:
To analyze key financial and demographic factors to develop a predictive model for home loan eligibility, enabling more accurate and fair loan approval decisions.

Secondary Objectives:
 1. To assess the impact of education level on loan eligibility by analyzing factors such as average applicant income, debt-to-income ratio (DTI), and loan amounts for graduates versus non-graduates.
 2. To evaluate the influence of credit history and self-employment status on loan approval rates by identifying patterns in approved loans based on credit history and examining the relationship between self-employment and loan status.

This project focuses on developing a machine learning model to predict home loan eligibility using applicant data. The dataset includes key financial and demographic features such as income, loan amount, credit history, and employment status, which influence loan approval decisions. The first step involves data acquisition and preparation, where the dataset is cleaned, missing values are handled, and categorical variables are encoded to ensure the data is in a suitable format for machine learning. Additionally, feature engineering techniques, such as calculating the debt-to-income (DTI) ratio and standardizing numerical values, help enhance the model’s predictive power.

The project utilizes logistic regression, a widely used classification algorithm, to determine loan approval outcomes. After splitting the data into training and testing sets, the model is trained using Scikit-learn and evaluated using accuracy, precision, recall, and F1-score metrics. Techniques such as hyperparameter tuning are applied to improve performance further. Additionally, alternative models like decision trees and random forests are considered to compare predictive accuracy and optimize results.

The file "eligibility.ipynb" is the notebook with all the code. The folder "data" contains the file with the dataset used to train and test the model(s). 

Class notes served as a primary resource in the development of this project. AI assistance was utilized for debugging and in instances where additional guidance was required.

Conclusion:
The models predicted home loan eligibility with 78-80% accuracy, doing well at approving eligible applicants but sometimes missing ineligible ones. The decision tree model performed best (79.67% accuracy). Further tuning and feature engineering can enhance fairness and reliability in loan approvals.
