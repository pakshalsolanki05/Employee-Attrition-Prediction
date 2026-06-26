# 👨‍💼 Employee Attrition Prediction Using Machine Learning

## 📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations. Losing skilled employees increases recruitment costs, training expenses, and reduces overall productivity. This project uses Machine Learning to predict whether an employee is likely to leave the company based on various HR-related factors.

The project demonstrates the complete Data Science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, visualization, and business recommendations for HR teams.

---

## 🎯 Problem Statement

The objective of this project is to build a Machine Learning model that predicts employee attrition using employee-related information such as:

- Age
- Monthly Income
- Job Role
- Department
- Work-Life Balance
- Job Satisfaction
- Years at Company
- Overtime
- Performance Rating
- and several other HR attributes.

The project also identifies the major factors influencing employee attrition and provides actionable HR recommendations.

---

## 📂 Dataset

**Dataset Name:** IBM HR Analytics Employee Attrition & Performance

**Source:** Kaggle

The dataset contains **1,470 employee records** with **35 features**, including demographic information, job-related factors, compensation details, and employee satisfaction metrics.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading & Exploration

- Loaded HR dataset
- Explored dataset structure
- Checked missing values
- Identified numerical and categorical features
- Calculated employee attrition rate

---

### 2. Data Cleaning & Preprocessing

- Removed unnecessary columns
- Converted target variable into numerical format
- Applied One-Hot Encoding
- Scaled numerical features using StandardScaler

---

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition

---

### 4. Machine Learning Models

The following classification models were implemented:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

### 5. Model Evaluation

Models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

### 6. Feature Importance

The project identifies the top factors contributing to employee attrition using Logistic Regression coefficients.

---

## 📊 Visualizations

The project includes the following visualizations:

- Department-wise Attrition Rate
- Job Role-wise Attrition Rate
- Monthly Income Box Plot
- Work-Life Balance Analysis
- Years at Company Distribution
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison

---

## 🔍 Key Findings

- Sales Department experienced the highest employee attrition.
- Sales Representatives showed the highest turnover among all job roles.
- Employees working overtime were more likely to leave.
- Lower monthly income was associated with higher attrition.
- Most resignations occurred within the first five years of employment.
- Work-life balance played a significant role in employee retention.

---

## 💡 HR Recommendations

Based on the analysis:

- Focus retention programs on Sales employees and high-turnover job roles.
- Conduct regular career development discussions for employees during their first five years.
- Monitor overtime and improve work-life balance initiatives.
- Review compensation and employee engagement strategies for high-risk groups.

---

## 📁 Project Structure

```
Employee-Attrition-Prediction/

│
├── analysis.ipynb
├── HR_Attrition.csv
├── summary.pdf
├── README.md
├── requirements.txt
│
├── charts/
│   ├── chart1_department_jobrole.png
│   ├── chart2_income_boxplot.png
│   ├── chart3_confusion_matrix.png
│   ├── chart4_feature_importance.png
│   └── chart5_roc_curve.png
│
└── LICENSE
```

---

## 🚀 How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/Employee-Attrition-Prediction.git
```

### Navigate to the Project Folder

```bash
cd Employee-Attrition-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **analysis.ipynb** and run all the cells sequentially.

---

## 📈 Model Performance

Three Machine Learning models were trained and compared.

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

After evaluation using Precision, Recall, F1-Score, and ROC-AUC Score, **Logistic Regression** was selected as the most suitable model for employee attrition prediction because it achieved the highest Recall and ROC-AUC, making it more effective at identifying employees who are likely to leave.

---

## 🌟 Future Improvements

- Hyperparameter Tuning
- SMOTE for Class Imbalance
- XGBoost Classifier
- Streamlit Web Application
- HR Risk Dashboard
- Real-Time Employee Attrition Prediction

---

## 👨‍💻 Author

**Pakshal**

Third Year – Artificial Intelligence & Data Science Engineering

Savitribai Phule Pune University (SPPU)

---

## ⭐ If you found this project useful, consider giving it a star!
