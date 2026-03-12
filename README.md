# 📊 Customer Churn Analysis — Telco Dataset
**Tool:** Python &nbsp;|&nbsp; **Domain:** Telecom &nbsp;|&nbsp; **Dataset:** Telco Customer Churn (Kaggle)

A complete Python-based exploratory data analysis (EDA) project to identify why customers churn and provide actionable business recommendations to reduce churn rate using Pandas, Matplotlib, and Seaborn.

---

## 📈 Charts Preview

### Chart 1 — Overall Churn Rate
<img width="1050" height="750" alt="chart1_churn_rate" src="https://github.com/user-attachments/assets/e6e68feb-cea2-429c-a09d-808839c7a447" />


### Chart 2 — Churn by Contract Type
<img width="1200" height="750" alt="chart2_contract_churn" src="https://github.com/user-attachments/assets/ed74791c-3358-4be8-8b3e-3f91e41a76fa" />


### Chart 3 — Churn by Customer Tenure
<img width="1500" height="750" alt="chart3_tenure_churn" src="https://github.com/user-attachments/assets/1ba191be-21bf-4d00-90c3-ffdc617628bd" />

### Chart 4 — Monthly Charges vs Churn
<img width="1200" height="750" alt="chart4_charges_churn" src="https://github.com/user-attachments/assets/ba637d6d-0e50-474e-943f-1fcc417fefaa" />


### Chart 5 — Churn by Internet Service
<img width="1200" height="750" alt="chart5_internet_churn" src="https://github.com/user-attachments/assets/e338bad8-985a-4cc5-9a91-7d7b297fa089" />


### Chart 6 — Churn by Payment Method
<img width="1500" height="750" alt="chart6_payment_churn" src="https://github.com/user-attachments/assets/e2629b42-eaa9-4ff9-ad17-d097e283016a" />

---

## 🎯 Business Problem

A telecom company is losing customers every month. The business needs to understand **who is churning, why they are churning, and what can be done to retain them.** This analysis answers those questions using real customer data.

---

## 💡 Key Insights

| # | Insight |
|---|---|
| 1 | **26.5%** overall churn rate — 1 in 4 customers leaves |
| 2 | **Month-to-month** contract customers churn at **42%** vs 3% for 2-year contracts |
| 3 | **New customers (0–12 months)** are at highest churn risk |
| 4 | Churned customers pay **~$13 more per month** than retained ones |
| 5 | **Fiber Optic** internet users churn at **42%** — highest of all service types |
| 6 | **Electronic check** payment users churn the most at **45%** |

---

## ✅ Business Recommendations

- Offer discounts to convert month-to-month customers to annual contracts
- Create an onboarding loyalty program for first 12 months
- Investigate Fiber Optic service quality and pricing
- Promote auto-pay options over electronic checks
- Target high monthly charge customers with retention offers

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, transformation |
| NumPy | Numerical operations |
| Matplotlib | Chart creation and styling |
| Seaborn | Statistical visualizations |
| Google Colab | Notebook environment |

---

## 📋 Analysis Workflow

```
1. Import Libraries
2. Load Dataset
3. Data Cleaning (fix TotalCharges, handle nulls)
4. Overall Churn Rate — Pie Chart
5. Churn by Contract Type — Bar Chart
6. Churn by Tenure — Histogram
7. Monthly Charges vs Churn — Box Plot
8. Churn by Internet Service — Bar Chart
9. Churn by Payment Method — Bar Chart
10. Key Insights & Business Recommendations
```

---

## 📁 Files in this Repo

| File | Description |
|---|---|
| `Customer_Churn_Analysis.ipynb` | Complete Jupyter notebook |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Raw dataset |
| `chart1_churn_rate.png` | Overall churn pie chart |
| `chart2_contract_churn.png` | Churn by contract type |
| `chart3_tenure_churn.png` | Churn by tenure histogram |
| `chart4_charges_churn.png` | Monthly charges box plot |
| `chart5_internet_churn.png` | Churn by internet service |
| `chart6_payment_churn.png` | Churn by payment method |
| `README.md` | Project documentation |

---

## 🗄️ Dataset Info

- **Source:** Kaggle — Telco Customer Churn
- **Records:** 7,032 customers
- **Columns:** 21 features including tenure, contract type, monthly charges, internet service, payment method

---

## 👤 Author

**Himanshu Chavhan** — Data Analyst
www.linkedin.com/in/himanshu-chavhan-b7a80123b
