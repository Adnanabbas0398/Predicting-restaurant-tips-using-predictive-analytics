# 📈 Predicting Restaurant Tips
### Predictive Analytics Case Study · Excel-Based Regression Model

---

## 📌 Project Overview

Restaurant tip amounts vary significantly based on factors like bill size, party size, day of week, and dining time. This project builds a **regression-based predictive model in Excel** to estimate tip amounts — demonstrating the full predictive analytics workflow from raw data to actionable business insight.

> **Role:** Data Analyst  
> **Tools:** Microsoft Excel  
> **Domain:** Hospitality · Predictive Analytics · Regression Modelling

---

## 🎯 Business Problem

Restaurant managers and owners often lack visibility into tipping patterns, making it difficult to:
- Understand which factors most influence tip amounts
- Set realistic revenue expectations from gratuities
- Identify opportunities to improve customer experience and increase tips

**Goal:** Build a predictive model that estimates tip amounts based on measurable variables, and surface insights that support data-driven operational decisions.

---

## 📂 Dataset

| Feature | Description |
|---|---|
| `total_bill` | Total bill amount ($) |
| `tip` | Tip amount ($) — **target variable** |
| `sex` | Gender of the bill payer |
| `smoker` | Whether the party included smokers |
| `day` | Day of the week |
| `time` | Lunch or Dinner |
| `size` | Party size |

---

## 🔍 My Approach

### 1. 🧹 Data Cleaning & Preparation
- Inspected the dataset for missing values, duplicates, and outliers
- Standardised formatting and ensured data type consistency across all columns
- Validated data integrity before modelling

### 2. 🔠 Categorical Encoding
- Identified categorical variables: `sex`, `smoker`, `day`, `time`
- Applied **binary and dummy encoding** to convert categories into numeric format suitable for regression
- Documented encoding decisions for reproducibility

### 3. 📊 Exploratory Data Analysis (EDA)
- Analysed distributions of tip amounts and total bill values
- Identified correlations between variables using Excel charts and pivot tables
- Key finding: `total_bill` and `size` showed the strongest relationship with tip amount

### 4. 🤖 Regression Model Building
- Defined **dependent variable:** `tip`
- Defined **independent variables:** `total_bill`, `size`, encoded categorical features
- Built a **multiple linear regression model** using Excel's Data Analysis ToolPak
- Interpreted coefficients to understand each variable's impact on tip amount

### 5. 📏 Model Evaluation
- Evaluated model performance using:
  - **RMSE (Root Mean Squared Error)** — measures average prediction error in dollar terms
  - **R² (R-Squared)** — measures how well the model explains tip variation
- Iterated on feature selection to improve model accuracy

### 6. 💡 Insights & Recommendations
- Translated model outputs into actionable business recommendations
- Presented findings in a clear, non-technical format suitable for restaurant management

---

## 📦 Key Findings

- 💰 **Total bill amount** is the strongest predictor of tip size — larger bills consistently generate higher tips
- 👥 **Party size** has a positive but weaker effect on tip amounts
- 🌙 **Dinner service** tends to generate slightly higher tips than lunch
- 📅 **Weekend dining** (Sat/Sun) correlates with higher average tips

---

## 🛠️ Tools & Technologies

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

**Techniques:** Data Cleaning · Categorical Encoding · Exploratory Data Analysis · Multiple Linear Regression · RMSE · R² Evaluation · Data Storytelling

---

## 📈 Results

| Metric | Value |
|---|---|
| Model Type | Multiple Linear Regression |
| Evaluation Metric | RMSE & R² |
| Key Predictor | Total Bill Amount |
| Tool | Microsoft Excel (Data Analysis ToolPak) |

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `README.md` | This file — full project case study |
| *(Excel workbook)* | Data cleaning, encoding, regression model, and results |

---

## 👤 Author

**Adnan Abbas** — Business Analyst & Data Analyst  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adnan-abbas-business-analyst/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Adnanabbas0398)
