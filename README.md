# 🏥 Medical Insurance Cost Strategic Intelligence
> **An end-to-end Data Analytics project exploring behavioral and demographic drivers of medical expenses for 1,338 individuals using Power BI.**

---

## 🎥 Project Demo
* **[🚀 Live Interactive Dashboard](这里粘贴你的PowerBI分享链接)**
* **Video Walkthrough:** Found in `/Media/capstone_video.mp4`

---

## 🛠️ Data Engineering & Pipeline
Before visualization, I performed data profiling and extensive ETL to ensure data quality:

* **Data Scale:** Analyzed **1,338 records** across 7 key dimensions (Age, Sex, BMI, Children, Smoker, Region, Charges).
* **Cleaning Logic:**
    * Verified demographic features and identified behavioral patterns.
    * Ensured data integrity for the target variable: medical charges billed.

---

## 📈 Visual Insights

### 1. Executive Summary
Overview of global KPIs including **Average Charges**, **Max Charges**, and count of observations.

![Dashboard Overview](Media/dashboard_main.png)

### 2. Smoker Impact Analysis
Smoking behavior is the strongest contributor to increased costs; on average, **smokers pay 3x more** than non-smokers.

### 3. BMI & Expense Correlation
Medical costs rise significantly once BMI exceeds the **30 (Obese)** threshold, showing a clear positive correlation.

### 4. Regional Intelligence
The **Southeast region** leads in average medical cost, and **male smokers** represent the highest-risk group.

---

## 📂 Repository Structure

```text
├── Data/
│   └── insurance.csv               # Raw dataset (1,338 records)
├── Reports/
│   ├── insurance_cost_dashboard.pbix # Power BI interactive dashboard
│   └── Medical Insurance Cost Analysis with Power BI.pptx # Summary presentation
├── Media/
│   ├── dashboard_main.png          # Main dashboard screenshot
│   ├── smoker_analysis.png         # Key analysis visualization
│   └── bmi_charges.png             # BMI correlation visualization
└── README.md                       # Project documentation
