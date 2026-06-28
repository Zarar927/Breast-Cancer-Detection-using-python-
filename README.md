# 🧬 Breast Cancer Survival Prediction Using Machine Learning

## 📌 Overview
This project applies Machine Learning techniques to predict the survival outcome of breast cancer patients based on clinical and demographic features.

The dataset contains **4024 patient records** with features like tumor size, cancer stage, lymph node involvement, and patient survival status.

The goal is to compare multiple ML algorithms and identify the best-performing model for classification.

---

## 🎯 Problem Statement
Breast cancer is one of the most critical diseases worldwide. Early prediction of patient survival can help in better diagnosis and treatment planning.

This project aims to:
- Analyze breast cancer dataset
- Perform Exploratory Data Analysis (EDA)
- Train multiple machine learning models
- Compare model performance
- Predict patient survival status (Alive / Dead)

---

## 📊 Dataset Description

### Features:
- Age
- Race
- Marital Status
- T Stage
- N Stage
- 6th Stage
- Tumor Differentiation
- Grade
- A Stage
- Tumor Size
- Estrogen Status
- Progesterone Status
- Regional Node Examined
- Regional Node Positive
- Survival Months
- Status (Target Variable)

---

## 📈 Exploratory Data Analysis (EDA)

Performed visual analysis to understand data distribution:

- Race distribution
- Tumor differentiation distribution
- Feature relationships

📊 Insights:
- Data contains both numerical and categorical variables
- Some imbalance in class distribution
- Medical features strongly influence survival outcome

---

## ⚙️ Data Preprocessing
- Loaded dataset using Pandas
- Checked dataset structure and summary
- Selected features and target variable
- Split dataset into training and testing sets (80/20)
- Used raw features for baseline models

---

## 🤖 Machine Learning Models

The following classification models were implemented:

### 🌳 Decision Tree Classifier
- Simple and interpretable model
- Captures non-linear relationships

### 🧮 Gaussian Naive Bayes
- Probabilistic model based on Bayes theorem
- Fast baseline classifier

### ⚡ Support Vector Machine (SVM)
- High-performance classifier
- Works well for complex decision boundaries

### 📍 K-Nearest Neighbors (KNN)
- Instance-based learning model
- Classifies based on nearest neighbors

---

## 📊 Model Performance Comparison

| Model              | Training Accuracy | Testing Accuracy |
|-------------------|------------------|-----------------|
| Naive Bayes       | 0.81             | 0.84            |
| SVM               | 0.88             | 0.89            |
| KNN               | 0.91             | 0.89            |

---

## 🏆 Best Model
✔ **Support Vector Machine (SVM)** achieved the best balance between training and testing performance, making it the most reliable model for this dataset.

---

## 🧠 Key Insights
- Tumor size and cancer stage are major predictors of survival
- SVM provides strong generalization compared to other models
- KNN shows slight overfitting due to high training accuracy
- Feature selection and preprocessing significantly affect performance

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📁 Project Structure

breast-cancer-ml/
│── Breast_Cancer.csv
│── main.py
│── README.md
│── requirements.txt
│── plots/


---

## 🚀 How to Run

### 1. Clone repository
```bash
git clone https://github.com/your-username/breast-cancer-ml.git
cd breast-cancer-ml
2. Install dependencies
pip install -r requirements.txt
3. Run project
python main.py
📦 Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
🔮 Future Improvements
Apply proper encoding for categorical variables
Feature engineering for better accuracy
Hyperparameter tuning (GridSearchCV)
Try ensemble models (Random Forest, XGBoost)
Deploy model using Flask or Streamlit
Add confusion matrix and ROC curve analysis
👨‍💻 Author

Zarar Ahmed
Artificial Intelligence Student | Machine Learning Enthusiast

⭐ Conclusion

This project demonstrates how machine learning can be used in healthcare for survival prediction. Among all tested models, SVM performed the best, making it the most reliable choice for classification.

📌 Note

This project is for educational purposes only.


---

If you want next upgrade, I can also make:
- 🔥 GitHub README with **badges (accuracy, python, sklearn, license)**
- 📊 Add **confusion matrix + graphs section**
- 🚀 Turn it into **FYP final documentation report**
- 🌐 Or deploy it as **Streamlit web app**
