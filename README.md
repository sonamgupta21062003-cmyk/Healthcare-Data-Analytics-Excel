Healthcare Data Analytics – Excel Project

📊 Project Overview

This project is an end-to-end Healthcare Data Analytics project built in Microsoft Excel using a dataset of 10,000 patient records.

The objective is to transform raw healthcare data into meaningful business insights related to:

Patient demographics

Medical conditions

Hospital admissions

Insurance providers

Billing amounts

Length of hospital stay

Gender and age-group patterns

Medical-condition distribution

Insurance and billing analysis

The project demonstrates practical Excel skills including data cleaning, feature engineering, formulas, PivotTables, statistical analysis, and analytical storytelling.

🎯 Business Objectives

The analysis was designed to answer questions such as:

Which medical conditions are most common?

How are patients distributed across age groups and genders?

Which hospitals have the highest number of patients?

How are patients distributed across insurance providers?

What is the average billing amount?

Does the length of stay have a relationship with billing amount?

How do billing amounts differ across medical conditions?

How are medical conditions distributed across insurance providers?

How do medical conditions vary by gender?

How has patient volume changed over the years?

🗂️ Dataset

Records: 10,000 patients

Original columns: 15

Final analytical columns: 22

Time period: 2018–2023

Main fields

Category

Fields

Patient

Name, Age, Gender, Blood Type

Medical

Medical Condition, Medication, Test Results

Hospital

Hospital, Doctor, Room Number

Admission

Date of Admission, Admission Type, Discharge Date

Financial

Billing Amount

Insurance

Insurance Provider

Derived Features

Age Bucket, Demographic Group, Duration of Stay, Year, Month, Day, Month Name

🧹 Data Preparation

The raw dataset was transformed into an analysis-ready sheet.

Data preparation steps

Cleaned inconsistent text/category values

Standardized medical-condition names

Standardized admission-type values

Converted numeric fields to proper numeric format

Converted date fields to usable date formats

Calculated Duration of Stay

Extracted Year, Month, Day, and Month Name

Created Age Bucket

Created combined Demographic Group fields such as Senior-Female and Middle-Male

Structured the dataset for PivotTable analysis

🧮 Feature Engineering

Additional analytical fields were created to make the dataset easier to analyze.

Duration of Stay

Duration of Stay = Discharge Date - Date of Admission

Age Bucket

Patients were grouped into:

Young

Middle

Senior

Demographic Group

Gender and age bucket were combined to create groups such as:

Young-Female
Young-Male
Middle-Female
Middle-Male
Senior-Female
Senior-Male

Date Features

The admission date was broken into:

Year

Month

Day

Month Name

📈 Analysis Performed

1. Patient & Medical Condition Analysis

Analyzed patient counts by:

Medical condition

Gender

Age bucket

Blood type

Hospital

The analysis identifies the distribution of major conditions including:

Hypertension

Cancer

Obesity

Arthritis

Asthma

Diabetes

2. Demographic Analysis

Analyzed how medical conditions are distributed across:

Young / Middle / Senior patients

Male / Female patients

Combined demographic groups

This helps identify demographic patterns in patient conditions.

3. Insurance Provider Analysis

Compared insurance providers based on:

Number of patients

Percentage of total patients

Average billing amount

Insurance providers included:

Medicare

UnitedHealthcare

Aetna

Cigna

Blue Cross

4. Billing Analysis

Analyzed billing amounts using:

Average billing amount

Medical condition

Insurance provider

Patient demographics

Duration of stay

The overall average billing amount in the analytical dataset is approximately 23,381.

5. Length of Stay Analysis

Calculated the duration of each hospital stay and analyzed:

Patient count by stay duration

Average billing amount by stay duration

Billing differences across stay durations

This analysis was used to investigate whether hospitalization duration is associated with billing amount.

Note: This is an observational Excel analysis and does not establish causation.

6. PivotTable Analysis

PivotTables were used extensively to summarize:

Patient counts

Medical conditions

Gender distribution

Age groups

Blood types

Insurance providers

Year-wise patient volume

Condition vs demographic relationships

Condition vs insurance relationships

Billing metrics

📊 Key Dataset Statistics

Metric

Value

Total Patients

10,000

Medical Conditions

6

Insurance Providers

5

Admission Types

3

Test Result Categories

3

Medications

5

Age Groups

3

Years Covered

2018–2023

Average Billing Amount

~23,381

Average Duration of Stay

~13.82 days

Maximum Duration of Stay

30 days

🛠️ Excel Skills Demonstrated

This project demonstrates practical skills in:

Data Cleaning

Data Transformation

Excel Tables

Data Validation / Standardization

IF / nested logic

Date calculations

Text standardization

Feature Engineering

PivotTables

Pivot Charts

COUNTIF / COUNTIFS

SUMIF / SUMIFS

AVERAGEIF / AVERAGEIFS

Percentage calculations

Descriptive Statistics

Comparative Analysis

Business Insight Generation

Dashboard-style analytical reporting

📁 Workbook Structure

Raw_Data

Original healthcare dataset.

Healthcare

Cleaned and transformed analytical dataset containing derived features.

Sheet5

Working/analysis sheet derived from the cleaned dataset.

Sample Sales Analysis

PivotTable-based exploratory analysis including:

Hospital patient counts

Medical-condition counts

Gender distribution

Blood-group distribution

Year-wise patient volume

Age-group vs medical-condition analysis

Advance analysis

Advanced analytical work including:

Age-group vs medical-condition analysis

Gender distribution by medical condition

Blood-group vs medical-condition analysis

Insurance-provider analysis

Insurance-provider billing analysis

Medical-condition billing comparison

Duration-of-stay analysis

Billing comparison by stay duration

💡 Business Insights

The workbook can be used to communicate insights such as:

Patient volume can be compared across years to understand changes in healthcare demand.

Medical conditions can be examined across age and gender groups to identify demographic patterns.

Insurance providers can be compared using both patient volume and average billing amount.

Billing amounts can be analyzed across medical conditions and hospitalization duration.

PivotTable analysis makes it easier for healthcare managers to explore patient and financial patterns.

📌 Important Note

This project is intended for portfolio and educational data-analysis purposes.

The dataset is analyzed statistically and should not be interpreted as medical advice or as evidence of clinical causation.

👩‍💻 Author

Sonam Gupta

Skills

Microsoft Excel Data Analytics Data Cleaning PivotTables Statistics Data Visualization Business Analysis

⭐ Project Highlights

10,000+ healthcare records | Data Cleaning | Feature Engineering | Statistics | PivotTables | Advanced Excel Analysis | Healthcare Analytics
