# Customer Churn Prediction – Telecom Domain

## 📌 Project Overview
Customer churn is a major challenge in the telecom industry, directly impacting revenue and customer lifetime value.  
This project focuses on building  machine learning solution to predict whether a customer is likely to churn, enabling proactive retention strategies.

## 🎯 Business Objective
- Predict customers who are likely to churn (cancel telecom services).
- Enable early intervention through targeted retention campaigns.
- Reduce revenue loss by improving customer retention.

## 🧠 Approach
The project follows a structured machine learning lifecycle:

1. **Business Understanding**
   - Defined churn prediction as a classification problem.
   - Identified recall as the primary success metric to minimize missed churners.

2. **Data Understanding & Preparation**
   - Explored customer demographics, service usage, and contract details.
   - Handled missing values and corrected data types.
   - Performed exploratory data analysis (EDA) to uncover churn patterns.

3. **Feature Engineering**
   - Encoded categorical variables.
   - Scaled numerical features where required.
   - Removed non-informative identifiers.

4. **Modeling**
   - Trained and compared multiple models:
     - Logistic Regression
     - Random Forest
     - XGBoost
     - Neural Network
   - Tuned models to optimize performance.

5. **Evaluation**
   - Evaluated models using Recall, F1-score, Accuracy, and ROC-AUC.
   - Selected the best-performing model based on business-driven metrics.
   - Visualized confusion matrix and ROC curve.

6. **Deployment (Optional)**
   - Saved the final model for deployment.
   - Prepared the pipeline for integration with a web application.

---

## 📊 Dataset
- **Source:** Public Telecom Customer Churn Dataset (Kaggle)
- **Data Type:** Customer demographics, service subscriptions, billing, and contract information
- **Target Variable:** `Churn` (Yes / No)

---

## 📈 Key Insights
- Customers with **month-to-month contracts** show significantly higher churn rates.
- **Higher monthly charges** are strongly associated with churn.
- Customers with **longer tenure** are less likely to churn.
- Certain payment methods and service combinations influence churn behavior.

---

## 🛠️ Technologies Used
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow/Keras  
- **Visualization:** Matplotlib, Seaborn  
- **Platform:** Google Colab  

---

## 📦 Repository Structure

