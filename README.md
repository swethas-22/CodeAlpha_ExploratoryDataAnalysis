# CodeAlpha_ExploratoryDataAnalysis

## 📌 Overview
This repository contains **Task 2: Exploratory Data Analysis (EDA)** completed as part of the **CodeAlpha Data Analytics Internship**. The project explores the Titanic dataset to understand its structure, handle missing data, and uncover survival trends.

## 🛠️ Tools & Libraries
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook

## 🔍 Workflow & Steps
1. **Data Exploration:** Inspected dataset dimensions, column data types, and summary statistics.
2. **Data Cleaning:** Imputed missing `age` values with the median, dropped the `deck` column due to excessive missing values, and removed duplicate rows.
3. **Statistical Analysis & Visualization:** Analyzed survival rates across gender and passenger class, and identified ticket fare outliers using countplots and boxplots.

## 📊 Key Insights
* **Gender Impact:** Females had a significantly higher survival rate (~74%) compared to males (~19%).
* **Class Disparity:** 1st-class passengers had the highest survival rate (~63%), whereas 3rd-class passengers had the lowest (~24%).
* **Anomalies:** Detected high-fare outliers primarily in the 1st-class category.
