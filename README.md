
# 📉 Customer Churn Prediction using Machine Learning

This project aims to predict customer churn using the **Telco Customer Churn** dataset. It demonstrates the complete end-to-end machine learning pipeline — from data cleaning and exploration to model building, evaluation, and saving the trained model.

---

## 📌 Problem Statement
**Churn** refers to customers who stop doing business with a company. Identifying potential churners allows businesses to take proactive steps to retain customers and reduce loss.

---

## 📂 Dataset
- **Source**: IBM Telco Customer Churn Dataset
- **Target Variable**: `Churn` (Yes / No)
- **Features**: Customer demographics, billing, contract type, tenure, etc.

---

## 🧪 Workflow

1. **Data Cleaning**  
   - Removed invalid entries  
   - Converted `TotalCharges` to numeric  
   - Handled missing values

2. **Exploratory Data Analysis (EDA)**  
   - Plotted histograms and boxplots  
   - Analyzed churn distribution and feature impact

3. **Data Preprocessing**  
   - Label encoding for categorical variables  
   - Handled class imbalance using **SMOTE**

4. **Model Training**  
   - Trained multiple models:
     - Decision Tree
     - Random Forest
     - XGBoost

5. **Model Evaluation**  
   - Metrics used: **Accuracy, Precision, Recall, F1-score**  
   - Used **confusion matrix** and **classification report**

6. **Model Saving**  
   - Best model was saved using `pickle` for future use

---

## 🧠 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `xgboost`
- `imblearn` (SMOTE)

---

## ✅ Results

- Best model: **XGBoost Classifier**
- Achieved ~80–85% accuracy on test data
- Balanced performance across precision, recall, and F1-score

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Customer_Churn_Prediction_using_ML.ipynb` | Main notebook |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Dataset |
| `model.pkl` | Saved ML model |
| `README.md` | Project description |

---

## 🚀 How to Run

1. Clone this repository  
2. Upload the dataset to your notebook environment  
3. Run all cells in the notebook  
4. Check evaluation metrics and saved model output

---

## 🤝 Acknowledgements

- Dataset courtesy: IBM Sample Data
- Built and tested in: Google Colab

---

## 🧾 License

This project is licensed for educational and personal use.
