# Credit Risk Analysis

**Project type:** Notebook-based credit risk analysis and modeling.

---

## Project Overview

This project focuses on credit risk analysis using Python, combining data preprocessing, exploratory data analysis (EDA), and visualization to gain insights into patterns that influence loan approval and risk classification. It leverages pandas for efficient data manipulation and matplotlib for clear, data-driven visualizations.

The workflow includes:

Importing and cleaning raw credit risk data from Excel.

Performing descriptive statistics and detecting missing or inconsistent values.

Visualizing key financial and demographic variables related to creditworthiness.

Identifying correlations and risk factors that help evaluate borrower reliability.

This repository provides a structured, reproducible notebook suitable for data analytics, financial modeling, and credit scoring insights using open-source Python tools.

---

## Dataset overview

- Source file: `Credit_Risk_Dataset.xlsx`
- Size: 32581 rows, 29 columns
- Detected target column (best guess): `loan_status`
- Columns (sample): client_ID, person_age, person_income, person_home_ownership, person_emp_length, loan_intent, loan_grade, loan_amnt, loan_int_rate, loan_status, loan_percent_income, cb_person_default_on_file, cb_person_cred_hist_length, gender, marital_status, education_level, country, state, city, city_latitude, ...
- Numeric columns count: 17, Categorical/other columns count: 12
- Missing values total: 4011

---

## Notebook analysis (`Credit_Risk.ipynb`)

- Preprocessing steps detected in code: fillna
- Models detected in code: None detected explicitly
- Evaluation metrics/validation detected: None detected explicitly

---

## Methodology (summary)

The notebook performs exploratory data analysis, data preprocessing, feature engineering (as present in the code), model training using one or more supervised classifiers, and evaluation using standard metrics and validation techniques (as present in the code).

---

## Notebook outputs (excerpt)

- Loaded dataset with 32581 rows and 29 columns.
- client_ID  person_age  person_income person_home_ownership  \
- 0  CUST_00001          22          59000                  RENT
- 1  CUST_00002          21           9600                   OWN
- 2  CUST_00003          25           9600              MORTGAGE
- 3  CUST_00004          23          65500                  RENT
- 4  CUST_00005          24          54400                  RENT
- person_emp_length loan_intent loan_grade  loan_amnt  loan_int_rate  \
- 0             123.00    PERSONAL          D      35000          16.02
- 1               5.00   EDUCATION          B       1000          11.14

---

## Files in repository

- `Credit_Risk.ipynb` — Jupyter notebook with analysis and model code.
- `Credit_Risk_Dataset.xlsx` — dataset used by the notebook.

---

## Data schema (columns)

client_ID, person_age, person_income, person_home_ownership, person_emp_length, loan_intent, loan_grade, loan_amnt, loan_int_rate, loan_status, loan_percent_income, cb_person_default_on_file, cb_person_cred_hist_length, gender, marital_status, education_level, country, state, city, city_latitude, city_longitude, employment_type, loan_term_months, loan_to_income_ratio, other_debt, debt_to_income_ratio, open_accounts, credit_utilization_ratio, past_delinquencies

---

## 🧾 Author

**Muhammad Asad**

---

## 🪪 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.
