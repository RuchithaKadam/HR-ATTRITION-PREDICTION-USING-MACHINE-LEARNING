📊 HR Attrition Prediction using Machine Learning

📌 Project Overview
Employee attrition is a major challenge for organizations as it affects productivity, cost, and team performance. This project aims to build a machine learning model that predicts whether an employee is likely to leave the company based on various factors such as job role, salary, work environment, and experience.

The goal is to help HR teams take proactive measures to reduce employee turnover using data-driven insights.

🎯 Problem Statement
Predict employee attrition (Yes/No) using historical HR data and identify the key factors influencing employee turnover.

📂 Dataset Description

The dataset contains employee-related features such as:
  • Age
  
  • Job Role
  
  • Department
  
  • Monthly Income
  
  • Job Satisfaction
  
  • Work Experience
  
  • Overtime
  
  • Distance from Home
  
  • Education Level
  
  • Performance Rating]=
  
  • And other HR-related attributes
  
Target Variable:

• Attrition (Yes = 1, No = 0)

🔧 Project Workflow
1️⃣ Data Preprocessing

• Removed unnecessary columns

• Handled missing values

• Converted categorical variables using encoding techniques

• Treated class imbalance using SMOTE
• Standardized numerical features

2️⃣ Exploratory Data Analysis (EDA)
• Analyzed attrition distribution
• Visualized correlations using heatmaps
• Identified important features influencing attrition

3️⃣ Model Building
• Implemented multiple classification algorithms:
• Logistic Regression
• Decision Tree (with Hyperparameter Tuning)
• Random Forest
• Gradient Boosting

4️⃣ Model Evaluation
Models were evaluated using:
• Accuracy
• Precision
• Recall
• F1-Score
• Confusion Matrix
• ROC-AUC Curve

| Model                        | Train Score | Test Accuracy |
| ---------------------------- | ----------- | ------------- |
| Random Forest Classifier     | 1.0000      | 0.9530        |
| Gradient Boosting Classifier | 0.9903      | 0.9092        |
| Decision Tree (Tuned)        | 0.9913      | 0.9011        |
| Logistic Regression          | 0.8746      | 0.8541        |


The Random Forest model achieved the highest accuracy with strong generalization performance.

📊 Key Insights
• Overtime employees are more likely to leave.
• Low job satisfaction strongly impacts attrition.
• Monthly income and job level influence employee retention.
• Work-life balance plays a significant role in turnover.

🚀 Technologies Used
• Python
• Pandas & NumPy
• Matplotlib & Seaborn
• Scikit-learn
• SMOTE (Imbalanced-learn)

💡 Business Impact
• This model can help HR departments:
• Identify high-risk employees early
• Design targeted retention strategies
• Improve workforce planning
• Reduce hiring and training costs

Project: HR Attrition Prediction
Author: Ruchitha M
Created: 2026
Description: Machine learning model to predict employee attrition.
