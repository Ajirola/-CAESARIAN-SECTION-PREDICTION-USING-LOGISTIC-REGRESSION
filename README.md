# CAESARIAN-SECTION-PREDICTION-USING-LOGISTIC-REGRESSION

## 📑 TABLE OF CONTENTS

[Project Overview](#-project-overview)  

[Description](#-description)  

[Problem Statement](#-problem-statement) 

[Project Objective](#-project-objective)  

[Key Areas Analyzed](#-key-areas-analyzed)  

[Data Source](#-data-source)  

[Dataset Description](#-dataset-description)  

[Tools](#-tools)  

[Methodology](#-methodology)  

[Data Cleaning](#-data-cleaning)  

[Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)  

[Visual Insights](#-visual-insights)  

[Summary Statistics Interpretation](#-summary-statistics-interpretation)  

[Logistic Regression Model](#-logistic-regression-model)  

[Predictors Interpretation](#-predictors-interpretation)  

[Model Evaluation](#-model-evaluation)  


[Recommendation](#-recommendation)  

[Acknowledgement](#-acknowledgement)  

[Contact](#-contact)


## 📖 PROJECT OVERVIEW
This project applies **logistic regression** to predict whether a woman will undergo a **Caesarean Section (CS)** based on features such as age, blood pressure, delivery type, and heart condition. The goal is to identify significant predictors that influence CS delivery decisions using statistical and visual analysis.

## 🔍 DESCRIPTION
Caesarean deliveries are critical for managing high-risk pregnancies but can be overused if not guided by evidence. Predicting CS risk helps clinicians tailor care and avoid unnecessary procedures.

## ❓ PROBLEM STATEMENT
Health professionals lack predictive insights into CS risk, leading to under- or over-utilization. Early predictions can assist in planning safer delivery options for mothers.

## 🎯 PROJECT OBJECTIVE
This project aims to:

✅ Analyze medical and delivery-related features influencing CS delivery

✅ Build a logistic regression model to predict CS occurrence

✅ Identify significant predictors using statistical tests

✅ Support better maternal healthcare decisions with data

## 🔍 KEY AREAS ANALYZED
📌 Caesarean distribution by blood pressure, age and delivery type

📌 Feature correlation using heatmaps 

📌 Significant predictors via logistic regression 

📌 Performance evaluation (accuracy, AUC)


## 📊 DATA SOURCE
The data was obtained from kaggle website 

Here's the link to the dataset: https://www.kaggle.com/datasets/amir75/caesarean-section-classification?utm_source=chatgpt.com

## 📂 Dataset Description
Dataset: Caesarean Section Classification  

Records: 80 patient cases  
  

| Column             | Description                           |
|--------------------|---------------------------------------|
| Age                | Mother's age                          |
| Delivery Type      | Timely or Premature                   |
| Blood Pressure     | Normal, High, or Low                  |
| Heart Problem      | Yes or No                             |
| Caesarian          | Target variable (Yes or No)           |


## ⚒️ Tools Used
 **Python**(**Pandas**, **Seaborn**, **Matplotlib**
**Statsmodels**, **Scikit-learn**)

## 📒 Methodology
1️⃣ Load and clean dataset  

2️⃣ Standardize and encode variables  

3️⃣ Perform exploratory data analysis  

4️⃣ Check multicollinearity using VIF  

5️⃣ Train logistic regression model  

6️⃣ Interpret model coefficients  

7️⃣ Evaluate model performance

## 🧹 Data Cleaning
✅ Renamed and standardized columns  

✅ Encoded categorical variables (e.g., Caesarian 0/1)  

✅ Verified **no missing** or duplicate values  

✅ Converted boolean features to integers  

✅ Dropped redundant **Delivey No** column

## 🧮 Summary Statistics Interpretation

| Statistic | Age |
|-----------|-----|
| Mean      | 27.7 |
| Median    | 27   |
| Std Dev   | 5.0 |
| Min–Max   | 17–40 |

Majority of patients were in their late 20s to early 30s, common childbearing age group. The dataset provides a good age range for modeling.

## 📊 Statistical Insights and Data Visualization

### 📊 Target Distribution
![Screenshot](Screenshot_20250728-190206.jpg)

- **Yes (CS delivery)**: 46  
- **No**: 34  

> Majority of deliveries resulted in Caesarean Sections (~58%).


