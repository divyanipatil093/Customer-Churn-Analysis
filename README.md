# 📊 Customer Churn Analysis – Python EDA Project

## 🧠 Objective
This project focuses on analyzing customer churn behavior to identify key factors influencing customer attrition. The goal is to perform Exploratory Data Analysis (EDA) and derive actionable business insights to improve customer retention.

---

## 📂 Dataset Overview
The dataset includes customer information such as:
- Contract type
- Tenure
- Internet service type
- Payment method
- Additional services
- Churn status

---

## 📊 Key Insights

### 1. Overall Churn
- Retained Customers: **73.46%**
- Churned Customers: **26.54%**

---

### 2. Contract Type
- Month-to-Month contracts have the highest churn
- Long-term contracts significantly improve retention

---

### 3. Tenure Analysis
- New customers churn the most
- Longer tenure → higher loyalty

---

### 4. Internet Service
- Fiber Optic users show higher churn
- DSL users have lower churn rates

---

### 5. Service-Based Insights
Customers without the following services are more likely to churn:
- Online Security
- Tech Support
- Online Backup
- Device Protection

---

### 6. Payment Method
- Electronic Check users churn more
- Auto-payment users are more stable

---

### 7. Demographics
- Senior citizens show higher churn rates

---

## 📊 Visualizations Used
- Count Plots
- Pie Charts
- Stacked Bar Charts
- Histograms
- Correlation Heatmaps

---

## 💡 Business Recommendations
- Promote long-term contracts
- Improve onboarding experience
- Enhance Fiber Optic service quality
- Encourage bundled service adoption
- Increase automatic payment usage
- Create retention strategies for high-risk users

---

## 🛠️ Tech Stack
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run This Project

```bash
git clone https://github.com/divyanipatil093/customer-churn-eda-python.git
cd customer-churn-eda-python
pip install -r requirements.txt
jupyter notebook
