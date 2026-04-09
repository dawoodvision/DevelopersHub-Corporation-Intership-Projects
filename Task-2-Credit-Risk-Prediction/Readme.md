# Credit Risk Prediction

A simple machine learning project that predicts whether a **loan application will be approved or rejected**.  
The project uses the **Loan Prediction dataset** and demonstrates a complete data science workflow including data cleaning, exploratory data analysis, model training, and evaluation.

---

## Project Objective

The objective of this project is to analyze applicant information and build a model that can predict **loan approval status**.  

Through this project, we practice key data science skills such as:

• Data cleaning and preprocessing  
• Exploratory Data Analysis (EDA)  
• Data visualization  
• Binary classification using machine learning  
• Model evaluation using accuracy and confusion matrix

---

## Dataset

The dataset used in this project is the **Loan Prediction Dataset** from Kaggle.

It contains several features related to loan applicants, including:

| Feature | Description |
|---|---|
| ApplicantIncome | Income of the applicant |
| CoapplicantIncome | Income of the co-applicant |
| LoanAmount | Requested loan amount |
| Loan_Amount_Term | Loan repayment period |
| Credit_History | Credit history of the applicant |
| Education | Applicant education level |
| Property_Area | Location of the property |
| Loan_Status | Loan approval status (Target Variable) |

The target variable **Loan_Status** indicates whether the loan was **approved (Y)** or **rejected (N)**.

---

## Project Workflow

### 1. Data Cleaning and Preparation

The dataset was first prepared for analysis:

• Missing values were handled  
• Unnecessary columns such as **Loan_ID** were removed  
• Dependents value **3+** was converted to numeric form  
• Loan status was encoded into binary values (1 = Approved, 0 = Rejected)  
• Categorical variables were converted using **one hot encoding**

This step ensured the dataset was ready for machine learning.

---

### 2. Exploratory Data Analysis

Several visualizations were created to understand patterns in the dataset.

Visualizations included:

• Applicant income distribution  
• Loan amount distribution  
• Education vs loan approval  
• Loan amount vs loan approval

These graphs helped reveal relationships between applicant characteristics and loan approval.

---

### 3. Model Training

A **Logistic Regression model** was trained to predict loan approval.

The dataset was divided into:

• Training data for learning patterns  
• Testing data for evaluating the model

This allowed us to measure how well the model performs on unseen data.

---

## Model Performance

**Model Accuracy:** `0.87` (87%)

### Confusion Matrix

| Actual \ Predicted | Rejected | Approved |
|---|---|---|
| Rejected | 7 | 7 |
| Approved | 1 | 47 |

The results show that the model correctly predicts most loan approvals and rejections.

---

## Key Insights

• Applicant income and loan amount vary significantly across applicants  
• Education level shows some influence on loan approval  
• Logistic Regression works well for this binary classification problem  
• The model achieved strong prediction accuracy with simple preprocessing

---

## Tools and Technologies

• Python  
• Pandas  
• Matplotlib  
• Seaborn  
• Scikit-learn  
• Jupyter Notebook

---

## Final Thoughts

This project demonstrates how **data analysis and machine learning** can be used to solve a real world financial problem.

By cleaning the data, exploring patterns, and building a classification model, we created a system that can help predict **loan approval decisions** with good accuracy.