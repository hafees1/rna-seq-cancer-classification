# 🧬 RNA-Seq Cancer Classification using Machine Learning

![Project Image](images/readme.png)

## 📌 Overview

This project builds an end-to-end machine learning pipeline to classify different cancer types using RNA sequencing (RNA-Seq) gene expression data.

The project demonstrates a complete supervised machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature scaling, model training, evaluation, and comparison of multiple classification algorithms.

---

## 📂 Dataset

**Source:** Kaggle - Gene Expression Cancer RNA-Seq Dataset  

https://www.kaggle.com/datasets/waalbannyantudre/gene-expression-cancer-rna-seq-donated-on-682016/data

**Original Source:** UCI Machine Learning Repository – Gene Expression Cancer RNA-Seq Dataset

https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq

The dataset is a part of the RNA-Seq (HiSeq) PANCAN dataset and contains gene expression profiles from cancer samples.

Each sample contains expression levels of 20,531 genes along with the corresponding cancer type label. The dataset includes samples from five different cancer types:

- BRCA → Breast Cancer
- KIRC → Kidney Renal Clear Cell Carcinoma
- COAD → Colon Adenocarcinoma
- LUAD → Lung Adenocarcinoma
- PRAD → Prostate Adenocarcinoma

The dataset is a high-dimensional classification dataset where machine learning models are used to identify patterns in gene expression data and classify samples into their respective cancer types.

### Target Variable

- **Class** → Cancer Type

---

## 🎯 Objective

The objective of this project is to build machine learning models capable of accurately classifying cancer types based on gene expression patterns and compare the performance of different classification algorithms.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 📊 Project Workflow

The project follows an end-to-end machine learning workflow:

- Data Loading
- Data Inspection
- Data Cleaning and Merging
- Exploratory Data Analysis (EDA)
- Label Encoding
- Train-Test Split
- Feature Scaling using StandardScaler
- Model Training
- Model Evaluation
- Cross Validation
- Model Comparison

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

- Loaded gene expression and label datasets
- Renamed columns for improved readability
- Merged datasets into a single DataFrame
- Checked and handled missing values
- Encoded cancer type labels using `LabelEncoder`
- Split data into training and testing sets
- Standardized features using `StandardScaler`
- Prevented data leakage by fitting the scaler only on training data

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- 5-Fold Cross Validation

The performance of all models was compared to identify the most effective classifier for cancer type prediction.

---

## ✅ Results

- Built a complete machine learning classification pipeline for RNA-Seq data.
- Applied preprocessing techniques for high-dimensional biological data.
- Trained and compared four different machine learning classifiers.
- Evaluated model performance using accuracy and cross-validation.
- Demonstrated the use of machine learning techniques for cancer classification.

---

## 🚀 Future Improvements to be done

- Perform hyperparameter tuning using `GridSearchCV` or `RandomizedSearchCV`.
- Build reusable preprocessing pipelines using Scikit-learn `Pipeline`.
- Apply feature selection techniques to reduce dimensionality.
- Analyze feature importance to identify important genes.
- Experiment with deep learning models for cancer classification.

---

