# 🧠 Customer Churn Analysis — Portfolio Project

This project focuses on analyzing customer churn behavior to identify key factors that drive customers to discontinue their subscriptions.  
It highlights important retention insights and demonstrates practical data analysis and visualization skills — a crucial part of any Data Science portfolio.

---

## 📌 Objective

To explore customer churn data, understand behavioral patterns, and identify actionable strategies that can help reduce churn and improve customer retention.

---

## 🧰 Tools & Libraries Used

| Category | Tools |
|-----------|-------|
| Data Handling | **Python**, **Pandas**, **NumPy** |
| Visualization | **Matplotlib**, **Seaborn** |
| Environment | **Jupyter Notebook** |

---

## 🗂️ Dataset Overview

The dataset contains customer demographics, subscription details, and service usage information.  
The key target variable is **`Churn`**, indicating whether a customer left (Yes) or stayed (No).

**Key Columns:**
- `customerID` – Unique customer identifier  
- `gender`, `SeniorCitizen`, `Partner`, `Dependents` – Demographics  
- `tenure`, `Contract`, `PaymentMethod` – Account details  
- `MonthlyCharges`, `TotalCharges` – Billing metrics  
- `Churn` – Target variable (Yes/No)

---

## 📊 Exploratory Data Analysis (EDA)

### 1️⃣ Churn Rate by Contract Type
Shows how churn rate varies based on the type of customer contract.


<img width="1800" height="1200" alt="churn_rate" src="https://github.com/user-attachments/assets/f0c6a5ad-1781-4235-b2af-c8546cb6dae8" />


### 2️⃣ Percentage of Churned Customers

<img width="1200" height="1200" alt="Percentage_pf_churned" src="https://github.com/user-attachments/assets/3611fe83-df70-4171-a481-daf6b05cdcdf" />

---

### 3️⃣ Churn by Senior Citizen (Stacked Bar Chart)
Compares churn rates between senior and non-senior customers.

<img width="1800" height="1200" alt="Churn_by_seniorcitizen" src="https://github.com/user-attachments/assets/0fbd2a42-87c1-4c56-a29c-f5aa11600207" />

---

### 4️⃣ Churn on the Basis of Tenure
Shows how customer tenure (length of relationship) impacts churn probability.


<img width="3000" height="1200" alt="churn_by_tenur" src="https://github.com/user-attachments/assets/21bd890d-fd8b-49be-bb3c-a360eaa06af1" />

---

## 🔍 Key Insights

- **Contract type** has a major impact — month-to-month customers churn far more than others.  
- **Overall churn rate** shows moderate attrition; retention strategies are needed for short-term users.  
- **Senior citizens** show slightly higher churn than younger customers.  
- **Longer tenure** strongly reduces churn likelihood — loyalty improves with time.

---

## 🧾 Conclusion

Customer churn is mainly influenced by **contract type**, **tenure**, and **age group**.  
To minimize churn, businesses should:
- Promote **long-term contract options** with incentives.  
- Offer **special retention programs** for senior customers.  
- Focus on improving early customer experience to increase tenure.

This project demonstrates data-driven customer insights and visualization storytelling — essential for decision-making and predictive modeling.

---

## 📁 Project Structure




