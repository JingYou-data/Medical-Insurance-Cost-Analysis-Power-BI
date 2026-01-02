# 🏥 Medical Insurance Cost Strategic Intelligence
> **An end-to-end Data Analytics project exploring behavioral and demographic drivers of medical expenses for 1,338 individuals.**

---

## 📄 Project Overview
This project explores the factors that influence personal medical charges using behavioral and demographic data. The goal is to uncover patterns that inform health insurance strategies and cost prediction.

* **Tools Used:** Power BI, Microsoft Excel.
* **Dataset Scale:** 1,338 raw records from Kaggle.

---

## 🛠️ Data Engineering Pipeline
Before visualization, I performed data profiling and cleaning to ensure data quality:

* **Data Cleaning:** Verified demographic features (Age, BMI, Region) and ensured data integrity for the target variable (Charges).
* **Feature Scope:** Processed 7 key dimensions including smoker status and dependent counts.

---

## 📈 Key Strategic Insights
(Detailed analysis and visualizations are available in the **PPT Presentation** found in the `/Reports` folder)

### 1. Smoker Impact Analysis
* Smoking behavior is the strongest contributor to increased medical costs.
* On average, **smokers pay 3x more** than non-smokers.

### 2. BMI & Expense Correlation
* BMI shows a clear positive correlation with expenses.
* Costs rise significantly once BMI exceeds the **30 (Obese)** threshold.

### 3. Demographic Risk Groups
* The **Southeast region** shows the highest average charges.
* **Male smokers** represent the highest-cost risk group identified in the study.

---

## 📂 Repository Structure

```text
├── Data/
│   └── insurance.csv               # Raw dataset (1,338 records)
├── Reports/
│   ├── insurance_cost_dashboard.pbix # Power BI project file
│   └── Medical Insurance Cost Analysis.pptx # Comprehensive project summary
└── README.md                       # Project documentation
