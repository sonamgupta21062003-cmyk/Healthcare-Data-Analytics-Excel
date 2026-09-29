🏥 Healthcare Data Analytics & Excel Dashboard

An end-to-end Excel analytics project focused on patient demographics, medical conditions, admissions, insurance, billing, and length-of-stay analysis.






📌 Project Overview

This project analyzes a 10,000-record healthcare dataset to understand patient demographics, medical conditions, admission patterns, insurance distribution, hospital billing, and length of stay.

The workbook combines data cleaning, feature creation, pivot-based analysis, advanced Excel calculations, KPI analysis, and dashboard-style visualizations to convert raw healthcare records into actionable insights.

🎯 Business Questions

The analysis was designed around questions such as:

Which medical conditions occur most frequently?

Which conditions have the highest average billing?

How have patient admissions changed over the years?

Which admission type is most common?

How are patients distributed across insurance providers?

What is the typical patient billing amount?

Does length of stay show a meaningful relationship with billing?

How do patient demographics differ across conditions?

How can insurance providers be compared using patient volume and billing metrics?

📊 Dataset Snapshot

Metric

Value

Total patient records

10,000

Average billing amount

23,381.11

Median billing amount

20,280.00

Average length of stay

13.82 days

Female patients

50.7%

Male patients

49.2%

Emergency admissions

35.9%

Highest-volume condition

Hypertension (2,155)

Highest average billing condition

Cancer (39,676.54)

Most represented insurer

Medicare (2,428)

Peak admission year

2021 (2,063 records)

Note: Monetary values are presented in the dataset's original units; the workbook does not specify a currency.

🧰 Tools & Skills

Core Tools

Microsoft Excel

Pivot Tables

Pivot Charts

Excel formulas

Data cleaning

Exploratory Data Analysis (EDA)

Dashboard design

Business-oriented data storytelling

Excel Techniques

COUNTIF / COUNTIFS

SUMIF / SUMIFS

AVERAGEIF / AVERAGEIFS

MINIFS / MAXIFS

Date and time functions

Conditional formatting

PivotTable aggregation

Grouping and categorization

Percentage calculations

Cross-tabulation

Trend analysis

🔄 Analysis Workflow

                 RAW HEALTHCARE DATA
                         │
                         ▼
                ┌─────────────────┐
                │ Data Inspection  │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Data Cleaning    │
                │ & Standardizing  │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Feature Creation │
                │ Age Bucket       │
                │ Year / Month     │
                │ Stay Duration    │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Pivot Analysis   │
                │ & KPIs           │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Visualization    │
                │ & Dashboard      │
                └────────┬────────┘
                         │
                         ▼
                 BUSINESS INSIGHTS

📈 Visual Analysis

1. Medical Condition Distribution

The condition distribution shows Hypertension as the largest patient category in this dataset.



2. Average Billing by Medical Condition

Average billing differs substantially across conditions. Cancer has the highest average billing in this dataset.



3. Patient Admissions Over Time

The yearly trend shows how the number of records changes across the available admission years, with the highest recorded volume occurring in 2021.



4. Admission Type Analysis

Emergency admissions represent the largest admission category, followed by urgent and elective admissions.



5. Insurance Provider Distribution

The analysis compares patient volume across the five insurance providers represented in the dataset.



6. Length of Stay vs Billing

A scatter analysis was used to examine whether longer hospital stays correspond to higher billing amounts.

The Pearson correlation in this dataset is approximately -0.003, indicating very little linear relationship between these two variables.



Correlation does not establish causation. Other factors such as medical condition, treatment, medication, and admission characteristics may contribute to billing.

🔎 Key Insights

🩺 Patient Mix

Hypertension is the most frequently represented medical condition with 2,155 records.

The dataset contains six major medical conditions.

Female patients account for approximately 50.7% of the records, while male patients account for 49.2%.

💰 Billing

Average billing is approximately 23,381.11.

Median billing is approximately 20,280.00.

Cancer has the highest average billing amount among the medical conditions.

🏥 Admissions

Emergency is the most common admission type.

Emergency admissions account for approximately 35.9% of all records.

The highest annual record volume occurs in 2021.

🛡️ Insurance

Medicare has the largest patient count among the insurance providers.

Insurance providers can be compared using both patient volume and average billing rather than relying on a single metric.

⏱️ Length of Stay

Average length of stay is 13.82 days.

The correlation between length of stay and billing is approximately -0.003, so the dataset does not show a strong linear relationship between these variables.

📋 Workbook Structure

The original Excel workbook contains multiple analytical sheets:

Sheet

Purpose

Healthcare

Cleaned/analysis-ready healthcare dataset with calculated fields

Raw_Data

Raw source data

Sheet5

Additional working/analysis data

Sample Sales Analysis

Pivot-style summary analysis

Advance analysis

Advanced cross-tabulations, billing analysis, insurance analysis and relationship analysis

Important calculated fields

The analysis-ready sheet includes derived fields such as:

Age Bucket

Demographic columns

Duration of stay

Year

Month

Day

Month Name

📊 KPI Dashboard Concept

The dashboard is designed around five major KPI areas:

┌────────────────┬────────────────┬────────────────┐
│ Total Patients │ Avg Billing    │ Avg Stay       │
│    10,000      │   23,381.11    │   13.82 days   │
└────────────────┴────────────────┴────────────────┘

┌────────────────┬────────────────┬────────────────┐
│ Top Condition  │ Top Insurance  │ Peak Year      │
│  Hypertension  │    Medicare    │     2021       │
└────────────────┴────────────────┴────────────────┘

These KPIs provide a quick executive-level summary before moving into detailed analysis.

💡 Why This Project Matters

This project demonstrates how raw healthcare records can be transformed into a structured analytical solution.

Instead of only creating charts, the project follows a business-analysis approach:

Raw Data → Cleaning → Feature Engineering → KPI Creation → Segmentation → Trend Analysis → Visualization → Insights

This makes the project suitable for demonstrating practical skills for Data Analyst / Business Analyst / Excel Analyst roles.

🚀 Possible Future Improvements

Build an interactive Excel dashboard with slicers

Add month-over-month admission trends

Add condition × insurance heatmaps

Analyze medication patterns

Add doctor/hospital performance analysis

Create a billing segmentation model

Add automated KPI refresh using Power Query

Rebuild the dashboard in Power BI

Build the same analysis using Python + Pandas

Add statistical testing and hypothesis analysis

Explore relationships between medical condition, stay duration, and billing

📁 Recommended GitHub Structure

Healthcare-Data-Analytics/
│
├── README.md
│
├── data/
│   └── healthcare_dataset.xlsx
│
├── visualizations/
│   ├── 01_condition_distribution.png
│   ├── 02_avg_billing_condition.png
│   ├── 03_admissions_by_year.png
│   ├── 04_admission_type.png
│   ├── 05_insurance_distribution.png
│   └── 06_stay_vs_billing.png
│
└── dashboard/
    └── healthcare_dashboard.xlsx

If the workbook contains any real/personal patient information, do not upload it publicly. Use an anonymized or synthetic dataset instead.

👩‍💻 Author

Sonam Gupta

B.Sc. Computer Science | Aspiring Data Analyst / AI & ML Professional

⭐ Project Highlights

10,000+ records • Healthcare analytics • Excel • PivotTables  • EDA • Dashboarding • Business insights • Data visualization

