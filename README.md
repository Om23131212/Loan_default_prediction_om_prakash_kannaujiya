# Loan_default_prediction_om_prakash_kannaujiya
# 🏦 Loan Default Prediction

## 📘 Overview

This project aims to develop a machine learning model to predict whether a loan applicant is likely to default. Early identification of high-risk applicants can significantly reduce financial losses for lending institutions. We apply classification algorithms—primarily Decision Trees—and visualize feature importance to understand the key factors influencing loan defaults.

---

## 🎯 Objective

To build a predictive model that classifies loan applicants as **"Default"** or **"No Default"**, based on various financial and demographic features. The model will assist banks and financial institutions in making data-driven lending decisions.

---

## 🧪 Methodology

### 1. **Data Collection**
The dataset consists of applicant information such as income, loan amount, employment status, credit history, and more. The target variable indicates whether the applicant defaulted on their loan.

### 2. **Data Preprocessing**
- Handled missing values through imputation.
- Categorical variables were encoded using Label Encoding and One-Hot Encoding.
- Numerical features were scaled where necessary.
- Data was split into **training (80%)** and **testing (20%)** sets to evaluate model performance.

### 3. **Exploratory Data Analysis (EDA)**
- Visualized distributions, correlations, and class imbalances.
- Identified key trends: applicants with poor credit history and low income had higher default rates.

### 4. **Model Building**
Implemented and compared multiple classification algorithms:
- **Logistic Regression**
- **Decision Tree Classifier** (main focus)
- **Random Forest**
- **XGBoost (Extreme Gradient Boosting)**

### 5. **Model Evaluation**
Used various metrics to evaluate model performance:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC Score**

### 6. **Model Interpretation**
- Visualized the structure of the decision tree.
- Analyzed **feature importance** to identify which input variables most influenced loan default predictions.

---

## 📊 Results

| Metric        | Decision Tree (Example) |
|---------------|--------------------------|
| Accuracy      | 85%                      |
| Precision     | 82%                      |
| Recall        | 78%                      |
| F1 Score      | 80%                      |
| ROC-AUC       | 0.87                     |

Top features influencing prediction:
- Credit History
- Applicant Income
- Loan Amount
- Employment Type
- Number of Dependents

---

## 📈 Visualizations

- Decision Tree Plot  
- Feature Importance Bar Chart  
- ROC Curve

All visualizations are available in the `./visuals/` directory or the Jupyter notebook.

---

## 🛠 Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Scikit-learn** – Model building
- **Matplotlib**, **Seaborn** – Visualization
- **XGBoost** – Advanced classification
- **Jupyter Notebook** – Development environment

---

## 🔍 Conclusion

This project demonstrates the potential of machine learning in risk assessment and credit evaluation. The decision tree model offers a balance of interpretability and accuracy, making it suitable for use in financial applications.

---

## 🚀 Future Enhancements

- Address class imbalance using oversampling techniques like **SMOTE**.
- Deploy the model via **Flask** or **Streamlit** for real-time prediction.
- Integrate real-world data pipelines for dynamic updating.

---

## 📁 Repository Structure


---

## 📬 Contact

**Author**: [om prakash kannaujiya]  
📧 Email: your.email@example.com  
🌐 GitHub: [github.com/yourusername](https://github.com/yourusername)

---

⭐ If you found this project useful, feel free to give it a star!

