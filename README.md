# TITANIC-ML-Exploratory-Data-Analysis-using-Python-libraries
Exploratory Data Analysis of the Titanic dataset using Python (Pandas, Seaborn, Matplotlib). Includes data overview, missing value detection, visualizations (pairplots, heatmaps, histograms, boxplots, scatterplots), and key insights on survival patterns by gender, class, age, and fare.

Here’s a concise **README summary** you can post on GitHub for your Titanic EDA project:

---

## 📊 Titanic Dataset – Exploratory Data Analysis

This project performs a complete exploratory data analysis (EDA) on the Titanic dataset (`train.csv`) using Python (Pandas, Seaborn, Matplotlib).

### **Key Steps**

* Data overview using `.info()`, `.describe()`, `.value_counts()`
* Missing value identification
* Pairplots & correlation heatmaps for relationship analysis
* Histograms & boxplots for distribution and outlier detection
* Scatterplots to study variable interactions
* Observations documented for each visual

### **Main Findings**

1. Dataset has **891 rows, 12 columns**, with missing values in `Age` (177), `Cabin` (687), and `Embarked` (2).
2. Majority of passengers were **male (577/891)**.
3. Higher survival rates among **females**, **first-class passengers**, and those paying higher fares.
4. **Age** concentrated between 20–40 years; **Fare** is right-skewed with extreme outliers.
5. **Pclass** is strongly related to both fare and survival.
6. Large `Cabin` data gap suggests many passengers traveled in shared/lower-class accommodations.

