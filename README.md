<div align="center">

# 🛡️ SafeHer
### Machine Learning-Based Crime Prediction & Analysis for Women's Safety

<p>
An intelligent machine learning system that analyzes crime patterns, predicts case outcomes, and provides actionable insights to support data-driven decision-making for women's safety.
</p>

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-blue?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

🎥 **Demo Video:** *https://drive.google.com/file/d/1Jxn9eUgNpOMcVFgWnfPdUEjoqe3BTpRF/view?usp=sharing*

📄 **Project Documentation:** *https://docs.google.com/document/d/14-ja6zSChSsZrYHLRD4LNSLGS6FP7hmH/edit?usp=sharing&ouid=106753848410231431636&rtpof=true&sd=true*

📊 **Dataset:** *https://www.kaggle.com/datasets/sudhanvahg/indian-crimes-dataset*

</div>

---

# 📌 Problem Statement

Despite significant efforts toward women's safety, crime rates continue to rise across various regions. Large volumes of crime data remain underutilized due to their complexity, making it difficult to identify patterns and support informed decision-making.

SafeHer leverages Machine Learning and Data Analytics to uncover hidden trends in crime data, predict case outcomes, and provide meaningful insights that can assist researchers, policymakers, and law enforcement agencies.

---

# 🎯 Objectives

- Analyze historical crime data related to crimes against women.
- Identify hidden crime patterns using Exploratory Data Analysis.
- Predict case closure status using Machine Learning.
- Compare multiple ML algorithms for optimal performance.
- Provide meaningful visual insights for data-driven decision making.

---

# ✨ Key Features

✅ Data Cleaning & Preprocessing

✅ Feature Engineering

✅ Exploratory Data Analysis (EDA)

✅ Interactive Data Visualizations

✅ Classification using Multiple ML Models

✅ Model Performance Comparison

✅ Crime Trend Analysis

✅ Predictive Analytics for Case Closure

---

# 🏗️ Project Workflow

```
Crime Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Machine Learning Models
      │
      ▼
Model Evaluation
      │
      ▼
Predictions & Insights
```

---

# 🧠 Machine Learning Pipeline

SafeHer follows an end-to-end machine learning workflow that transforms raw crime records into actionable insights through **data preprocessing, exploratory analysis, predictive modeling, and pattern discovery**. The project combines **Classification, Regression, and Clustering** techniques to analyze crime trends from multiple perspectives.

---

## 🔹 Data Preprocessing & Exploratory Data Analysis

The dataset was prepared through:

- Data Cleaning & Missing Value Handling
- Duplicate Removal & Outlier Detection
- Label Encoding of Categorical Features
- Feature Scaling using StandardScaler
- Date & Time Feature Extraction
- Feature Engineering

Exploratory Data Analysis (EDA) was performed using **correlation heatmaps, histograms, box plots, count plots, pie charts, confusion matrices, and statistical summaries** to identify crime patterns, temporal trends, victim demographics, and feature relationships before model development.

---

## 🤖 Machine Learning Models

### 📌 Classification

To predict **case closure status**, three classification models were implemented and compared:

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

Models were evaluated using **Accuracy, Precision, Recall, F1-Score, and Confusion Matrices**. Performance was further improved through **Decision Tree Pruning, Grid Search, and Randomized Search**. Among all classifiers, **XGBoost delivered the most balanced overall performance**, while Decision Tree performance improved significantly after pruning.

---

### 📌 Regression

Regression analysis was performed for two prediction tasks:

- **Case Closure Duration Prediction**
  - Accuracy: **80.45%**
  - MAE: **33.52**
  - MSE: **3231.71**
  - R² Score: **80.44%**

- **City-wise Monthly Crime Frequency Prediction**
  - Accuracy: **94.71%**
  - MAE: **10.47**
  - MSE: **190.60**
  - R² Score: **94.71%**

The optimized Decision Tree Regressor demonstrated excellent generalization after pruning, making it highly effective for crime trend prediction.

---

### 📌 Clustering

K-Means Clustering was applied to discover hidden crime patterns using **City, Crime Domain, Month, Day of Week, and Hour of Occurrence**. The optimal number of clusters (**k = 4**) was determined using the **Elbow Method**.

**Key Insights**

- Crime patterns were primarily driven by **location and time of occurrence**.
- Delhi and Mumbai emerged as major crime hotspots with distinct temporal trends.
- Separate clusters captured **early-morning**, **afternoon**, and **seasonal crime behaviors**.
- Seasonal spikes around **June** indicated recurring crime patterns influenced by temporal factors.

---

## 📈 Model Evaluation

SafeHer adopts a comprehensive evaluation strategy using task-specific metrics:

- **Classification:** Accuracy, Precision, Recall, F1-Score & Confusion Matrix
- **Regression:** Accuracy, MAE, MSE & R² Score
- **Clustering:** Elbow Method, Cluster Analysis & Pattern Interpretation

Overall, the project demonstrates a complete machine learning pipeline by integrating **Classification, Regression, and Clustering** with optimization techniques to generate meaningful insights and support data-driven decision-making for women's safety.

---

# 📂 Dataset

SafeHer uses the **Indian Crime Dataset** sourced from Kaggle, containing historical records of crimes against women across different cities, crime categories, victim demographics, and case information. The dataset was preprocessed, engineered, and analyzed to support exploratory analysis, predictive modeling, and pattern discovery.

**Source:** Kaggle – Indian Crime Dataset

---

# 🛠️ Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

### Development Environment

- Google Colab

---


# 📷 Screenshots

<img width="1919" height="777" alt="image" src="https://github.com/user-attachments/assets/cc32655b-6567-4542-bf7f-ac1f1caf6924" />

<img width="1919" height="773" alt="image" src="https://github.com/user-attachments/assets/f659df9b-f82e-43d1-915d-aff41d7d9de7" />



# 📂 Repository Contents

This repository contains:

-  Google Colab Notebook
-  Dataset
-  Project Documentation
-  Demo Video
-  Project Screenshots
---

# 💡 Future Enhancements

- Real-time crime forecasting
- Interactive web dashboard
- GIS-based crime heatmaps
- Deep Learning models
- Deployment using Streamlit
- AI-powered safety recommendation system

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---
