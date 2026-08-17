# Student Academic Pressure & Mental Health Analysis

## 📌 Project Overview

This project analyzes student academic pressure and mental health-related factors using a student survey dataset sourced from Kaggle.

The project was completed as part of my self-directed learning journey in Data Analytics, with Microsoft Excel used to clean, analyze, visualize, and present the data.

The analysis focused on identifying patterns in:

- Academic pressure
- Stress frequency
- Age groups
- Gender
- Sleep duration
- Reported causes of academic pressure

The final outcome was an interactive Excel dashboard designed to make the survey data easier to understand and interpret.

---

## 🎯 Project Objective

The main objective of this project was to transform raw student survey responses into meaningful insights using Microsoft Excel.

Specifically, I wanted to understand:

- How academic pressure varied across age groups
- How frequently students experienced stress
- Whether reported academic pressure differed by gender
- How sleep duration related to reported academic pressure
- What students reported as causes of academic pressure
- How stress frequency varied across age groups

---

## 🗂️ Dataset

**Source:** Kaggle

**Dataset Type:** Student survey data

**Number of Respondents:** 453

The dataset contained variables related to students' demographic characteristics, academic pressure, stress frequency, sleep duration, and reported causes of academic pressure.

### Key Variables

- Age Group
- Gender
- Academic Pressure
- Stress Frequency
- Sleep Duration
- Main Cause of Academic Pressure

---

## 🛠️ Tools & Techniques

### Tools

- Microsoft Excel

### Techniques

- Data Cleaning
- Data Validation
- Excel Tables
- Excel Formulas
- PivotTables
- PivotCharts
- Percentage Calculations
- Data Visualization
- KPI Development
- Dashboard Design

---

## 🔄 Project Workflow

The project followed this workflow:

**Raw Kaggle Dataset**

↓

**Data Cleaning & Validation**

↓

**Calculations**

↓

**PivotTables**

↓

**PivotCharts**

↓

**Dashboard Development**

↓

**Insight Generation**

---

## 🧹 Data Preparation

Before beginning the analysis, I reviewed and prepared the dataset to make sure the variables were suitable for analysis.

The preparation process included:

- Reviewing the dataset structure
- Reviewing the variables
- Checking data types
- Cleaning survey fields
- Working with categorical variables such as stress frequency
- Preparing academic pressure for numerical analysis
- Creating respondent count calculations
- Calculating stress percentages
- Validating calculations against the source data
- Formatting the results for presentation

---

## 📊 Data Analysis

I used PivotTables to summarize the survey responses and compare academic pressure and stress across different groups.

### Analysis Areas

#### Academic Pressure by Age Group

I calculated the average academic pressure for different age groups to identify differences across the dataset.

#### Stress Frequency

I calculated the percentage of respondents who reported experiencing stress:

- Sometimes
- Always
- Often

#### Academic Pressure by Gender

I compared the average academic pressure reported by male and female respondents.

#### Sleep Duration & Academic Pressure

I examined the average academic pressure across different sleep-duration categories.

#### Causes of Academic Pressure

I analyzed the reported causes of academic pressure, including financial and examination-related factors.

#### Age Group & Stress Frequency

I compared stress frequency across different age groups to identify patterns in the responses.

---

## 📈 Dashboard Development

I created two versions of the dashboard during the project.

### Version 1 — Initial Analytical Dashboard

[📊 View First Dashboard](https://github.com/Roshydah-07/Student-Mental-Health-Academic-Pressure-Analysis/blob/main/First%20dashboard%20of%20students%20mental%20health.png)The first dashboard focused mainly on exploring and presenting the analysis.

It included:

- Average academic pressure by age
- Stress frequency distribution
- Sleep duration vs. academic pressure
- Gender vs. academic pressure
- Main causes of academic pressure
- Age group vs. stress frequency

### Version 2 — Refined Dashboard

[📊 View Final Dashboard](https://github.com/Roshydah-07/Student-Mental-Health-Academic-Pressure-Analysis/blob/main/F%20Second%20dashboard%20of%20students%20mental%20health.png)
After reviewing the first version, I improved the dashboard to make it more suitable for presentation.

The improvements included:

- KPI cards
- Average academic pressure KPI
- Respondent count KPI
- Improved spacing
- Clearer chart titles
- Consistent formatting
- Better visual organization
- Cleaner overall presentation

The second version became the refined and presentation-ready version of the dashboard.

---

## ⚠️ Challenges & Problem Solving

### 1. DIV/0! Error When Calculating Average Academic Pressure

While calculating average academic pressure, I encountered a `DIV/0!` error.

I investigated the underlying data and calculation setup to determine why Excel was unable to produce a valid average.

I checked the relevant values and calculation setup, corrected the issue, and rebuilt the analysis.

### What I Learned

This helped me understand the importance of checking the underlying data and calculation logic instead of simply ignoring an error.

---

### 2. Stress Percentage Initially Returned 100%

Another challenge occurred when calculating the percentage of respondents in each stress-frequency category.

The calculation initially returned **100%**, which was not the expected result.

After investigating the calculation, I realized that the denominator was being affected by the same category filter. This meant the calculation was effectively comparing a category against itself.

I corrected the calculation so that the denominator represented the **total number of respondents**.

I then validated the results against the dataset.

### Final Stress Distribution

- **Sometimes — 64%**
- **Always — 21%**
- **Often — 15%**

---

### 3. Dashboard Readability

I also worked on improving the presentation of the dashboard.

I adjusted:

- Data labels
- Number formatting
- Chart titles
- Spacing
- Visual organization

This made the final dashboard easier to read and interpret.

---

## 💡 Key Findings

### 1. Younger Respondents Reported Higher Average Academic Pressure

The analysis showed that average reported academic pressure decreased across the age groups in this dataset.

| Age Group | Average Academic Pressure |
|---|---:|
| Under 15 | 4.5 |
| 15–18 | 4.1 |
| 19–22 | 3.8 |
| 23–26 | 3.0 |
| 27+ | 2.5 |

The **Under 15** group recorded the highest average academic pressure at **4.5**, while the **27+** group recorded the lowest at **2.5**.

> This represents an observed pattern in the dataset and should not be interpreted as evidence that age causes academic pressure.

---

### 2. Most Respondents Experienced Stress Sometimes

The stress-frequency analysis showed:

- **64%** experienced stress sometimes
- **21%** experienced stress always
- **15%** experienced stress often

This shows that experiencing stress was common among the respondents, with "Sometimes" being the largest reported category.

---

### 3. Male Respondents Reported a Higher Average Academic Pressure Score

The analysis showed approximately:

| Gender | Average Academic Pressure |
|---|---:|
| Male | 4.0 |
| Female | 3.6 |

Male respondents in this dataset reported a higher average academic pressure score than female respondents.

> This is an observed difference within the dataset and does not establish that gender causes the difference.

---

### 4. Sleep Duration and Academic Pressure

The analysis showed the following average academic pressure scores:

| Sleep Duration | Average Academic Pressure |
|---|---:|
| More than 8 hours | 4.0 |
| 7–8 hours | 3.9 |
| 5–6 hours | 3.8 |

Interestingly, respondents reporting more than 8 hours of sleep had the highest average academic pressure among the categories shown.

> This represents an observed association in the dataset and does not establish that sleep duration causes academic pressure.

---

### 5. Financial and Examination-Related Factors Appeared Among Reported Causes

The analysis identified categories relating to:

- Financial conditions
- Exams
- Difficulty understanding subjects
- Other financial concerns
- Business stress

These factors appeared among the reported causes of academic pressure in the dataset.

---

### 6. Stress Patterns Differed Across Age Groups

Stress frequency was not evenly distributed across the age groups.

The **15–18** age group appeared particularly prominent, especially within the "Sometimes" stress category.

---

## 📷 Dashboard Preview

### Initial Dashboard

_Add screenshot of the first dashboard here._

### Refined Dashboard

_Add screenshot of the final/refined dashboard here._

---

## 📊 Key Performance Indicators

The final dashboard included two main KPIs:

### Average Academic Pressure

**3.8**

### Number of Respondents

**453**

---

## 🧠 What I Learned

This project helped me develop practical experience in:

- Cleaning and validating data
- Working with survey datasets
- Using Excel formulas
- Creating PivotTables
- Creating PivotCharts
- Calculating percentages
- Developing KPIs
- Building dashboards
- Troubleshooting calculation errors
- Improving dashboard design
- Communicating analytical findings

One of the most valuable parts of the project was learning how to investigate unexpected results rather than simply accepting them.

---

## 🚀 Project Outcome

The project transformed individual student survey responses into an interactive Excel dashboard that made it easier to identify patterns in academic pressure and stress across different groups.

Through this project, I strengthened my ability to move from:

**Raw Data → Cleaning → Analysis → Visualization → Dashboard → Insights**

---

## ⚠️ Analytical Note

The findings in this project describe patterns and associations observed within the dataset.

They should not be interpreted as evidence of causation.

For example, a difference in academic pressure across age groups does not mean that age causes academic pressure.

---

## 👩🏽‍💻 About This Project

This project was completed as part of my self-directed learning journey in Data Analytics.

I handled the project from data preparation through to the final dashboard, including data cleaning, calculations, PivotTables, PivotCharts, visualization, troubleshooting, and dashboard design.

### Tools Used

**Microsoft Excel**

### Project Type

**Self-Learning / Data Analytics Project**

---

## 👤 Author

**Rasheedat Oseni**

Aspiring Data Analyst | Excel | Power Query | Power BI
