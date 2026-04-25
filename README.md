# HR Employee Attrition – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the **HR Employee Attrition dataset** to understand the key factors that influence employee turnover in an organization.

The dataset contains **35 features** related to employee demographics, job role, salary, experience, and work environment.

---

## 🎯 Objective

The main goal of this project is to identify **why employees leave the company** and uncover patterns that can help improve employee retention.

---

## ❓ Business Questions

This analysis focuses on answering the following questions:

1. What is the overall attrition rate in the company?
2. How do age and distance from home affect employee attrition?
3. Does monthly income (salary) impact employee attrition?
4. How do overtime and business travel affect employee turnover?

---

## 📂 Dataset Information

* Source: HR Employee Attrition Dataset
* Features: 35 columns
* Target Variable: `Attrition` (Yes / No)

---

## ⚙️ Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🧹 Data Cleaning Steps

* Checked and handled missing values
* Removed duplicate records
* Dropped irrelevant columns (e.g., EmployeeNumber, StandardHours)
* Handled outliers using the IQR method (clipping)
* Checked and treated skewness using log transformation

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Univariate Analysis

* Attrition distribution analysis
* Age distribution
* Gender distribution
* Overtime patterns

### 2. Bivariate Analysis

* Age vs Attrition
* Monthly Income vs Attrition
* Overtime vs Attrition
* Business Travel vs Attrition

### 3. Multivariate Analysis

* Age vs Monthly Income (with Attrition & Experience)

---

## 🔥 Key Insights

### 📌 1. Overtime increases attrition

Employees working overtime are more likely to leave due to burnout and poor work-life balance.

### 📌 2. Low salary leads to higher attrition

Employees with lower monthly income tend to leave the company more frequently.

### 📌 3. Young employees are more likely to leave

Employees aged 25–32 and those in early career stages show higher turnover.

### 📌 4. Frequent business travel impacts retention

Employees who travel frequently show higher attrition compared to others.

---

## 📈 Correlation Findings

* Age and Total Working Years are strongly correlated
* Monthly Income increases with experience
* Distance from Home has weak correlation with attrition

---

## 💡 Recommendations

### 1. Control Overtime

* Reduce excessive overtime
* Hire additional staff if workload is high

### 2. Improve Salary Structure

* Review salaries for entry and mid-level employees
* Offer bonuses and performance-based incentives

### 3. Improve Early Employee Retention

* Introduce mentorship programs
* Provide clear career growth paths

---

## 🏁 Conclusion

Employee attrition is mainly influenced by **salary, workload, age, and early career experience**. By addressing these factors, companies can significantly improve employee retention and satisfaction.

---

## 🚀 Future Improvements

* Apply machine learning models to predict attrition
* Build a dashboard for HR insights
* Perform role-wise deeper analysis

---

## 👩‍💻 Author

Ayesha Tabassum

---

⭐ If you like this project, feel free to star the repository!
