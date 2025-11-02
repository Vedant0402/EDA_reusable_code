# EDA-reusable_code

#### Just a practice repo for EDA.
#### Writing some code everyday for learning and practicing EDA techniques.


#### Goal -->

#### 1. Perform end-to-end EDA on any dataset.
#### 2. Handle missing data, outliers, skewness, correlations, and feature relationships.
#### 3. Visualize and interpret statistical + business insights with precision.
#### 4. Write clean, professional, and reusable EDA notebooks.

# 10 Days of EDA Mastery Bootcamp (Python + Seaborn)

Welcome to my **10-Day EDA Mastery Bootcamp** — a hands-on journey to mastering **Exploratory Data Analysis (EDA)** using Python, Pandas, NumPy, Matplotlib, and Seaborn.

Over 10 days, I practiced data profiling, visualization, correlation analysis, feature engineering, and automated report generation — building strong analytical intuition step by step.

---

## 📚 Table of Contents
- [Overview](#overview)
- [Environment Setup](#environment-setup)
- [Daily Learning Breakdown](#daily-learning-breakdown)
  - [Day 1 – EDA Foundations & Setup](#day-1--eda-foundations--setup)
  - [Day 2 – Data Profiling & Summary Statistics](#day-2--data-profiling--summary-statistics)
  - [Day 3 – Missing Value Detection & Imputation](#day-3--missing-value-detection--imputation)
  - [Day 4 – Outlier Detection & Treatment](#day-4--outlier-detection--treatment)
  - [Day 5 – Univariate Analysis](#day-5--univariate-analysis)
  - [Day 6 – Bivariate Analysis](#day-6--bivariate-analysis)
  - [Day 7 – Multivariate & Advanced Visualizations](#day-7--multivariate--advanced-visualizations)
  - [Day 8 – Feature Engineering within EDA](#day-8--feature-engineering-within-eda)
  - [Day 9 – Automated EDA Reports & Insights](#day-9--automated-eda-reports--insights)
  - [Day 10 – Final Case Study (Capstone)](#day-10--final-case-study-capstone)
- [Tools & Libraries](#tools--libraries)
- [Key Takeaways](#key-takeaways)
- [Author](#author)

---

## 🧾 Overview

Exploratory Data Analysis (EDA) is the **foundation of every data science project**.  
The goal of this bootcamp was to:
- Understand dataset structures
- Detect and treat missing values & outliers
- Visualize data relationships
- Engineer new meaningful features
- Summarize insights and generate auto-EDA reports

Each day built upon the previous one, making the learning experience progressive, hands-on, and real-world ready.

---

## ⚙️ Environment Setup


pip install pandas numpy seaborn matplotlib plotly ydata-profiling sweetviz missingno scikit-learn

---

Day 1 – EDA Foundations & Setup

Dataset: tips

Learned EDA workflow (load → inspect → summarize → visualize)

Checked dataset structure, shape, datatypes, missing values

Built a reusable EDA template for all future days

Tools: info(), describe(), pairplot, and quick summary functions



Day 2 – Data Profiling & Summary Statistics

Dataset: tips

Explored data types, counts, and distributions

Created a summary DataFrame including skewness & kurtosis

Built a custom profiling function

Learned to handle numeric vs categorical summaries



Day 3 – Missing Value Detection & Imputation

Dataset: titanic

Detected missingness via isnull() and missingno visualizations

Learned types: MCAR, MAR, MNAR

Performed:

Mean/Median/Mode imputation

Group-wise imputation

KNN Imputer for advanced handling

Verified results visually & statistically



Day 4 – Outlier Detection & Treatment

Dataset: titanic

Learned IQR method and Z-score method for outliers

Visualized with boxplots

Applied:

Outlier removal

Winsorization (capping)

Log transformations

Compared data before and after treatment



Day 5 – Univariate Analysis

Dataset: iris

Explored individual features using:

Histograms

KDE plots

Boxplots

Violin plots

Learned skewness & kurtosis interpretation

Analyzed categorical distributions (countplots & pie charts)



Day 6 – Bivariate Analysis

Dataset: penguins

Analyzed relationships between:

Numeric–numeric → scatterplots, correlation

Categorical–numeric → boxplots, violinplots

Categorical–categorical → crosstabs, countplots

Performed Pearson correlation and Chi-square tests



Day 7 – Multivariate & Advanced Visualizations

Dataset: flights + iris

Created multi-variable plots:

Heatmaps

FacetGrid (subplots by category)

PairGrid (custom pairwise visuals)

Jointplot (scatter + density)

Built interactive plots using Plotly

Derived seasonality & trend insights



Day 8 – Feature Engineering within EDA

Dataset: mpg

Created new features (power_to_weight, car_age, engine_size_category)

Applied:

Label encoding & one-hot encoding

Standard scaling & log transformations

Rare category grouping

Analyzed correlation changes after transformations



Day 9 – Automated EDA Reports & Insights

Dataset: titanic

Used:

ydata-profiling for HTML-based full EDA reports

Generated Titanic_EDA_Report.html & Titanic_Sweetviz_Report.html

Wrote business insights tables and summaries for stakeholders



Day 10 – Final Case Study (Capstone)

Dataset: Custom (EV dataset / HR dataset / Kaggle dataset)

Tasks:

Perform end-to-end EDA

Handle missing values, outliers, and feature engineering

Create automated EDA reports

Write professional insight summaries


Deliverables:

Final_EDA_CaseStudy.ipynb

Auto_EDA_Report.html

Insights_Report.pdf


Outcome:

A portfolio-ready EDA project demonstrating complete real-world data analysis workflow.
