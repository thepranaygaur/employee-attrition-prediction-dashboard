````md
# Employee Attrition Prediction & HR Analytics Dashboard

## 📌 Project Overview
This project focuses on predicting employee attrition using Machine Learning and analyzing workforce trends using an interactive Power BI dashboard.  

The objective is to help HR teams identify employees at high risk of leaving and take proactive retention actions.

---

## 🎯 Business Problem
Employee attrition increases hiring cost, training cost, and productivity loss.  

Using HR data, this project predicts attrition and uncovers the major factors influencing employee exits.

---

## 📂 Dataset
IBM HR Analytics Employee Attrition Dataset

- Total Records: 1470 Employees  
- Features: 35 Columns  
- Target Variable: Attrition (Yes / No)

---

## 🛠️ Tools & Technologies

### Python
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

### Power BI
- Dashboard Creation  
- KPI Cards  
- Interactive Filters  

---

## 📊 Project Workflow

### 1. Data Preprocessing
- Null value check  
- Blank value check  
- Constant column removal  
- Target encoding  
- One-hot encoding  

### 2. Exploratory Data Analysis
- Attrition by Department  
- Attrition by Overtime  
- Attrition by Job Role  
- Attrition by Age Group  
- Salary vs Attrition  

### 3. Model Building
Models used:

- Logistic Regression  
- Balanced Logistic Regression  
- Random Forest Classifier  

### 4. Model Evaluation
Metrics used:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC AUC Score  

---

## 🏆 Final Result

Balanced Logistic Regression improved recall for attrition employees, making it more useful for HR retention use-cases.
ROC AUC Score achieved good class separation performance.

---

## 📊 Dashboard Preview

![Dashboard Screenshot](dashboard_screenshot.png)

---

## 📈 Key Business Insights

- Employees doing overtime showed higher attrition rate  
- Sales department had highest attrition rate  
- Younger employees had higher attrition tendency  
- Certain job roles had significantly higher attrition risk  
- Lower salary groups were more likely to leave  

---

## 📊 Power BI Dashboard Includes

- Total Employees  
- Attrition Count  
- Attrition Rate %  
- Average Age  
- Average Salary  
- Attrition by Department  
- Attrition by Overtime  
- Attrition by Job Role  
- Attrition by Age Group  

---

## 📁 Project Files

- `HR_Attrition_Project.ipynb`
- `HR_Attrition_Dashboard.pbix`
- `dashboard_screenshot.png`
- `hr_attrition_model.pkl`
- `scaler.pkl`

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
````

Open Jupyter Notebook and run:

```bash
HR_Attrition_Project.ipynb
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* SMOTE for class imbalance
* Streamlit deployment
* Real-time HR monitoring dashboard

---

## 👨‍💻 Author

Pranay Gaur

```
```
