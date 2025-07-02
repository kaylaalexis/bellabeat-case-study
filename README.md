# Bellabeat Case Study (Google Data Analytics Capstone)

This project is the final capstone for the Google Data Analytics Certificate.  
It explores how a wellness company like **Bellabeat** can leverage data from smart devices to better understand user behavior and improve their marketing strategy.

## 📊 Business Task

Analyze smart device usage data (Fitbit) to identify trends in physical activity, sleep, and calorie burn. Use these insights to make high-level recommendations that could support Bellabeat’s growth.

## 🗂️ Data Sources

- Public Fitbit user data from Kaggle  
- Datasets include: daily activity, sleep tracking, step count, calories burned, etc.

## 🔧 Tools Used

- **Google BigQuery Sandbox** (SQL queries)  
- **Microsoft Excel** (pivot tables + charts)  
- **GitHub** (for project storage and sharing)

## 🧹 Data Cleaning

Data was cleaned and merged in BigQuery using SQL joins, filters, and date formatting.  
Unnecessary columns and inconsistent date formats were removed or transformed.

## 📈 Key Findings

- Most users averaged fewer than **8,000 steps per day**
- Users who slept **7+ hours** generally walked more and burned more calories
- **Weekend activity** was lower than weekdays for many users
- A **small percentage** of users tracked their weight consistently
- **Sedentary time** made up the largest portion of most users' day

## ✅ Recommendations

- **Encourage consistent sleep** through in-app prompts and insights
- **Reward users for tracking daily habits** like steps and sleep
- **Educate users on the risks of low activity levels** using personalized app feedback
- **Promote weekday engagement and weekend challenges** to sustain user momentum

## 📂 Files in This Repository

- `bellabeat_case_study.pdf`: Full written case study with all findings and visualizations  
- `sql_query_1.png` to `sql_query_6.png`: Screenshots of SQL code used in BigQuery  
- `avg_steps_chart.png`, `sleep_vs_steps.png`, etc.: Visuals generated in Excel  
- `README.md`: Summary of project scope, tools, and findings
