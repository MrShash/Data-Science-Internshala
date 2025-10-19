# 📊 Data Science Training - Internshala (6 Weeks)

This repository contains all course notebooks, datasets, quizzes, and the **final capstone project** completed as part of the **6 Weeks Data Science Training by Internshala Trainings**.  
The program provided a hands-on introduction to **Python**, **statistics**, **data preprocessing & visualization**, and **machine learning** using **Jupyter Notebook**.

---

## 🧠 Course Overview

- **Duration:** 6 Weeks (May 4, 2020 – June 15, 2020)  
- **Issuer:** Internshala Trainings  
- **Score:** 87%  
- **Environment:** Jupyter Notebook  
- **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

---

## 📚 Topics Covered

### 1) Python Basics
Core Python syntax and data types, loops & conditionals, lists, dictionaries, reading CSV/Excel files with Pandas, DataFrames & indexing, and coding challenges.

**Key notebooks:**
- `1 Python Basics.ipynb`
- `2 Python for DataScience.ipynb`
- `3 loop.ipynb`
- `4 List.ipynb`
- `5 Dictionaries.ipynb`
- `6 Read csv and excel file in PANDAS.ipynb`
- `7 DataFrame and Indexing.ipynb`
- `Python_Coding_Challenge.ipynb`
- `Python_Coding_Challenge_Solution.ipynb`

---

### 2) Understanding the Statistics for Data Science
Covers descriptive statistics (mean, median, mode, variance, SD), frequency & histogram plots, hypothesis testing (one-sample, two-sample, paired t-tests), correlation, and chi-square tests.

**Key notebooks:**
- `1 Mode.ipynb`
- `2 Mean.ipynb`
- `3 Median.ipynb`
- `4 Spread of Data.ipynb`
- `5 Variance.ipynb`
- `6 Standard Deviation.ipynb`
- `7 Frequency table.ipynb`
- `8 Histogram.ipynb`
- `9 T-test( one sample ).ipynb`
- `10 2 sample T-test.ipynb`
- `11 Paired T-test.ipynb`
- `12 Chi square.ipynb`
- `13 Correlation.ipynb`

---

### 3) Predictive Modeling & Machine Learning
Explores data ingestion, variable identification, univariate/bivariate analysis, treating missing values & outliers, transforming variables, and implementing ML models like regression, decision trees, and clustering.

**Submodules & Key notebooks:**

#### 🔹 Data Preparation & Exploration
- `1 Reading the data into Python.ipynb`
- `2 Variable Identification.ipynb`
- `3 Univariate Analysis for Continuous Variables.ipynb`
- `4 Univariate analysis for Categorical Variables.ipynb`
- `5 Bivariate Analysis.ipynb`
- `6 Treating missing values.ipynb`
- `7 outliers treatment.ipynb`
- `8 Transforming variables test.ipynb`

#### 🔹 Linear Regression
- `Implemented BySelf.ipynb`
- `train.csv`

#### 🔹 Logistic Regression
- `logistic Regression.ipynb`
- `How to decide the threshold.odt`

#### 🔹 Decision Tree
- `Decision Tree.ipynb`
- `Decision tree simplified.odt`

#### 🔹 K-Means Clustering
- `K-Means.ipynb`
- `Final+Test+Data+Set.csv`

---

## 🚀 Final Project — Predicting Term Deposit Subscription (Retail Bank)

**Goal:** Build a binary classification model to predict whether a customer will subscribe to a **term deposit** using demographic and campaign data (`train.csv`, `test.csv`).

**Approach (High Level):**
1. Data loading and exploratory analysis  
2. Data cleaning, encoding categorical variables, and scaling  
3. Model training — Logistic Regression & Decision Tree  
4. Model evaluation (Accuracy, Precision, Recall, Confusion Matrix)  
5. Feature importance & business insights (e.g., contact duration, campaign frequency, previous outcomes)

**Project Artifacts:**
- `Benchmark solution.ipynb`
- `Problem Statement.pdf`
- `solution_checker.xlsx`
- `submission.csv`
- `train.csv`, `test.csv`

👉 **GitHub Repository:** [ShaswatManoj/Data-Science-Internshala](https://github.com/MrShash/Data-Science-Internshala)

---

## 📁 Folder Structure

```text
│   README.md
│
├───1. Python Basics
│       1 Python Basics.ipynb
│       2 Python for DataScience.ipynb
│       3 loop.ipynb
│       4 List.ipynb
│       5 Dictionaries.ipynb
│       6 Read csv and excel file in PANDAS.ipynb
│       7 DataFrame and Indexing.ipynb
│       data.csv
│       data.xlsx
│       data1.csv
│       data_python.csv
│       Module Test 1.csv
│       Python_Coding_Challenge.ipynb
│       Python_Coding_Challenge_Solution.ipynb
│
├───2. Understanding the Statistics for Data Science
│       1 Mode.ipynb
│       10 2 sample T-test.ipynb
│       11 Paired T-test.ipynb
│       12 Chi square.ipynb
│       13 Correlation.ipynb
│       2 Mean.ipynb
│       3 Median.ipynb
│       4 Spread of Data.ipynb
│       5 Variance.ipynb
│       6 Standard Deviation.ipynb
│       7 Frequency table.ipynb
│       8 Histogram.ipynb
│       9 T-test( one sample ).ipynb
│       chi_square.csv
│       correlation.csv
│       Data for 2 sample test.csv
│       Data for paired t test.csv
│       Data for paired t test.xlsx
│       Frequency Table.csv
│       Histogram.csv
│       mean.csv
│       mean_robust.csv
│       Median.csv
│       mode.csv
│       onesample.csv
│       Spread of Data.csv
│       Standard Deviation.csv
│       variance.csv
│
├───3. Predictive modeling and ML
│   │   1 Reading the data into Python.ipynb
│   │   2 Variable Identification.ipynb
│   │   3 Univariate Analysis for Continuous Variables.ipynb
│   │   4 Univariate analysis for Categorical Variables.ipynb
│   │   5 Bivariate Analysis.ipynb
│   │   6 Transforming variables test.ipynb
│   │   6 Treating missing values.ipynb
│   │   7 outliers treatment.ipynb
│   │   8 Transforming variables test.ipynb
│   │   data.csv
│   │   data1.csv
│   │   data2.csv
│   │   titanic.csv
│   │   train.csv
│   │   train1.csv
│   │
│   ├───1. Linear Regression
│   │       Implemented BySelf.ipynb
│   │       train.csv
│   │
│   ├───2. Logistic Regression
│   │       How to decide the threshold .odt
│   │       logistic Regression.ipynb
│   │       titanic.csv
│   │
│   ├───3. Decision Tree
│   │       data_cleaned.csv
│   │       Decision tree simplified.odt
│   │       Decision Tree.ipynb
│   │
│   └───4. K means
│           Final+Test+Data+Set.csv
│           K-Means.ipynb
│           student_evaluation.csv
│
└───Final Project
        Benchmark solution.ipynb
        Problem Statement.pdf
        solution_checker.xlsx
        submission.csv
        test.csv
        train.csv
