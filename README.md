# Customer-Churn-Prediction
Machine Learning project to predict customer churn using Logistic Regression, Random Forest, and XGBoost with EDA and performance evaluation.
## Project Overview
Customer churn refers to customers discontinuing a company's service. This project aims to predict customer churn using machine learning models and identify the key factors influencing customer retention.
## Dataset
Telco Customer Churn Dataset
The dataset contains customer demographic information, account details, services subscribed, and churn status.
## Objectives
- Analyze customer behavior and churn patterns.
- Perform Exploratory Data Analysis (EDA).
- Build classification models to predict churn.
- Compare model performance using evaluation metrics.
## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- VS Code
## Exploratory Data Analysis (EDA)

The following analyses were performed:
- Churn Distribution
- Gender vs Churn
- Contract Type vs Churn
- Internet Service vs Churn
- Monthly Charges vs Churn
- Tenure vs Churn
- Correlation Heatmap

## Data Preprocessing

- Removed unnecessary columns
- Handled missing values
- Encoded categorical variables
- Feature scaling
- Train-Test Split

## Machine Learning Models

### 1. Logistic Regression

Accuracy: 81.55%

### 2. Random Forest

Accuracy: 79.77%

### 3. XGBoost

Accuracy: 79.21%

## Model Comparison

| Model | Accuracy | Recall | ROC-AUC |
|---------|----------|---------|---------|
| Logistic Regression | 0.815 | 0.579 | 0.740 |
| Random Forest | 0.798 | 0.477 | 0.695 |
| XGBoost | 0.792 | 0.517 | 0.704 |

## Key Findings

- Customers with month-to-month contracts are more likely to churn.
- Customers with higher monthly charges show higher churn rates.
- Longer-tenure customers are less likely to leave.
- Contract type and tenure are strong predictors of churn.

## Business Impact

This model helps businesses identify customers at risk of leaving and enables proactive retention strategies, reducing revenue loss and improving customer satisfaction.

## Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- openpyxl
- jupyter
