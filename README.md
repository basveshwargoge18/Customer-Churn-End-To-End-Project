#  Customer Churn Analysis & Machine Learning

> An End-to-End Data Science Project that performs Exploratory Data Analysis (EDA), Data Preprocessing, Feature Engineering, Machine Learning Model Building, Model Evaluation, and Business Recommendations to predict customer churn.

---

#  Table of Contents

- Introduction
- Problem Statement
- Project Objectives
- Dataset Information
- Technologies Used
- Project Workflow
- Exploratory Data Analysis
- Data Preprocessing
- Feature Engineering
- Machine Learning Models
- Model Evaluation
- Business Insights
- Business Recommendations
- Folder Structure
- Installation
- How to Run the Project
- Results
- Future Improvements
- Author

---

#  Introduction

Customer churn is one of the most important business problems in industries such as telecommunications, banking, insurance, SaaS, and subscription-based services.

Acquiring a new customer is significantly more expensive than retaining an existing one. Therefore, predicting which customers are likely to leave helps organizations take proactive retention measures.

This project demonstrates a complete Machine Learning workflow starting from understanding the data to building predictive models capable of identifying customers who are likely to churn.

---

#  Problem Statement

The objective of this project is to analyze customer behavior and identify the key factors responsible for customer churn.

Using historical customer information, we aim to build machine learning models that can accurately predict whether a customer will churn.

---

#  Project Objectives

- Understand customer demographics and service usage.
- Explore customer behavior using EDA.
- Clean and preprocess raw data.
- Handle missing values and incorrect data.
- Convert categorical variables into numerical format.
- Detect patterns influencing customer churn.
- Build multiple machine learning classification models.
- Compare model performances.
- Identify important features affecting churn.
- Generate actionable business recommendations.

---

#  Dataset Information

The dataset contains customer information including demographic details, account information, subscribed services, billing information, and customer churn status.

### Target Variable

```
Churn
```

- Yes → Customer Left
- No → Customer Stayed

---

#  Dataset Features

### Customer Information

- Customer ID
- Gender
- Senior Citizen
- Partner
- Dependents

### Account Information

- Tenure
- Contract Type
- Paperless Billing
- Payment Method

### Services

- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

### Billing Information

- Monthly Charges
- Total Charges

### Target

- Churn

---

#  Technologies Used

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Development Environment

- Jupyter Notebook

---

#  Project Workflow

```
Data Collection
        │
        ▼
Dataset Understanding
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Data Preprocessing
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Business Insights
        │
        ▼
Recommendations
```

---

#  Exploratory Data Analysis

The notebook performs comprehensive EDA including:

## Data Understanding

- Dataset Shape
- Dataset Information
- Statistical Summary
- Column Inspection
- Data Types

---

## Data Cleaning

- Missing Value Detection
- Duplicate Record Check
- Handling Incorrect Values
- Data Type Conversion

---

## Univariate Analysis

Performed analysis on:

- Gender
- Senior Citizen
- Partner
- Dependents
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Tenure

Visualizations include:

- Countplots
- Histograms
- Pie Charts
- Distribution Plots

---

## Bivariate Analysis

Relationship between:

- Gender vs Churn
- Contract vs Churn
- Internet Service vs Churn
- Tech Support vs Churn
- Online Security vs Churn
- Tenure vs Churn
- Monthly Charges vs Churn
- Total Charges vs Churn

Visualizations:

- Countplots
- Boxplots
- Bar Charts

---

## Correlation Analysis

- Correlation Matrix
- Heatmap
- Feature Relationship Analysis

---

#  Data Preprocessing

The following preprocessing techniques were applied:

- Missing Value Handling
- Duplicate Removal
- Data Type Conversion
- Label Encoding
- One-Hot Encoding (if required)
- Feature Selection
- Feature Scaling
- Train-Test Split

---

#  Machine Learning Models

The following classification algorithms were implemented:

## Logistic Regression

A simple baseline classification model used for binary prediction.

---

## Decision Tree Classifier

A tree-based algorithm capable of learning non-linear relationships.

---

## Random Forest Classifier

An ensemble learning algorithm that combines multiple decision trees for improved accuracy and robustness.

---

## XGBoost Classifier

A gradient boosting algorithm known for high performance and predictive accuracy on structured datasets.

---

#  Model Evaluation

Each model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

These metrics help compare the performance of different models and identify the most suitable one for churn prediction.

---

#  Key Business Insights

Some important findings from the analysis include:

- Customers with month-to-month contracts have the highest churn rate.
- Customers with higher monthly charges are more likely to churn.
- Customers with longer tenure are less likely to leave.
- Online Security significantly reduces churn.
- Customers using Tech Support services tend to remain loyal.
- Fiber Optic Internet users exhibit comparatively higher churn.
- Electronic Check payment users have a higher likelihood of churn.
- Customers with low total charges often churn early in their lifecycle.

---

#  Business Recommendations

Based on the analysis, the following strategies can help reduce customer churn:

- Encourage customers to adopt yearly or two-year contracts.
- Offer discounts to customers with high monthly charges.
- Improve customer support quality.
- Promote Online Security and Tech Support services.
- Launch loyalty programs for long-tenure customers.
- Provide personalized retention offers for high-risk customers.
- Monitor new customers during their first six months.
- Improve customer onboarding experience.

---

#  Project Structure

```
Customer-Churn-Analysis/
│
├── Customer_Churn_EDA_and_Machine_Learning.ipynb
├── churn.csv
├── README.md
│
└── images/
    ├── churn_distribution.png
    ├── correlation_heatmap.png
    ├── contract_vs_churn.png
    ├── tenure_distribution.png
```

---

#  Installation

Clone this repository

```bash
git clone https://github.com/yourusername/customer-churn-analysis.git
```

Move into the project directory

```bash
cd customer-churn-analysis
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Customer_Churn_EDA_and_Machine_Learning.ipynb
```

Run all notebook cells sequentially.

---

#  Visualizations Included

The project contains multiple visualizations including:

- Count Plots
- Histograms
- Boxplots
- Pie Charts
- Heatmap
- Distribution Plots
- Correlation Matrix
- Churn Comparison Charts
- Feature-wise Analysis

---

#  Expected Outcome

After completing this project, you will understand:

- Factors responsible for customer churn.
- Customer behavior patterns.
- Feature importance in churn prediction.
- How machine learning can assist customer retention strategies.
- End-to-end implementation of a classification project.

---

#  Future Improvements

Potential enhancements include:

- Hyperparameter Tuning using GridSearchCV.
- Cross Validation.
- Feature Importance Visualization.
- ROC-AUC Curve Analysis.
- Precision-Recall Curve.
- Model Deployment using Flask or FastAPI.
- Interactive Dashboard using Streamlit or Power BI.
- Real-time Customer Churn Prediction API.

---

#  Contributing

Contributions are welcome.

Feel free to fork this repository, create a new branch, and submit a pull request with improvements.

---

#  Author

## Basveshwar Goge

**Aspiring Data Scientist**

### Skills

- Python
- SQL
- Machine Learning
- Data Analysis
- Statistics
- Power BI
- Exploratory Data Analysis
- Data Visualization

---


#  License

This project is intended for educational and portfolio purposes.
