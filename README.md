# Healthcare Insurance Charges — Exploratory Data Analysis

## 📌 Project Overview

This project performs exploratory data analysis (EDA) on a healthcare insurance dataset to understand how demographic and lifestyle-related factors are associated with medical insurance charges.

The analysis focuses on identifying patterns in insurance charges across **age, BMI, smoking status, sex, number of children, and region** using Python, Pandas, Matplotlib, and Seaborn.

## 🎯 Objectives

- Inspect and clean the dataset
- Check for missing values and duplicate records
- Understand distributions of numerical variables
- Compare insurance charges across different demographic groups
- Analyze relationships between numerical variables and charges
- Investigate whether patterns differ across smoker/non-smoker groups
- Identify key findings and limitations from the analysis

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** — data cleaning, grouping, aggregation and analysis
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualizations
- **Jupyter Notebook / VS Code**

## 🔍 Analysis Performed

### 1. Data Cleaning & Validation
- Inspected dataset structure and data types
- Checked for missing values
- Identified and removed duplicate records
- Reviewed descriptive statistics

### 2. Distribution Analysis
Analyzed the distributions of:
- Age
- BMI
- Number of children
- Insurance charges

Skewness was also examined, particularly because insurance charges contain high-value observations.

### 3. Group Analysis
Compared insurance charges across:
- Smoker vs. non-smoker
- Male vs. female
- Different regions

Both **mean and median charges** were considered to better understand the effect of skewed values.

### 4. Correlation Analysis
Examined relationships between:
- Age and charges
- BMI and charges
- Number of children and charges

A correlation heatmap was used to visualize relationships between numerical variables.

### 5. Subgroup Analysis
Further analysis was performed by:
- Comparing age and charges by smoking status
- Comparing BMI and charges by smoking status
- Categorizing BMI into four groups
- Comparing BMI categories across smoker/non-smoker groups
- Checking whether the higher-charge pattern among smokers remained consistent across regions and sex

## 📊 Key Findings

- Insurance charges were substantially higher among smokers than non-smokers in this dataset.
- The smoker group showed higher median charges across each region and both sex categories.
- Age showed a positive relationship with insurance charges.
- The relationship between BMI and charges was stronger among smokers than non-smokers.
- Median charges for males and females were relatively similar.
- Regional differences in average charges were comparatively smaller than the difference observed between smoker and non-smoker groups.
- Insurance charges were right-skewed, making median values useful when comparing groups.

## ⚠️ Limitations

- The analysis identifies **associations, not causal relationships**.
- The dataset does not contain detailed medical history, diagnoses, healthcare utilization, or other factors that may influence insurance charges.
- Insurance charges are skewed, so mean values can be influenced by extreme observations.
- Correlation measures linear relationships and does not establish causation.

## 🚀 Possible Next Step

A potential next step would be to build a regression model to predict insurance charges and evaluate which features contribute most to prediction performance.

## 📁 Project Structure

```text
Healthcare-Insurance-EDA/
│
├── insurance.csv
├── healthcare_insurance_eda.py
└── README.md
```

