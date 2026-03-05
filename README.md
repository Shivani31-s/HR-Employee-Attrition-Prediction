Project Overview

Employee attrition is a major challenge for organizations as it leads to increased recruitment costs, loss of experienced talent, and reduced productivity.

This project aims to analyze employee data and build a machine learning model to predict whether an employee is likely to leave the company. The goal is to help HR departments proactively identify at-risk employees and implement retention strategies.

🎯 Objective

Analyze key factors contributing to employee attrition

Build predictive models to classify employees as likely to leave or stay

Compare multiple machine learning models

Provide actionable business insights for HR decision-making

📂 Dataset

IBM HR Analytics Employee Attrition Dataset

Contains employee-level information such as:

Age

Department

Monthly Income

Job Role

Years at Company

Overtime

Promotion History

Attrition (Target Variable)

🛠️ Tools & Technologies Used

Python

Pandas

NumPy

Seaborn & Matplotlib

Scikit-learn

Power BI (for dashboard visualization)

🔎 Project Workflow

Data Preprocessing

Checked for missing values

Encoded categorical variables

Split dataset into training and testing sets

Exploratory Data Analysis (EDA)

Analyzed attrition distribution

Visualized salary vs attrition

Department-wise attrition analysis

Correlation heatmap

Model Building

Logistic Regression

Random Forest Classifier

Applied class balancing techniques

Model Evaluation

Accuracy Score

Confusion Matrix

Precision, Recall, F1-score comparison

Feature Importance Analysis

Identified key drivers of attrition

Interpreted results for business impact

📈 Key Insights

Overtime significantly increases attrition risk

Lower monthly income is associated with higher resignation probability

Employees with fewer years at the company are more likely to leave

Lack of promotion impacts retention

Distance from home influences attrition behavior

🏆 Model Performance

Logistic Regression Accuracy: ~86%

Random Forest Accuracy: ~88–90% (Improved detection of attrition cases)

Random Forest performed better in identifying employees at risk of leaving.

💡 Business Impact

The predictive model can help HR teams:

Identify high-risk employees early

Implement targeted retention strategies

Improve employee satisfaction

Reduce recruitment and training costs

