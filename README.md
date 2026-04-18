# SaaS Customer Churn: Predictive ML & Financial Risk Modeling 🚀

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Excel](https://img.shields.io/badge/Excel-Financial--Modeling-green)
![ML](https://img.shields.io/badge/Machine--Learning-Random--Forest-orange)

## 📌 Project Overview
This repository contains a comprehensive analysis of customer churn for a SaaS telecommunications provider. This project goes beyond simple classification—it bridges the gap between **Machine Learning** and **Financial Impact**, translating churn probabilities into a concrete **Revenue at Risk** model.

### Key Achievement:
Identified a total of **$88,529.66** in high-risk Monthly Recurring Revenue (MRR) and provided actionable segmentation for targeted retention campaigns.

---

## 🛠️ Tech Stack
* **Analysis:** Python (Pandas, NumPy)
* **Machine Learning:** Scikit-Learn (Random Forest Classifier)
* **Survival Analysis:** Lifelines (Kaplan-Meier Curves)
* **Business Intelligence:** Microsoft Excel (Pivot Tables, Conditional Formatting, Financial Modeling)

---

## 📊 Project Workflow

### 1. Survival Analysis (Time-to-Event)
Used Kaplan-Meier survival curves to analyze the "lifespan" of different contract types. 
* **Finding:** Month-to-month contracts exhibit a critical "drop-off" zone within the first 5 months, representing a high CAC recovery risk.

### 2. Predictive Modeling (Random Forest)
Trained a Random Forest model to predict individual churn probability based on 18 behavioral variables.
* **Feature Importance:** Monthly Charges (24%) and Tenure (22%) were identified as the primary churn drivers.

### 3. Financial Risk Quantization (Excel)
Exported ML outputs to an interactive Excel model to calculate **Expected Loss**:
> `Expected Loss = Monthly Charges * Churn Probability`

| Risk Category | Key Driver | Financial Exposure |
| :--- | :--- | :--- |
| 🔴 **High Risk** | Month-to-Month | **$88,529.66** |
| 🟡 Medium Risk | Variable | $XX,XXX |
| 🟢 Low Risk | Long-term Contract | $XX,XXX |

---

## 📈 Business Recommendations
1.  **Contract Conversion:** Incentivize Month-to-month users to switch to 1-year plans via targeted discounts to stabilize the $88k exposed revenue.
2.  **Price Sensitivity Guardrails:** Proactively engage high-charge customers with value-added services before they cross the churn threshold.
3.  **Precision Retention:** Use the generated "High Risk Matrix" to prioritize customer success outreach efforts.

---

## 📂 Repository Structure
* `notebooks/` - Contains the Jupyter Notebook with Python code for ML and Survival Analysis.
* `data/` - Raw and processed datasets.
* `financial_model/` - The final Excel (.xlsx) file featuring the Risk Dashboard and Pivot Tables.
* `plots/` - Exported visualizations (Survival curves, Feature importance).

---

## 🔗 Contact & Portfolio
* **Notion Case Study:** [[Link your Notion Project here]](https://www.notion.so/SaaS-Retention-Financial-Risk-Modeling-From-Machine-Learning-to-Revenue-Forecasting-3434961d87b5806d8e2fecfdc38e7a40?source=copy_link)
* **LinkedIn:** [[Link your LinkedIn profile here]](https://www.linkedin.com/in/zixuan-zhao1998/)
