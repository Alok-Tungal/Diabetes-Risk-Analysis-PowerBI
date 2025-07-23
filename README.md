🩺 Diabetes Risk Analysis (Power BI Project)
This project showcases a complete Power BI dashboard focused on diabetes patient risk analysis, mimicking the real-world reporting standards used in healthcare analytics companies like Cotiviti.

📊 Dataset:
Source: Kaggle – Diabetes Patient Data

Patients: 768

Columns: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Diabetes

🛠️ Tools Used:
Power BI

DAX (Calculated Columns, Measures)

Data Modeling

Custom Visuals (Decomposition Tree, Gauge, Bullet, Box Plot)

🧩 Key Visuals & Insights:
🔢 Chart Type	🎯 Purpose
Pie / Donut Charts	Diabetes distribution by flag (Yes/No)
Clustered Bar/Column	Avg BMI & Glucose by diabetes status
Scatter Plot	Visualize BMI vs Glucose correlation
Line Chart	Glucose trends across Age
Heatmap / Matrix	Diabetes spread by Age Group & BMI Category
Gauge	Avg Pedigree Function (Genetic Risk Score)
Decomposition Tree	Drill-down on what influences diabetes most
Treemap	Diabetes count by BMI Category
KPI Cards	Total Patients, Avg BMI, Avg Glucose, Diabetic %
Table with Flags	Flag high-risk patients (BMI > 35 & Glucose > 160)

🧠 DAX Calculated Fields:
Diabetes_Flag: Yes/No

BMI_Category: Obese / Overweight / Normal

Age_Group: Under 30 / 30–50 / Above 50

Risk_Flag: High Risk if Glucose & BMI exceed thresholds

Health_Score: Custom metric combining Glucose, BMI, Age

🎯 Dashboard Highlights:
5 well-organized pages:

Overview

Risk Segments

Clinical Indicators

Lab Vitals

Summary Cards

Interactive filters:

Age Group

BMI Category

Diabetes Status

Clean layout with 3x5 grid, consistent color themes (Red = Risk, Green = Healthy)
