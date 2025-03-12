# **Data Quality Assurance in Healthcare Analytics**

## 📌 Overview
This project focuses on **data quality assessment, cleaning, and exploratory data analysis (EDA) in healthcare analytics**. Poor data quality can lead to incorrect insights and decisions, especially in the healthcare industry, where accuracy is critical. The project compares two datasets—**a clean version (A) and a corrupted version (B)**—to demonstrate common data quality issues and their solutions.

## 🛠 Key Objectives
- ✅ Perform **data quality checks** to identify missing values, duplicates, inconsistent formatting, and invalid values.  
- ✅ Implement **data cleaning techniques** to improve completeness, uniqueness, and validity.  
- ✅ Generate **data quality scores** before and after cleaning to measure improvements.  
- ✅ Conduct **exploratory data analysis (EDA)** to uncover insights related to patient demographics, smoking status, marital status, work type, and residence type.  
- ✅ Ensure **data integrity and reliability** for meaningful healthcare analytics.  

## 🗂 Dataset
- The project uses a **stroke prediction dataset** from a public source.  
- **Dataset A**: Original clean dataset.  
- **Dataset B**: Modified dataset with intentional errors (duplicates, missing values, inconsistent formats, and invalid values).  

## 📝 Data Quality Assessment Metrics
The project evaluates data quality based on the following key metrics:  

| **Metric**            | **Description**  |
|----------------------|----------------|
| **Data Size**       | Total records and attributes |
| **Missing Values**  | Percentage of missing data |
| **Duplicates**      | Number of duplicate records |
| **Completeness**    | How much of the data is available |
| **Uniqueness**      | Identifying duplicate values |
| **Validity**        | Ensuring correct and logical values |
| **Overall Data Quality Score** | Aggregated score based on completeness, uniqueness, and validity |

## 📊 Techniques Used
- 🔍 **Data Inspection** – Checking data types, missing values, duplicates, and anomalies.  
- 🛠 **Data Cleaning** – Handling missing values, removing duplicates, fixing incorrect formatting.  
- 📈 **Data Quality Score Calculation** – Measuring improvements before and after cleaning.  
- 📊 **Exploratory Data Analysis (EDA)** – Visualizing key relationships in healthcare data.  

---

## 📊 **Exploratory Data Analysis (EDA)**
### 🔎 **Key Findings from EDA**
After data cleaning, we performed **EDA to extract meaningful insights** from the dataset. Below are some of the key observations:

### 📌 **1. Age Distribution and Stroke Risk**
- The **majority of patients are aged between 45-75 years**.
- **Stroke prevalence increases significantly** in older age groups, with a sharp rise after age 50.
- There are very few cases of stroke among individuals under 40.

### 📌 **2. Gender vs. Stroke Incidence**
- Stroke cases are slightly **higher in males than females**, though the difference is not significant.
- The ratio of stroke occurrences remains fairly **consistent across genders**.

### 📌 **3. Smoking Status and Stroke Correlation**
- **Current smokers have a noticeably higher risk of stroke** compared to non-smokers.
- **Former smokers also show a slightly elevated stroke risk**, indicating long-term effects of smoking.
- **Non-smokers had the lowest stroke occurrence rates**, reinforcing the negative impact of smoking.

### 📌 **4. Work Type and Stroke Risk**
- The highest number of stroke cases were observed in individuals with **private sector jobs**.
- **Self-employed individuals also showed a relatively high stroke rate**.
- Those categorized as **children and unemployed had the lowest risk**, possibly due to lifestyle factors.

### 📌 **5. Marital Status and Stroke Risk**
- **Married individuals had a higher stroke rate** than single or never-married individuals.
- This could be due to **age factors**, as older individuals are more likely to be married.
- The impact of marital status itself needs further study to separate it from age influences.

### 📌 **6. Residence Type and Stroke Risk**
- No significant difference was found between **rural and urban residents**.
- This suggests that **lifestyle factors may play a larger role** than geographical location in stroke risk.

### 📌 **7. Hypertension & Heart Disease Correlation with Stroke**
- Patients with **hypertension and heart disease** had a significantly **higher stroke risk**.
- Almost **50% of stroke cases had a history of hypertension**, making it a major risk factor.
- Individuals with **both heart disease and hypertension** were at the highest risk.

### 📌 **8. Glucose Levels and BMI Impact**
- Higher **average glucose levels** were observed in stroke patients, indicating a possible link between **diabetes and stroke**.
- Patients with **high BMI (obesity)** also had an increased stroke risk, highlighting the importance of **weight management in stroke prevention**.

---

## 📌 **Key Takeaways from EDA**
✔ **Age, smoking status, and hypertension are the most influential factors** in predicting stroke risk.  
✔ **Individuals with heart disease and high glucose levels require closer monitoring**, as they fall in high-risk categories.  
✔ **Lifestyle choices such as smoking and obesity** play a significant role in increasing stroke risk.  
✔ **Urban vs. rural residence has minimal impact**, suggesting that healthcare interventions should be universal.  
