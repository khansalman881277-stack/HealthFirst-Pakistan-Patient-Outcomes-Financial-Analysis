
🏥 Pakistan Hospital Patients Analysis
📌 Project Overview
This project analyzes patient data from multiple hospitals operated by HealthFirst Pakistan. The goal is to clean inconsistent data, perform meaningful analysis, and generate insights to support hospital management decisions.

🎯 Objectives
Clean and standardize messy healthcare data
Identify data quality issues
Analyze patient outcomes, billing, and hospital trends
Provide actionable recommendations for management
🧹 Phase 1 — Data Cleaning
Key issues identified and fixed:

Removed 'Rs.' prefix from bill_pkr and converted to numeric

Handled missing values and incorrect data types

Filtered unrealistic:

Body temperatures (<95°F or >105°F)
Ages (<0 or >100)
Standardized text fields (city, hospital names)

Removed duplicate patient records

📊 Phase 2 — Analysis
🔹 Key Business Questions Answered:
Top 5 diagnoses with highest average billing
Comparison of hospital stay (insured vs uninsured patients)
Relationship between ward type and patient outcomes
City-wise billing analysis (pricing vs diagnosis mix)
Correlation between blood pressure and length of stay
Monthly patient admission trends
📈 Key Insights
Certain diagnoses contribute significantly higher revenue
Insured patients tend to have longer hospital stays
ICU wards show different outcome patterns compared to general wards
Some cities show higher billing trends due to case complexity
Weak/moderate correlation between BP and length of stay
Seasonal spikes observed in hospital admissions
⚠️ Data Quality Issues
Inconsistent formatting across hospital systems
Missing and invalid entries in critical columns
Manual data merging introduced duplicates
Lack of validation rules in source systems
💡 Recommendations
Implement automated data validation at entry level
Standardize hospital data systems across all branches
Monitor high-cost diagnoses for cost optimization
Improve insurance handling workflows
Track seasonal demand for better resource planning
📁 Files Included
Hospital_Analysis.ipynb → Full analysis notebook
cleaned_data.csv → Cleaned dataset
🛠️ Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Google Colab
👤 Author
Data Analytics Project — HealthFirst Pakistan Case Study
