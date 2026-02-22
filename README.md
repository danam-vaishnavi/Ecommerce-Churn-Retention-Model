# Ecommerce-Churn-Retention-Model
Predictive churn model identifying $190k in at-risk revenue using RFM segmentation and Logistic Regression.

# E-Commerce Churn & Retention Analysis
### 🚀 Impact: Identified $192,997.68 in At-Risk Revenue

## 📌 Project Overview
This project addresses the "bottom line" of e-commerce by identifying why customers stop buying and which high-value segments are most likely to leave. Using a combination of **RFM Analysis** and **Machine Learning**, I quantified the financial risk and developed a data-driven retention strategy.

## 📊 Key Findings
* **The "Risk Threshold":** Customers who do not log in for **30+ days** show a 70% higher probability of churning.
* **Churn Drivers:** Logistic Regression analysis revealed that **Login Frequency** is a more significant predictor of retention than the total amount spent.
* **Revenue at Risk:** A specific group of 110 high-value customers represents **$192,997.68** in historical value that is currently at risk.

## 🛠️ Tech Stack
* **Python** (Pandas, NumPy) for data engineering.
* **Scikit-Learn** for Logistic Regression modeling.
* **Matplotlib/Seaborn** for the Executive Dashboard.
* **RFM Modeling** (Recency, Frequency, Monetary).

## 💡 Strategic Recommendations
1. **Early Warning System:** Trigger automated "Personalized Nudges" at the 15-day inactivity mark.
2. **High-Value Recovery:** Deploy 20% discount codes to "Churn Risk" segments who have exceeded 30 days of inactivity.
3. **Frequency Gamification:** Implement a loyalty "streak" program to reward 3+ purchases per month, directly influencing the model's most significant retention variable.

## 📂 Project Structure
* `CustomerChurnAndRetentionModel.ipynb`: Full Python code for cleaning, modeling, and visualization.
* `requirements.txt`: List of dependencies.
