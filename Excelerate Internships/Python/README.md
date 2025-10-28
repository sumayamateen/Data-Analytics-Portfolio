# Learner Churn Analysis Project 

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Machine Learning](https://img.shields.io/badge/Machine--Learning-Model-green)

---

## Overview
This project predicts **learner churn** (students dropping out) on an online learning platform.  
The workflow includes **data cleaning**, **feature engineering**, **exploratory data analysis (EDA)**, and **predictive modeling** to identify learners at risk of dropping out early.  

**Tech Stack:**  
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)  
- Jupyter Notebook  

---

## Problem Statement
- Learners start courses highly motivated, but many drop out unexpectedly.  
- 31.8% of learners withdraw silently, with no clear indicators, making intervention difficult.  
- Dropouts are influenced by **personal, academic, and platform-related factors**.  
- High enrollments but low completions highlight the need for **predictive solutions** to detect at-risk learners early.

---

## Project Files
- `notebooks/1_Data_Cleaning.ipynb` → Cleaning & preprocessing learner data  
- `notebooks/2_Feature_Engineering.ipynb` → Creating engagement & derived features  
- `notebooks/3_EDA_&_Data_Visualization.ipynb` → Exploring learner behavior & dropout patterns  
- `notebooks/4_Predictive_Modeling.ipynb` → Building models to predict learner churn  
- `presentation/Churn_Analysis_Presentation.pptx` → Summary of the full workflow, including data cleaning, feature engineering, EDA, modeling, insights, and recommendations  

---

## Model Building & Evaluation
- **Feature Selection:** Removed status-based features and checked correlations to avoid data leakage  
- **Models Tested:** Logistic Regression, SVM, Random Forest, Gradient Boosting, XGBoost  
- **Final Model:** Gradient Boosting Classifier — **Accuracy: 91%**, **F1-Score: 0.86**  

---

## Key Results & Recommendations

### Insights
- Delayed first application and long courses → higher dropout risk  
- Engagement metrics, regional application rate, and opportunity choices affect churn  

### Recommendations
- Personalized onboarding and early interventions  
- Restructure courses into weekly modules  
- Develop region-specific content and community hubs  
- Improve recommendation algorithm and use AI prompts to re-engage learners  

---
