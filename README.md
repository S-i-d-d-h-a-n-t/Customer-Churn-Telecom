# Customer Churn Prediction 

This repository contains a machine learning project focused on predicting customer churn. By analyzing customer demographics, account details, and service usage, the model identifies patterns that lead to customer attrition, enabling businesses to implement proactive retention strategies.

## 📊 Project Overview
Customer churn is a critical challenge for service-based industries. This project leverages a **Random Forest Classifier** to provide accurate predictions. The workflow covers everything from data cleaning and exploratory data analysis (EDA) to model training and performance evaluation.

## 🚀 Key Features
* **Data Preprocessing:** Handling categorical encoding and feature scaling.
* **Exploratory Data Analysis (EDA):** Identifying correlations and trends using visual tools.
* **Machine Learning Pipeline:** Implementing a Random Forest model with performance tuning.
* **Model Evaluation:** Using industry-standard metrics to validate model reliability.

## 📈 Visualizations
The project includes several analytical plots to interpret the model's findings:
* **Correlation Heatmap:** Visualizes the relationship between different customer features.
* **Feature Importance:** Highlights which factors (e.g., contract type, monthly charges) most influence churn.
* **Confusion Matrix:** Provides a detailed breakdown of correct and incorrect classifications.
* **ROC Curve:** Demonstrates the model's diagnostic ability and AUC (Area Under Curve) score.

## 🛠️ Technologies Used
* **Python**
* **Pandas & NumPy** (Data Manipulation)
* **Scikit-Learn** (Machine Learning)
* **Matplotlib & Seaborn** (Data Visualization)

## 📁 File Structure
* `customer-churn-prediction.ipynb`: The primary Jupyter Notebook containing the full code and analysis.
* `heat-map.png`: Visual representation of feature correlations.
* `Feature Importance.png`: Chart showing the most impactful variables.
* `Randomforest-Classification-Confusion Matrix.png`: Evaluation of classification accuracy.
* `ROC Curve Random Forest.png`: The model's performance curve.

## 📝 How to Use
1.  Clone the repository.
2.  Install required libraries: 
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  Open and run the `customer-churn-prediction.ipynb` notebook in a Jupyter environment or Kaggle.

## 🏆 Results
The Random Forest model demonstrates strong predictive power, effectively distinguishing between loyal customers and those likely to churn. Insights from the feature importance analysis provide actionable data for marketing and customer success teams to reduce attrition rates.
