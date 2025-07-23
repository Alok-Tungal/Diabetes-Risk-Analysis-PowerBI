# 🩺 Diabetes Risk Analysis – Power BI Project

This project demonstrates a **full-scale healthcare dashboard** using **Power BI**, inspired by real-world healthcare analytics used by companies like **Cotiviti**. The goal is to visually analyze patient health metrics and identify diabetes risk patterns using DAX, calculated metrics, and 25+ visualizations.

---

## 📊 Dataset Details

* **Source:** [Kaggle](https://www.kaggle.com/datasets/whenamancodes/diabetes-patient-data)
* **Total Records:** 768 patients
* **Columns:** Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Diabetes

---

## 🛠 Tools Used

* Power BI Desktop
* DAX for calculated columns and measures
* Power BI custom visuals (Decomposition Tree, Bullet Chart, Gauge, Box Plot)

---

## 📌 Dashboard Features

* ✅ 5 Clean Layout Pages:

  1. Diabetes Overview
  2. Risk Segments
  3. Clinical Factors
  4. Lab Vitals
  5. Summary Cards

* ✅ Color-coded Risk Levels:

  * Red: High Risk
  * Orange: Pre-Diabetic
  * Green: Healthy

* ✅ Slicers:

  * Age Group
  * BMI Category
  * Diabetes Status

---

## 🔎 Key DAX Calculated Columns

* `Diabetes_Flag` → IF(Diabetes = 1, "Yes", "No")
* `BMI_Category` → Obese / Overweight / Normal
* `Age_Group` → Under 30 / 30–50 / Above 50
* `Risk_Flag` → High Risk if Glucose > 160 & BMI > 35
* `Health_Score` → Custom metric combining Glucose, BMI, Age

---

## 📈 Key Visualizations (Top 15+)

* Pie Chart – Diabetes Distribution
* Column Chart – Diabetes by Age Group
* Scatter Plot – Glucose vs BMI
* Line Chart – Glucose Trend by Age
* Gauge – Avg Diabetes Pedigree Function
* Heatmap – Age Group × BMI Category
* KPI Cards – Total Patients, Avg BMI, Diabetic %
* Treemap – Diabetes by BMI Category
* Decomposition Tree – Diabetes Influencers
* Table with Risk Flags – High-Risk Patients
* Histogram – Glucose and BMI Distribution
* Bullet Chart – Avg Glucose vs Target
* Smart Narrative – AI Summary of Insights

---

## 📄 Files Included

* `diabetes_patient_health_data.pbit` – Main Power BI Dashboard
* `README.md` – Project Documentation
* 📷 `Screenshots/` – Dashboard views for resume/portfolio

---

## 🧠 Sample Insights

* Over 60% of diabetic patients are obese (BMI > 30)
* Avg glucose for diabetics exceeds 150 mg/dL
* 34% of patients over age 50 show high hereditary risk (pedigree > 0.7)

---

## 📌 How to Use

1. Open Power BI → File → Open → `diabetes_patient_health_data.pbit
2. Click through pages for visuals
3. Use slicers to filter Age/BMI/Diabetes Status
4. Export as PDF or PowerPoint for presentations

---

**Author:** Alok Mahadev Tungal
**LinkedIn:** [linkedin.com/in/your-profile](#)
**GitHub:** [github.com/yourusername](#)
