# 🚢 Titanic Survival Prediction

## 📌 Overview

This project builds a complete machine learning pipeline to predict passenger survival on the Titanic using structured tabular data.

The workflow includes data preprocessing, feature engineering, model training, and evaluation using cross-validation.

---

## 🛠️ Workflow

### 1️⃣ Data Preprocessing

- Handled missing values:
  - Group-based imputation for **Age**
  - Mode imputation for **Embarked**
  - Median imputation for **Fare**

- Encoded categorical variables (**Sex, Embarked, Title**)

- Removed non-informative features:
  - PassengerId
  - Ticket

---

### 2️⃣ Feature Engineering

- Extracted **Title** from the Name column  
- Created a new feature: **FamilySize**  
- Processed **Cabin** information  

---

### 3️⃣ Model Evaluation

- Used **15-Fold Cross Validation**
- Compared multiple classification algorithms

---

## 🤖 Models & Results

| Model | Accuracy |
|--------|----------|
| KNN | 73.18% |
| Decision Tree | 76.21% |
| Naive Bayes | 80.04% |
| Random Forest | 80.81% |
| SVM | 67.67% |

---

## 🏆 Best Model

**Random Forest Classifier** achieved the highest cross-validated accuracy.

---

## 📚 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🎯 Key Learnings

- Building an end-to-end machine learning pipeline  
- Feature engineering for structured data  
- Cross-validation for robust evaluation  
- Model comparison and selection  
