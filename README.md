# Loan Approval Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict whether a loan application will be approved or rejected based on applicant financial and personal information. Machine Learning techniques are used to analyze patterns in the dataset and build a predictive model.

## 🎯 Objective

The objective of this project is to build a classification model that can predict the **loan approval status** using features such as income, credit score, loan amount, and asset values.

## 📊 Dataset Features

* **loan_id** – Unique ID for each loan application
* **no_of_dependents** – Number of dependents of the applicant
* **education** – Education level (Graduate / Not Graduate)
* **self_employed** – Whether the applicant is self-employed
* **income_annum** – Annual income of the applicant
* **loan_amount** – Loan amount requested
* **loan_term** – Duration of the loan
* **cibil_score** – Credit score of the applicant
* **residential_assets_value** – Value of residential assets
* **commercial_assets_value** – Value of commercial assets
* **luxury_assets_value** – Value of luxury assets
* **bank_asset_value** – Value of bank assets
* **loan_status** – Target variable (Approved / Rejected)

## 🔍 Exploratory Data Analysis (EDA)

* Analyzed the dataset to understand the distribution of features.
* Checked for missing values and cleaned the dataset.
* Used data visualization techniques to identify relationships between features.
* Observed how factors like income, loan amount, and credit score influence loan approval.

## ⚙️ Machine Learning Approach

Steps followed in the project:

1. Data Cleaning and Preprocessing
2. Encoding categorical variables
3. Splitting dataset into training and testing sets
4. Training machine learning classification models
5. Evaluating model performance using accuracy metrics

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

- loan_approval_prediction.ipynb – Jupyter Notebook containing the code
- loan_approval_dataset.csv – Dataset used for training and testing
- loan_approval_prediction.pkl – Saved trained machine learning model
- README.md – Project documentation

## 📈 Outcome

The model analyzes applicant information and predicts whether the loan should be approved or rejected. This type of predictive system can help financial institutions make better lending decisions.

## 👩‍💻 Author

Sangjukta Bhattacharjee
