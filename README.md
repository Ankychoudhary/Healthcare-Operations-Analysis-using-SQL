# 🏥 Healthcare Data Analysis using SQL (Multi-Table Project)

## 📌 Project Overview

This project analyzes a multi-table healthcare dataset using SQL within a Python (Google Colab) environment. It simulates real-world relational data analysis by combining patient, doctor, appointment, treatment, and billing data.

The objective is to uncover meaningful insights related to patient behavior, treatment trends, doctor workload, and revenue patterns.

---

## 🛠️ Tools & Technologies

* SQL (SQLite)
* Python (Pandas, Matplotlib)
* Google Colab

---

## 📂 Dataset Description

The dataset includes the following tables:

* **patients** – Patient demographics
* **doctors** – Doctor details
* **appointments** – Appointment records
* **treatments** – Treatment types, costs, and dates
* **billing** – Billing and payment information

---

## 🔍 SQL Concepts Used

* SELECT, WHERE, GROUP BY, ORDER BY
* INNER JOIN (multi-table queries)
* Aggregate Functions (COUNT, AVG, SUM)
* Subqueries
* Window Functions (RANK)
* CASE Statements

---

## 📊 Key Analysis Performed

### 🔹 Patient & Appointment Analysis

* Total patients: **50**
* Total appointments: **200**

### 🔹 Doctor Performance Analysis

* Top doctor by appointments: **Sarah Taylor (29 appointments)**

### 🔹 Treatment Analysis

* Most common treatment: **Chemotherapy (49 cases)**
* Other frequent treatments: X-Ray, ECG, Physiotherapy, MRI

### 🔹 Billing Analysis

* Highest billing patient generated over **30,000+ total revenue**
* Significant variation observed in billing amounts across patients

---

## 📈 Visualizations

* Bar chart of most common treatments
* Average cost per treatment
* Doctor-wise appointment distribution

---

## 🧠 Key Insights

* **Chemotherapy** is the most frequently performed treatment, indicating high demand
* A small group of patients contributes disproportionately to total revenue
* **Sarah Taylor** handles the highest number of appointments, indicating workload imbalance
* Treatment costs vary significantly, with some procedures being much more expensive than others
* High billing values suggest the presence of premium or complex treatments

---

## 💡 Business Recommendations

* Allocate more resources to high-demand treatments like Chemotherapy
* Balance doctor workload to improve operational efficiency
* Optimize pricing strategies for high-cost treatments
* Focus on retaining high-value patients

---

## 📁 Project Structure

```
healthcare-sql-data-analysis/
│
├── data/
├── notebook.ipynb
├── sql_queries.sql
└── README.md
```

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload all dataset files (CSV)
3. Run all cells step-by-step
4. Execute SQL queries and view insights

---

## 📌 Conclusion

This project demonstrates practical SQL skills on a relational healthcare dataset, including joins, aggregations, and analytical queries. It highlights the ability to extract meaningful insights and support data-driven decision-making.

---

⭐ If you found this project useful, feel free to star the repository!
