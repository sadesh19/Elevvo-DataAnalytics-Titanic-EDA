# Titanic: Machine Learning from Disaster - EDA 🚢

### **Project Overview**

This project focuses on **Exploratory Data Analysis (EDA) and Data Cleaning** of the classic Titanic dataset as part of my **Data Analytics Internship**. The goal is to identify key factors that influenced passenger survival using **Python** and statistical visualizations.

### **Dataset**

**Source:** [Titanic: Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/c/titanic)

**Task Level:** Level 1

### **Key Tasks Performed**

1. **Data Cleaning & Preprocessing**

   * Filled missing Age values with the median; handled missing Embarked values using the mode.
   * Dropped the Cabin column due to >75% missing values.
   * Converted categorical variables (Sex, Embarked) into numerical types for analysis.

2. **Insight Generation**

   * Generated summary statistics for Age and Fare.
   * Calculated survival rates by **Gender** and **Passenger Class (Pclass)**.

3. **Data Visualization**

   * Bar plots for survival by gender and class.
   * Correlation heatmap for numerical features.
   * Age distribution plots showing survival density across age groups.

### **Tools & Libraries Used**

* Python, Pandas, Matplotlib, Seaborn
* Kaggle Notebooks for development

### **Key Insights**

* **Gender** was the strongest predictor: females had much higher survival rates.
* **Passenger Class (Pclass)** strongly correlated with survival: 1st-class passengers had the highest probability.
* Young children showed higher survival density, reflecting the historical “women and children first” pattern.
