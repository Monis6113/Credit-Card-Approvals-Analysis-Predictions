# Credit-Card-Loan-Approvals-Analysis-Predictions

# Objective:

As part of a practical machine learning application, I assumed the role of a data analyst working for a bank’s loan processing division. The goal was to analyze applicant profiles and develop predictive models that help assess whether a candidate should be granted a loan — streamlining manual evaluations and reducing risk.

# Dataset Overview

The dataset includes diverse applicant and loan information across these key categories:

**Demographics:** Gender, Marital Status, Dependents, Education, Self-Employed

**Financials:** Applicant Income, Coapplicant Income, Loan Amount, Loan Amount Term, Credit History

**Property:** Property Area (Urban/Rural/Semi-Urban)

**Target:** Loan Status (Approved/Not Approved)

# Approach

**1. Data Exploration & Cleaning**

Loaded data and reviewed types, shapes, and null values.

Dropped irrelevant columns like Loan_ID to avoid noise.

Visualized categorical features (e.g., Gender, Married, Education) using bar plots to spot dominant categories.

**2. Encoding & Preprocessing**

Applied Label Encoding to transform binary and categorical text features into numeric values for modeling.

Checked correlations with a heatmap to identify influential variables — Credit_History emerged as a strong predictor.

Filled missing values with mean imputation to maintain data integrity.

**3. Exploratory Analysis**

Visualized relationships with catplot to understand how factors like Gender and Marital Status impact Loan Approval.

Identified key patterns: applicants with a positive credit history and higher income generally had better approval odds.

**4. Splitting the Dataset**

Divided the dataset into training (60%) and test (40%) sets to evaluate model generalizability.

5. Model Development & Evaluation

Tested multiple classification models:

Random Forest Classifier

K-Nearest Neighbors

Support Vector Classifier

Logistic Regression

Evaluated model accuracy on both training and test sets to detect overfitting and select the best-performing model.

Random Forest achieved the highest test accuracy (~82%) indicating robust predictive capability.

# Key Insights

Credit History and Applicant Income were strong indicators of loan approval likelihood.

Married applicants and those with a steady coapplicant income showed higher approval rates.

Random Forest outperformed other classifiers, suggesting ensemble methods are well-suited for this type of binary classification task.

# Tools & Libraries Used

Python: Core scripting

**pandas, numpy:** Data wrangling and manipulation

**matplotlib, seaborn:** Visualization (bar plots, heatmaps, catplots)

**scikit-learn:** Label Encoding, Model Training, and Evaluation

# Outcome

This project strengthened my skills in data cleaning, exploratory analysis, and classification modeling, demonstrating how to turn raw application data into actionable lending insights. It reflects my ability to identify impactful variables, test multiple models, and deliver practical recommendations — skills directly relevant for data analyst and product analyst roles where data-driven decision-making is essential.
