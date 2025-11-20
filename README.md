# 🚢 Titanic Dataset – Exploratory Data Analysis (EDA)

This repository contains a complete and well-documented Exploratory Data Analysis (EDA) of the **Titanic: Machine Learning from Disaster** dataset.  
The goal of this project is to clean the dataset, engineer insightful features, visualize key patterns, and perform statistical analysis to understand which factors influenced passenger survival.

---

## 📁 Project Overview
The notebook walks through the full EDA workflow:

- Data loading & initial inspection  
- Data cleaning (missing values, duplicates, outliers)  
- Feature engineering  
- Exploratory visualizations  
- Statistical hypothesis testing  
- Clear documentation & insights after each analysis step  

This project was completed as part of a screening assignment and designed to be **interview-ready** and **industry-standard**.

---

## 🔧 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Jupyter Notebook  

---

## 🧹 Data Cleaning Steps
- Handled missing values using median (Age) and mode (Embarked)  
- Dropped highly incomplete columns (Cabin)  
- Removed duplicate entries  
- Outlier detection & removal using **Interquartile Range (IQR)** method  

---

## 🏗️ Feature Engineering
New derived features were created to uncover deeper survival patterns:

### 🔹 **AgeGroup**
Categorizes passengers into:
- Child  
- Adult  
- Senior  

### 🔹 **FamilySize**
Number of family members onboard (SibSp + Parch + 1)

### 🔹 **Title Extraction**
Extracted from the Name column (Mr, Mrs, Miss, Master, Rare)

These features improved interpretability and helped analyze survival trends more effectively.

---

## 📊 Visualizations
The notebook includes detailed visual analysis with documentation after every plot:

- Gender distribution  
- Age histogram  
- Survival by gender  
- Survival by passenger class  
- Survival by age group  
- Survival by family size  
- Survival by extracted titles  
- KDE plot: Age vs. Survival  
- Correlation heatmap (with engineered features)

Each visualization includes:
- Description  
- Interpretation  
- Key insights  

---

## 📈 Statistical Analysis
The project includes:

### 🔹 Central Tendency
- Mean, median, mode of Age and Fare

### 🔹 Hypothesis Testing
- **T-test** comparing male vs. female survival rates  

Both tests confirm that gender had a significant statistical impact on survival.

---

## 🎯 Key Insights
- Women and children had higher survival rates  
- First-class passengers survived more than second and third class  
- Medium-sized families had better survival chances  
- Title strongly correlates with survival (especially Master, Mrs, Miss)  
- Outliers and skewness in Fare influence overall distribution  
- Gender remains the strongest survival predictor  

