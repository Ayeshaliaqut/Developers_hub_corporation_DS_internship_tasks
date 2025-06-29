# Developers_hub_corporation_DS_internship_tasks
Data Science &amp; Analytics internship tasks
# 🧠 Data Science Projects: Classification & Regression Tasks

This repository contains a series of hands-on machine learning tasks designed to practice core data science skills such as data exploration, cleaning, modeling, evaluation, and visualization. Each task addresses a real-world problem using open datasets and standard Python ML libraries.


## Tasks Overview

### Task 1: Exploring and Visualizing a Simple Dataset (Iris Classification)

**Objective:** Understand relationships between Iris flower measurements and visualize species differences.

**Approach:**
- Loaded the Iris dataset using `seaborn`.
- Displayed structure with `.shape`, `.columns`, `.head()`.
- Visualized data using scatter plots, histograms, box plots, and pairplots.

**Insights:**
- Petal measurements are more effective for classifying species than sepal features.
- Visualizations showed clear separation between species groups.

---

### Task 2: Credit Risk Prediction

**Objective:** Predict whether a loan applicant will default on a loan.

**Approach:**
- Cleaned missing values and handled categorical data.
- Explored key features like loan amount, education, credit history, and income.
- Trained a Logistic Regression model to classify loan status.
- Evaluated model with accuracy and confusion matrix.

**Results & Insights:**
- The model performed well in identifying potential defaults.
- Credit history and applicant income were found to be strong predictors.

---

###  Task 3: Customer Churn Prediction (Bank Customers)

**Objective:** Identify which customers are likely to leave the bank.

**Approach:**
- Encoded categorical variables (e.g., geography, gender).
- Trained an XGBoost classifier for churn prediction.
- Used SHAP values to analyze feature importance.

**Results & Insights:**
- Accuracy was high, with **balance**, **age**, and **credit score** as top churn indicators.
- SHAP plots made the predictions interpretable for business understanding.

---

###  Task 4: Predicting Insurance Claim Amounts

**Objective:** Estimate medical insurance charges based on customer data.

**Approach:**
- Trained a Linear Regression model.
- Visualized relationships between charges and features like BMI, age, and smoking status.
- Evaluated model using **MAE** and **RMSE**.

**Results:**
- **MAE:** 4186.51  
- **RMSE:** 5799.59  
- Smokers tend to have significantly higher insurance charges, followed by age and BMI.

---

###  Task 5: Personal Loan Acceptance Prediction

**Objective:** Predict which customers are likely to accept a personal loan offer.

**Approach:**
- Performed EDA on age, job, marital status, and other demographics.
- Built a Logistic Regression classifier after data cleaning and encoding.
- Visualized trends using pie charts, stacked bars, and custom plots.

**Results:**
- **Accuracy:** 80%  
- Precision and recall were well-balanced.
- Single individuals and some job types (e.g., students, technicians) showed higher acceptance rates.

---

##  Technologies Used

- **Python 3**
- **pandas**, **numpy**
- **matplotlib**, **seaborn**
- **scikit-learn**, **xgboost**, **shap**
- Jupyter Notebook / Google Colab

---

## Highlights

- Clean, well-commented code throughout.
- Advanced, appealing visualizations.
- Real-world business insights derived from data.
- Each notebook is self-contained and interpretable.

---

##  Author
**Name:** *[Ayesha liaquat]*  




