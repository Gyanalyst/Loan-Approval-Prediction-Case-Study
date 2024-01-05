# Loan-Status-Prediction-Case-Study

_In this Notebook , We are going to solve the Loan Approval Prediction.This is a Classification problem in which we need to classify whether the loan will be approved or not._

## Problem Statement :-
_Automate the loan eligibility process (real-time) based on customer detail provided while filling the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others._

**The major aim of this notebook is to predict which of the customers will have their loan approved.**

## Features of our data :-
LoanID = Unique Loan ID

Gender = Male/ Female

Married = Applicant married (Y/N)

Dependents = Number of dependents

Education = Applicant Education (Graduate/ Under Graduate)
SelfEmployed = Self-employed (Y/N)

ApplicantIncome = Applicant income

CoapplicantIncome = Coapplicant income

LoanAmount = Loan amount in thousands

LoanAmountTerm = Term of the loan in months

CreditHistory = Credit history

PropertyArea= Urban/ Semi-Urban/ Rural

LoanStatus = (Target) Loan approved (Y/N)

Certainly, based on the analysis conducted in the provided code:


# **Table of Contents:**

**• Introduction**

**• Business Problem**

**• Importing Modules**

**• Dataset Analysis**

**• Handling Missing Values - Categorical & Numerical**

**• Outliers Detection & Handling**

**• Analysis Categorical Data with Target**

**• Data Preparation**

**• Handling Imbalance Data**

**• Creating Multiple Model & Choose The Ideal One**

**• Model Building**

### Process Involved:

- **Data Handling:**

  - **Null Values:** The missing values in the dataset were dealt with using mode and median imputations based on the data type.

  - **Outliers:** Outliers in features like ApplicantIncome, CoapplicantIncome, and LoanAmount were detected and appropriately handled to ensure model robustness.

  - **Data Transformation:** Log transformation was applied to numeric features to normalize their distributions for better model performance.

- ### Categorical Analysis:

  - **Loan Approval Rates:** Married individuals tend to have higher loan approval rates compared to unmarried applicants.

  - **Education Impact:** Graduates have higher chances of loan approval compared to non-graduates.

  - **Property Area Influence:** Applicants from semi-urban areas have higher chances of loan approval compared to urban and rural areas.

  - **Self-Employment Factor:** Self-employed applicants seem to have slightly lower loan approval rates than non-self-employed individuals.

- **Model Development:**

  - **Imbalanced Data:** SMOTE technique was used to handle the imbalance in the target variable ('Loan_Status') by oversampling the minority class.

  - **Model Comparison:** Various classifiers like K-Nearest Neighbors, Support Vector Machine, Decision Tree, Naive Bayes, and Random Forest were compared. Logistic Regression emerged as the most effective model with good accuracy for this dataset.

### Recommendations:

- **Further Feature Engineering:** Explore additional features or create new features from existing ones that might enhance the predictive power of the model.

- **Exploration of Other Algorithms:** Though Logistic Regression performed well, testing more complex algorithms or ensemble methods could potentially yield better performance.

- **Feature Importance:** Conduct feature importance analysis to identify key features driving loan approvals, which might help in focusing on crucial factors during applicant evaluations.

- **Data Collection & Quality:** Ensure ongoing data quality checks and consider expanding the dataset to improve model robustness and generalizability.

- **Deployment and Monitoring:** Once the model is ready, deploy it in a production environment and continuously monitor its performance for any drift or degradation in accuracy.

- **Regulatory Compliance:** Ensure the model complies with legal and regulatory frameworks governing the financial domain, especially in loan approval scenarios.

_By implementing these recommendations, the loan approval prediction model can be enhanced for more accurate and reliable real-time predictions._


## Skills :-
**Programming Language:** *Python (Pandas, NumPy, Matplotlib, Seaborn)*

**Model:** *KNN Classifier, SVC, Decision Tree Classifier, Logistic Regression, GaussianNB, Random Forest Classifier*

**Best Model Selection:** *LogisticRegression*

_[ Logistic regression can be used for our model as its giving effective training testing accuracy ]_

# Contact Info :-

## Linkedln : https://www.linkedin.com/in/gyan-ashish/

## Email : gyanashish753@gmail.com
