# 📊 Loan Limit Optimization Case Study

## 🚀 Overview

This project focuses on optimizing loan limit increase strategies to maximize profitability while minimizing default risk. It combines data analysis, machine learning, simulation, and financial modeling to build a practical decision-making framework.

---

## 🎯 Objective

* Maximize expected profit from loan limit increases
* Control and minimize default risk
* Model customer behavior using data-driven techniques
* Simulate outcomes under uncertainty

---

## 📂 Dataset

The dataset contains customer-level loan information:

* Customer ID
* Initial Loan Amount ($)
* Days Since Last Loan
* On-time Payments (%)
* Number of Increases (2023)
* Total Profit Contribution ($)

---

## ⚙️ Approach

### 1. Data Analysis & EDA

* Distribution of loan amounts and repayment behavior
* Relationship between payment discipline and profitability

### 2. Feature Engineering

* Risk Score based on payment history and recency
* Risk Categorization (Low / Medium / High)
* Default Probability estimation

### 3. Machine Learning

* Random Forest model to identify high-profit customers
* Classification based approach for decision support

### 4. Risk & Transition Analysis

* Risk segmentation to approximate customer state transitions
* Behavioral insights from repayment patterns

### 5. Optimization Strategy

* Expected profit calculation per customer
* Rule-based decision logic for loan limit increase

### 6. Simulation

* Monte Carlo simulation to estimate profit variability

### 7. Financial Modeling

* Net Present Value (NPV) using 19% discount rate

---

## 📈 Key Insights

* Higher on-time payment % leads to lower default risk
* Risk score is a strong indicator of profitability
* Controlled credit increases improve overall returns
* Simulation shows stable profit under optimized strategy

---

## 🧪 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook

---

## 💡 Future Enhancements

* Linear Programming for constraint optimization
* Reinforcement Learning for dynamic decision-making
* Advanced Markov Chain modeling
* Integration of macroeconomic factors

---

## 📌 Conclusion

This project demonstrates how machine learning, simulation, and financial logic can be combined to solve a real-world lending optimization problem effectively.

---
