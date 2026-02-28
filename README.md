# 📊 Telecom Customer Churn Analysis & Strategy

## 📝 Project Overview
Customer attrition (Churn) is one of the biggest challenges in the telecom industry. In this project, I analyzed a dataset of telecom customers to uncover the root causes of why **26.5%** of customers are leaving the company. 

The goal of this project is not just to create visualizations, but to provide **data-driven business recommendations** to stabilize Monthly Recurring Revenue (MRR) and improve Customer Retention.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Reporting:** `fpdf` (Automated PDF Report Generation)

## 🔍 Key Data Insights
Through Exploratory Data Analysis (EDA) and Bivariate Analysis, I discovered three critical pain points:

1. **⏳ The 10-Month Danger Zone:** There is a significant negative correlation between customer tenure and churn. Customers who leave have a median tenure of just **10 months**, whereas retained customers average around 38 months.
2. **📅 The Month-to-Month Trap:** The vast majority of leaving customers are on "Month-to-month" contracts. Annual contracts provide massive stability.
3. **⚠️ The Premium Paradox (Fiber Optic):** Despite paying the highest monthly fees, **Fiber Optic** customers have the highest churn rate. The data revealed a critical gap: *the absence of technical support*. Customers paying premium prices without tech support are leaving at alarming rates.

## 💡 Strategic Recommendations
Based on the data, I propose the following business actions:
* **Bundle Free Tech Support:** Integrate Technical Support automatically and free of charge into all premium Fiber Optic plans. It acts as a powerful "retention shield."
* **Contract Conversion Campaigns:** Launch targeted retention campaigns (loyalty discounts) to convert "Month-to-month" subscribers into 1-year annual contracts.
* **Focus on the First 12 Months:** Develop a robust customer onboarding program. Since churn drops drastically after the 12-month mark, surviving this initial period is crucial.

## 🚀 How to Run the Project
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/mohamedsalahabdelhamid/EDA-Telecom-Churn-Prediction.git](https://github.com/mohamedsalahabdelhamid/EDA-Telecom-Churn-Prediction.git)

2.Ensure you have the required libraries installed: pip install pandas numpy matplotlib seaborn fpdf
Open the Jupyter Notebook (.ipynb file) and run the cells sequentially.

📬 Contact
If you have any questions or want to discuss Data Analytics and Business Intelligence, feel free to connect with me!

LinkedIn: https://www.linkedin.com/in/mohamedsalah-abdelhamid/

GitHub: https://github.com/mohamedsalahabdelhamid
