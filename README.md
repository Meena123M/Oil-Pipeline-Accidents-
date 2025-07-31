# 🛢️ Oil Pipeline Accident Analysis

A comprehensive data analysis project on oil pipeline accidents, including preprocessing, exploratory data analysis (EDA), multicollinearity handling, outlier treatment, feature scaling, encoding, and building machine learning models for both classification and clustering tasks.

---

## 📂 Project Overview

This project aims to analyze and model oil pipeline accident data to understand patterns and potential predictors of incidents. The workflow includes:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Outlier detection and removal
- Handling multicollinearity
- Feature encoding and scaling
- Model building (classification and clustering)

---

## 🔧 Techniques Applied

### ✅ Data Preprocessing
- Dropped nulls and irrelevant features
- Handled missing and inconsistent values
- Converted categorical variables using `OneHotEncoder`
- Scaled numerical features using `StandardScaler`

### 📊 Exploratory Data Analysis (EDA)
- Univariate and bivariate visualizations using `matplotlib` and `seaborn`
- Correlation heatmaps
- Distribution plots for key features

### 🧮 Feature Engineering
- Removed features with high multicollinearity (correlation > 0.8)
- Applied encoding and scaling pipelines
- Outlier removal using IQR method

---

## 🤖 Models Built

| Model        | Type           | Purpose        |
|--------------|----------------|----------------|
| Linear Regression | Supervised | Regression analysis |
| Logistic Regression | Supervised | Binary classification |
| SVM          | Supervised     | Classification |
| K-Nearest Neighbors (KNN) | Supervised | Classification |
| KMeans Clustering | Unsupervised | Pattern discovery |

All models were built using `sklearn.pipeline.Pipeline` for clean and repeatable workflows.

---




