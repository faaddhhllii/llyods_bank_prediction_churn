# Lloyds Bank Customer Churn Prediction  

## Background  
Customer churn is one of the biggest challenges in the banking industry, including Lloyds Banking Group. With increasing competition, banks need to predict which customers are likely to leave so they can take preventive actions.  

## Project Objective  
This project aims to build a customer churn prediction model using historical customer data. Machine learning models are applied to identify patterns that influence customer decisions to stay or leave the bank’s services.  

## Methodology  
1. **Exploratory Data Analysis (EDA):** Initial analysis of customer data.  
2. **Preprocessing:** Handling missing values, encoding categorical variables, and standardization.  
3. **Modeling:** Implementing machine learning algorithms:  
   - Random Forest  
   - XGBoost  
4. **Model Evaluation:** Using metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC.  

## Results  
- Both Random Forest and XGBoost handled data imbalance relatively well.  
- ROC-AUC scores indicate that the models perform well in predicting churn.  

## Directory Structure  
📂 **project-root/**  
 ┣ 📂 **data/** → contains raw and processed datasets  
 ┗ 📂 **notebooks/** → Jupyter/Colab notebooks for EDA, preprocessing, modeling, and evaluation  

### Notebook Naming Convention  
📂 **notebooks/**  
 ┣ 📓 **1_EDA.ipynb** → Exploratory Data Analysis  
 ┣ 📓 **2_Preprocessing.ipynb** → Data cleaning & preprocessing  
 ┣ 📓 **3_Modeling.ipynb** → Model training with Random Forest & XGBoost  
 ┗ 📓 **4_Evaluation.ipynb** → Model evaluation and performance comparison  

