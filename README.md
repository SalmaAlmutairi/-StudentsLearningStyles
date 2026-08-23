# 📚 Student Learning Styles Classification using Machine Learning

## 🎯 Project Overview
### This project applies Machine Learning techniques to classify students' learning styles (Visual, Auditory, Kinesthetic) based on responses to a VAK questionnaire. The aim is to develop a predictive model using the CatBoost algorithm to improve personalized learning experiences in education.
### By analyzing a dataset of 1,210 students, this study identifies patterns in learning preferences to assist educators in tailoring teaching strategies.

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Installation Guide](#-installation-guide)
- [Methodology](#-methodology)
- [Results](#-results)
- [Future Improvements](#-future-improvements)

## 🚀 Features
- ✅ **Classification of student learning styles** (Visual, Auditory, Kinesthetic) using **CatBoost**
- ✅ **Preprocessing of dataset**, handling missing values, feature encoding, and selection
- ✅ **Machine Learning model training** and hyperparameter tuning
- ✅ **Comparison of classification models** (CatBoost, Decision Tree, KNN)
- ✅ **Performance evaluation using metrics** like Accuracy, Precision, Recall, and F1-score

## ▶️ How to Run

This project was developed and tested using **Google Colab**.

### 1. Open the Notebook
Open the `Learning_Styles_classification.ipynb` file in Google Colab.

### 2. Upload the Dataset
Upload the dataset file:

`contentSL_csv.csv`

to the Colab session before running the notebook.

### 3. Run the Notebook
Run the notebook cells sequentially from top to bottom.


## 🧠 Methodology

1. **Data Preprocessing**: Handling missing values, encoding categorical features, feature selection.
2. **Exploratory Data Analysis (EDA)**: Statistical summaries and visualizations.
3. **Model Selection**: **CatBoostClassifier** (with comparisons to Decision Tree, KNN).
4. **Hyperparameter Tuning**: Optimizing the model for best performance.
5. **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

## 📌 Results

- **Baseline CatBoost Model**: **87.13% accuracy** on test data.
- **Optimized Model**: **90.10% accuracy** after tuning.
- **Comparison**:
  - **CatBoost**: Best overall performance.
  - **KNN**: Moderate accuracy but sensitive to scaling.
  - **Decision Tree**: Overfitting issues.
### 📊 ROC Curve for Model Comparison
Below is the **ROC Curve Comparison** for **multiclass classification** using different models:

![ROC Curve Comparison](https://github.com/user-attachments/assets/94935f57-64b3-4c76-9d47-a6bd071e8845)




## 📌 Future Improvements

- Implement **Deep Learning** for better predictions.
- Expand dataset for better generalization.
- Deploy model as an **API** for educational platforms.



















