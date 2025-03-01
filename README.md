# 📚 Student Learning Styles Classification using Machine Learning

## 🎯 Project Overview
### This project applies Machine Learning techniques to classify students' learning styles (Visual, Auditory, Kinesthetic) based on responses to a VAK questionnaire. The aim is to develop a predictive model using the CatBoost algorithm to improve personalized learning experiences in education.
### By analyzing a dataset of 1,210 students, this study identifies patterns in learning preferences to assist educators in tailoring teaching strategies.

## 🚀 Features
- ✅ **Classification of student learning styles** (Visual, Auditory, Kinesthetic) using **CatBoost**
- ✅ **Preprocessing of dataset**, handling missing values, feature encoding, and selection
- ✅ **Machine Learning model training** and hyperparameter tuning
- ✅ **Comparison of classification models** (CatBoost, Decision Tree, KNN)
- ✅ **Performance evaluation using metrics** like Accuracy, Precision, Recall, and F1-score

## 📁 Project Structure

📁 **StudentsLearningStyles**  
│── 📁 **notebooks** │── 📄 Learning_Styles_classification.ipynb  
│── 📁 **data** │── 📄 contentSL_csv.csv  
│── 📄 README.md  




## 📥 Installation Guide

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/SalmaAlmutairi/StudentsLearningStyles.git
cd StudentsLearningStyles
pip install -r requirements.txt
```  

### 2️⃣ Download the Dataset
- Place the dataset (`SL_csv.csv`) in the `data/` directory.

### 3️⃣ Run the Jupyter Notebook 

- **Jupyter Notebook:**
  ```bash
  jupyter notebook

  Then open `Learning_Styles_classification.ipynb`.


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


## 📌 Future Improvements

- Implement **Deep Learning** for better predictions.
- Expand dataset for better generalization.
- Deploy model as an **API** for educational platforms.
















