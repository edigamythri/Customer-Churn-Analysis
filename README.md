# 📊 Customer Churn Analysis – Telecom Dataset

This project analyzes customer churn behavior in a telecom company using Python. The goal is to understand why customers leave and provide actionable insights to reduce churn and improve retention.

## 🔍 Objective

- Identify key factors leading to customer churn
- Visualize patterns in customer behavior
- Recommend strategies to reduce churn

## 📁 Dataset

The dataset contains information on 7,043 telecom customers with features including:

- Demographics (Gender, SeniorCitizen, Partner, Dependents)
- Account details (Tenure, Contract Type, Payment Method)
- Services used (Internet, OnlineSecurity, TechSupport, etc.)
- Charges (MonthlyCharges, TotalCharges)
- Churn status (Yes/No)

## 🧹 Data Preprocessing

- Replaced blank TotalCharges with 0
- Converted `SeniorCitizen` values from 0/1 to No/Yes
- Converted `TotalCharges` to numeric
- Handled categorical variables for analysis

## 📊 Key Insights

- **26.54%** of customers have churned.
- **Tenure:** Customers with only 1–2 months of service accounted for **~50%** of churns.
- **Contract Type:** Over **40%** of churned users were on **month-to-month** contracts.
- **Add-on Services:** Customers without services like **Online Security**, **Tech Support**, and **Backup** had **2x higher churn rates**.
- **Payment Method:** **Electronic Check** users had the highest churn rate (~45%).

## 📈 Visualizations

- Pie and bar charts illustrating churn distribution
- Countplots for each service feature vs. churn
- Correlation between contract type, tenure, payment methods and churn

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 💡 Business Recommendations

- Improve onboarding experience to retain new users
- Offer incentives for longer-term contracts
- Promote bundled add-on services for higher retention
- Encourage auto-payments through reliable digital methods

## 📂 Project Structure

  
