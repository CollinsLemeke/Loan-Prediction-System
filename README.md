
Loan Status Prediction Model

Project Objective
The objective of this project is to build a predictive model that can accurately predict the loan status (Approved or Rejected) based on various features. The features include the number of dependents, education level, self-employment status, annual income, loan amount, loan term, CIBIL score, residential assets value, commercial assets value, luxury assets value, and bank asset value.

By accomplishing this task, the project aims to develop a robust and accurate loan status prediction model that can assist in making informed lending decisions.

Data
The dataset used for this project is tabulated and contains the following columns:

loan_id: Unique identifier for each loan application.

no_of_dependents: The number of dependents associated with the loan applicant.

education: Education level of the loan applicant (Graduate/Not Graduate).

self_employed: Indicates whether the loan applicant is self-employed (Yes/No).

income_annum: The annual income of the loan applicant.

loan_amount: The amount of loan applied for by the borrower.

loan_term: The term or duration of the loan in months.

cibil_score: The CIBIL score of the loan applicant, representing their creditworthiness.

residential_assets_value: Value of the residential assets owned by the loan applicant.

commercial_assets_value: Value of the commercial assets owned by the loan applicant.

luxury_assets_value: Value of luxury assets owned by the loan applicant.

bank_asset_value: Value of the assets held in the bank by the loan applicant.

loan_status: The target variable to be predicted (Approved/Rejected).


Project Steps

Data Exploration and Preprocessing: Explore the dataset to gain insights into the distribution of features and check for any missing values. Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features if necessary.

Data Visualization: Visualize the data to understand the relationships between different features and their impact on the loan status.

Feature Selection: Identify the most relevant features that have a significant impact on the loan status prediction. Use techniques like feature importance or correlation analysis.

Model Selection: Choose appropriate machine learning algorithms for binary classification, such as Logistic Regression, Decision Trees, Random Forest, Support Vector Machines, or Gradient Boosting.

Model Training: Split the dataset into training and testing sets. Train the selected model(s) on the training data.

Model Evaluation: Evaluate the model(s) using appropriate metrics like accuracy, precision, recall, F1-score, and ROC-AUC to assess its performance.

Author: Collins Lemeke 
