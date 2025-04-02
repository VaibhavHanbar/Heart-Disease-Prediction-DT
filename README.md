# Heart-Disease-Prediction-DT
A Decision Tree-based machine learning model to predict heart disease risk. Includes EDA, hyperparameter tuning, and performance evaluation (79% accuracy). Built with Python (scikit-learn, pandas, matplotlib). Ideal for ML beginners in healthcare analytics

# Heart Disease Prediction using Decision Trees

**Author**: Vaibhav Hanbar 
**Last Updated**: 02/04/2025 

---

## **Project Overview**  
A machine learning model that predicts the likelihood of heart disease based on clinical parameters using a **tuned Decision Tree classifier**. Achieves **79% accuracy** with balanced precision/recall.

---

## **Table of Contents**  
1. [Features](#features)  
2. [Technical Approach](#technical-approach)  
3. [Results](#results)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [License](#license)  

---

## **Features**  
✔ **Data Analysis**: Exploratory Data Analysis (EDA) with visualizations  
✔ **Model Training**: Decision Tree with GridSearchCV hyperparameter tuning  
✔ **Interpretability**: Feature importance analysis and tree visualization  
✔ **Evaluation**: Accuracy, precision, recall, and F1-score metrics  

---

## **Technical Approach**  
### **Data**  
- **Source**: HeartDisease  
- **Features**: 13 clinical features (age, cholesterol, blood pressure, etc.)  
- **Target**: Binary classification (0 = No disease, 1 = Disease)  

### **Model**  
Best Hyperparameters: {'criterion': 'gini', 'max_depth': 3, 'min_samples_leaf': 4, 'min_samples_split': 2}
