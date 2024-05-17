# KaggleX-Biopic-Mentorship-Program-Cohort-3-2023
## Final Project - **📚 Predicting Student Adaptivity Level in Online Education 🎓**

Welcome to the **Predicting Student Adaptivity Level in Online Education** project! This repository contains everything you need to understand, replicate, and explore the prediction of students' adaptability to online education using various machine learning models.

### Table of Contents
1. Problem Statement
2. Data Collection and Understanding
3. Data Pre-Processing
4. Exploratory Data Analysis (EDA)
5. Model Training
6. Model Comparison
7. Best Model Selection


### Problem Statement - 
The COVID-19 pandemic has slowed down education for many underprivileged students. Online education is a viable solution, but we need to assess how well students adapt to this mode of learning. This project aims to analyze and predict students' adaptivity levels in online education using a dataset that measures various aspects of their adaptive skills.

### Data Collection and Understanding
* **Data Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/mdmahmudulhasansuzan/students-adaptability-level-in-online-education)
* **Features:** Gender, Age, Financial Condition, IT Student, Location, Load Shedding, Education Level, Institution Type, Self LMS, Class Duration, Internet Type, Network Type, Device
* **Target:** Adaptivity Level

### Data Pre-Processing
🗃️ **Total records:** 1205

🏷️ **13 categorical features** and **1 target feature**

🚫 No missing values

📂 All **data types** are **"object"**

### Exploratory Data Analysis
A comprehensive **EDA** was conducted to understand the distribution and relationships within the data. Key _insights_ were drawn to guide _model training_ and _feature selection_.

### Model Training
Various machine learning models were used for classification:

* **Basic Algorithms:** SVC, Gaussian Naive Bayes, Logistic Regression, Decision Tree, Random Forest, KNN
* **Advanced Algorithms:** XGBoost, Ensemble-Voting Classifier, Gaussian Process Classifier, Neural Network, AdaBoost, CatBoost

### Model Comparison
**_Basic Classification Algorithm Accuracies_**
**Model	Test Accuracy**
* Logistic Regression	0.68
* Gaussian Naive Bayes	0.68
* Support Vector Classification	0.71
* K-Nearest Neighbors (KNN)	0.78
* Decision Tree Classifier	0.89
* Random Forest Classification	0.91

**_Advanced Classification Algorithm Accuracies_**
**Model	Test Accuracy**
* XGBoost	0.76
* Neural Network	0.87
* Ensemble-Voting Classifier	0.89
* Gaussian Process Classifier	0.89
* CatBoost	0.90
* AdaBoost	0.92

### Best Model Selection
_The top 5 models with the highest accuracies:_

1. 🥇 AdaBoost: 92%
2. 🥈 Random Forest: 91%
3. 🥉 CatBoost: 90%
4. Gaussian Process Classifier: 89%
5. Decision Tree Classifier and Ensemble-Voting Classifier: 88%

### Project Links
* 📔 [Google Colab Notebook](https://colab.research.google.com/drive/1X52hazlrJRDl7vkXYX4GY9N9pnyV6mDQ?usp=sharing) 
* 📊 [Kaggle Notebook](https://www.kaggle.com/code/garimasharma05/analysing-student-performance-based-onlineeducat)

