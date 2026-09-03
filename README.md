# End-to-End Data Science Project — Advertising Spend & Sales Prediction

A  business-focused data-science project using advertising spend data from Kaggle. The objective is to understand how TV, radio, and newspaper advertising relate to sales and to build a model that predicts sales from campaign inputs.

## 🎯 Business Problem

A marketing team wants to understand whether advertising investment is associated with higher sales and whether historical campaign spend can support a simple sales-prediction model.

The project demonstrates the full workflow from raw data to a model-backed recommendation.

## 📊 Dataset

**Source:** Kaggle — [Advertising dataset](https://www.kaggle.com/datasets/tawfikelmetwally/advertising-dataset/data)

Kaggle describes this as a 200-row dataset with three advertising channels — TV, Radio, and Newspaper — and a Sales target. The dataset is tagged for business and beginner linear-regression use.

The repository includes `advertising.csv` for immediate local execution.

## 🔄 End-to-End Workflow

```text
Problem Definition
      ↓
Data Loading & Validation
      ↓
Exploratory Data Analysis
      ↓
Feature / Target Preparation
      ↓
Train / Test Split
      ↓
Baseline Model
      ↓
Linear Regression
      ↓
Random Forest + Gradient Boosting
      ↓
Cross-Validation & Model Comparison
      ↓
Residual / Error Analysis
      ↓
Feature Importance
      ↓
Scenario Prediction Function
      ↓
Business Recommendations
```

## 🧠 Concepts Demonstrated

- Data quality checks
- Descriptive statistics
- Correlation analysis
- Train/test evaluation
- Regression modelling
- Baseline comparison
- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression
- Cross-validation
- MAE, RMSE, R²
- Residual analysis
- Feature importance
- Scenario analysis
- Reproducibility

## 📁 Repository Structure

```text
End_to_End_Data_Science_Project/
├── README.md
├── end_to_end_sales_prediction.ipynb
├── advertising.csv
├── requirements.txt
└── .gitignore
```

## ▶️ Run Locally

```bash
pip install -r requirements.txt
jupyter notebook end_to_end_sales_prediction.ipynb
```

