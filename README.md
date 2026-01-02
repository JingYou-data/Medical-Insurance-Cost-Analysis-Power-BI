# 🏥 Medical Insurance Cost Strategic Intelligence
> **An end-to-end Data Analytics solution exploring behavioral and demographic drivers of medical expenses for 1,338 individuals using Power BI and DAX.**

---

## 🎥 Project Demo
* **[🚀 Live Interactive Dashboard](这里粘贴你的PowerBI分享链接)**
* **Video Walkthrough:** Found in `/Media/capstone_video.mp4`

---

## 🛠️ Data Engineering & Pipeline
Before visualization, I performed data profiling and extensive ETL to ensure data quality:

* **Data Scale:** Analyzed **1,338 records** across 7 key dimensions.
* **Cleaning Logic:**
    * Verified demographic features and identified behavioral patterns.
    * Ensured data integrity for medical charges billed.

---

## 🧮 Technical Implementation (DAX & Modeling)

### 1. Core Business Logic


Established explicit measures to ensure calculation accuracy and report performance. Utilized DAX to perform row-level precision for total and average cost metrics.

```dax
Total Charges = SUM ( insurance[charges] )

Average Charges = AVERAGE ( insurance[charges] )# Medical-Insurance-Cost-Analysis-Power-BI

❀ Project Objective

This project explores the factors that influence personal medical charges using behavioral and demographic data. The goal is to visualize and uncover patterns using Power BI, helping inform health insurance strategies and cost prediction.

 Tools Used

Power BI (Interactive Visualization & Dashboard)

Microsoft Excel (Initial Data Review)

Dataset Source: Kaggle (Medical Cost Personal Dataset)

Dataset Overview

Total records: 1,338

❀ Features:

age: Age of the individual

sex: Gender (male/female)

bmi: Body Mass Index

children: Number of dependents

smoker: Whether the person smokes

region: Residential region in the U.S.

charges: Medical charges billed (target variable)

Business Questions Answered

How does smoking behavior affect medical charges?

Are there cost differences based on gender or region?

Does higher BMI lead to higher medical expenses?

Which combinations of gender and smoking status result in higher risk?

❀  Dashboard Highlights

Chart 1: Average charges by smoker – smokers pay 3x more

Chart 2: BMI vs charges – costs rise significantly above BMI 30

Chart 3: Charges by gender and BMI – males incur higher charges on average

Chart 4: Charges by region – Southeast leads in average cost

Chart 5: Combined gender & smoker analysis – identifies high-risk groups

Interactive Filters (Slicers): Region, Gender, Smoker, Age

KPI Cards: Max charges, Average charges, Count of observations

❀  Screenshots

Screenshots of the dashboard pages should be included here.

❀  Key Insights

Smoking is the strongest contributor to increased medical costs.

BMI shows a clear positive correlation with expenses.

Southeast region shows the highest average charges.

Male smokers represent the highest-cost group.

❀ Next Steps

Add new features such as income, exercise level, or health conditions

Train predictive models (e.g., regression or classification) using Python or Power BI's DAX

Create comparisons between predicted and actual insurance premiums

Expand with Tableau or Jupyter notebooks for multi-platform analysis

❀ Files Included

/data/insurance.csv: Raw dataset

/report/insurance_cost_dashboard.pbix: Power BI dashboard file

/images/: Visualizations and screenshot assets

README.md: Project documentation

Created by Jing You | Data Analytics Capstone | April 2025

