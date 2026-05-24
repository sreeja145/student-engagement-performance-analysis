# Open University Learning Analytics: Student Success & Retention Analysis

## Project Overview
This project analyzes The Open University Learning Analytics dataset to evaluate how student engagement, learning behavior, and academic effort influence academic performance and retention outcomes.

The analysis focuses on identifying behavioral and academic patterns associated with efficient learning, disengagement, and withdrawal risk using Python, SQL, and Tableau.

A custom performance metric called **Academic Success Efficiency (ASE)** was designed to measure how effectively students convert learning effort into academic outcomes.

---

## Business Problem
Traditional learning analytics often rely on activity-based metrics such as:
- Login frequency
- Total VLE clicks
- Assessment submissions

However, high activity does not always translate into better academic performance.

This project aims to answer:
- Which student behaviors contribute to efficient learning?
- Can early engagement patterns predict retention risk?
- Do socioeconomic and educational factors influence academic efficiency?
- How can institutions identify at-risk students earlier?

---

## Dataset Information
Source: Open University Learning Analytics Dataset (OULAD)

The dataset contains:
- Student demographics
- Registration data
- Assessment scores
- Virtual Learning Environment (VLE) activity logs
- Course and module information

### Key Data Tables
- `studentInfo`
- `studentRegistration`
- `studentAssessment`
- `studentVle`
- `assessments`
- `courses`
- `vle`

---

## Tools & Technologies
- Python
- SQL
- Tableau
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Workflow
### 1. Data Cleaning & Preparation
- Removed duplicate records
- Handled missing values
- Merged multiple datasets
- Standardized data formats
- Treated outliers using percentile capping

### 2. Feature Engineering
Created custom analytical metrics including:
- Academic Success Efficiency (ASE)
- Early Engagement Score
- VLE Intensity Index
- Assessment Preparation Ratio

### 3. Exploratory Data Analysis (EDA)
Performed:
- Correlation analysis
- Distribution analysis
- Retention risk analysis
- Behavioral segmentation
- Demographic comparison analysis

### 4. Dashboard Development
Built Tableau dashboards to visualize:
- Student engagement trends
- ASE distribution
- Withdrawal risk indicators
- Performance comparisons
- Retention insights

---

## Key Findings

### 1. Moderate Engagement Produced Better Efficiency
Students with moderate early engagement and balanced assessment preparation achieved higher academic efficiency compared to students with extremely high activity levels.

### 2. High Activity Did Not Always Mean Better Outcomes
Students with excessive VLE interaction often showed diminishing returns in academic efficiency, indicating that more activity alone does not guarantee better performance.

### 3. Academic Workload Influenced Performance
Students carrying heavier academic workloads demonstrated lower ASE scores and higher retention risk patterns.

### 4. Educational Background Impacted Efficiency
Students with stronger prior educational backgrounds consistently showed higher academic efficiency and better academic outcomes.

### 5. Early Engagement Was a Strong Retention Indicator
Lower engagement during the first 30 days was frequently associated with lower performance and increased withdrawal risk.

---

## Tableau Dashboard
[https://public.tableau.com/app/profile/n.sreeja/viz/AcademicSuccessEfficiencyDashboard/ProjectOverview]

---

## Author
Sreeja N
