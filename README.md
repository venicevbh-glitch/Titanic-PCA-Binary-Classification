# Titanic-PCA-Binary-Classification
Titanic-PCA-Binary-Classification
# Titanic Binary Classification with PCA & Model Deployment

## 📌 Project Overview
This project implements a complete binary classification pipeline using the Titanic dataset.  
The goal is to predict whether a passenger survived or not using machine learning techniques and deploy the model using Streamlit.

The project includes:
- Data loading, cleaning, and preprocessing
- Feature scaling and PCA for dimensionality reduction
- Training multiple classification models
- Model evaluation and selection
- Streamlit app for deployment

---

## 📊 Dataset
The Titanic dataset contains passenger information:

- Features: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`
- Target: `Survived` (0 = Not Survived, 1 = Survived)

**Dataset Source:**  
[Titanic Dataset by DataScienceDojo](https://github.com/datasciencedojo/datasets/blob/master/titanic.csv)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Missing values handled using median (Age) and mode (Embarked)
- Categorical variables encoded using One-Hot Encoding
- Numerical features standardized using StandardScaler

### 2. PCA (Principal Component Analysis)
- PCA applied to reduce dimensionality
- 95% variance retained for model training

### 3. Model Training
Models trained:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

### 4. Model Evaluation
- Accuracy score used for evaluation
- Confusion matrices generated
- **Best-performing model:** SVM (highest test accuracy ~82%)

### 5. Model Saving
The
