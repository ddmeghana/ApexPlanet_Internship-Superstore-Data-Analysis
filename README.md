# 📊 Data Immersion & Wrangling – Superstore Sales Dataset

## 📌 Internship Task 1 – Data Analytics

This repository contains the work completed for **Task 1: Data Immersion & Wrangling** as part of my Data Analytics Internship.

---

## 📁 Dataset Used

* **Superstore Sales Dataset (Kaggle)**
* The dataset contains transactional sales data including customer details, product categories, sales, profit, and regional information.

---

## 🎯 Objective

The objective of this task is to:

* Understand the dataset structure
* Identify data quality issues
* Clean and transform the data
* Prepare an analysis-ready dataset

---

## 🛠️ Tools & Technologies

* Python 
* Pandas
* NumPy
* Jupyter Notebook (VS Code)

---

## 🔍 Steps Performed

### 1. Data Access & Familiarization

* Loaded dataset using Pandas
* Explored dataset structure using `.head()`, `.info()`, `.describe()`
* Understood each column and created a **Data Dictionary**

---

### 2. Data Quality Assessment

Identified the following issues:

* Missing values in certain columns
* Duplicate records
* Incorrect data types (Date columns stored as strings)
* Inconsistent column naming (spaces in column names)

---

### 3. Data Cleaning & Transformation

Performed the following operations:

* Converted date columns to datetime format
* Removed duplicate rows
* Handled missing values
* Standardized column names (removed spaces, used underscores)
* Created new features:

  * `Year`
  * `Month`
  * `Profit_Margin`

---

### 4. Final Output

* Generated a cleaned dataset ready for analysis
* Saved as: `cleaned_superstore.csv`

---

## 📊 Key Learnings

* Importance of data cleaning before analysis
* Handling missing values and duplicates
* Data type conversions
* Feature engineering for better insights

---


## 🙌 Acknowledgment

This task is part of my internship at **ApexPlanet**, helping me build foundational skills in data analytics.

---
