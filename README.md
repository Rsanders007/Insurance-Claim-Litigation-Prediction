# 🚀 Insurance Claim Litigation Prediction
Predicting whether an insurance claim will be litigated using machine learning.

## 📌 Overview
This project applies a **Random Forest model** and **Lasso regression** for feature selection to classify insurance claims as **litigated or not** based on claim characteristics.

## 📊 Dataset
- **Source**: Synthetic insurance claims dataset.
- **Features**: Claim amount, injury claim, fraud indicator, policy deductible, etc.
- **Target**: `Litigated` (Yes/No)

## 🛠️ Methodology
- **Data Preprocessing**: Handled missing values, label encoding.
- **Feature Selection**: Used Lasso regression to determine key drivers.
- **Model Training**: Trained a **Random Forest classifier** to predict litigation.
- **Evaluation**: ROC curve analysis for optimal threshold selection.

## 📈 Findings
- **Key Predictors**: Claim amount, injury claim, fraud reports.
- **Litigation Rate**: Model accurately classifies litigation likelihood.
- **Feature Importance**: Visualized using Lasso regression.

## 🔧 Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/Insurance-Claim-Litigation-Prediction.git
cd Insurance-Claim-Litigation-Prediction
pip install -r requirements.txt
