# 🚀 HR Analytics – Employee Attrition & Performance Prediction

## 📌 Overview
Built a Machine Learning–based HR Analytics system to predict employee attrition and analyze workforce performance using real-world HR data.

The system helps organizations:
- Reduce employee turnover
- Identify high-risk employees early
- Improve retention strategies
- Enable data-driven HR decisions

---

## 🎯 Problem Statement
Employee attrition leads to increased hiring costs and productivity loss.  
This project predicts whether an employee is likely to leave using historical HR data and behavioral patterns.

---

## ✨ Key Features
✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Outlier Detection (IQR Method)  
✔ Feature Engineering & Encoding  
✔ Model Training & Comparison  
✔ Visualization & Business Insights  

---

## 🤖 Machine Learning Models Used
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

---

## 📊 Results (Test Set Performance)

| Model | Accuracy | Precision | Recall | F1-score |
|-------|----------|-----------|---------|-----------|
| **Logistic Regression** | **87.4%** | 86.0% | 87.4% | 85.7% |
| Random Forest | 84.0% | 78.9% | 84.0% | 77.9% |
| XGBoost | 83.7% | 79.7% | 83.7% | 80.3% |
| SVM | 86.7% | 86.3% | 86.7% | 83.2% |

✅ **Best Model → Logistic Regression**

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📂 Project Structure
HR-Analytics-Employee-Attrition-Performance/
│
├── data/ # dataset files
├── notebooks/ # EDA + model training notebooks
├── models/ # saved trained models
├── requirements.txt # dependencies
└── README.md


---

## ▶️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/PURUSHOTTAM0001/HR-Analytics-Employee-Attrition-Performance.git
cd HR-Analytics-Employee-Attrition-Performance

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run notebook
jupyter notebook
