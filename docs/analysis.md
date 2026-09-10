# Analysis: Data Professional Survey Dashboard

<img width="1402" height="787" alt="Dashboard" src="screenshots/dashboard.png" />

## 1. Business Problem
The survey collects responses from data professionals worldwide. The goal is to understand:
- Which job titles pay the most
- Which programming languages are most used
- How difficult it is to break into data
- How satisfied professionals are with salary and work/life balance
- Where survey takers are located

## 2. Data Overview

| Field | Description |
|---|---|
| Unique ID | Survey response identifier |
| Date Taken | Date of response |
| Q1 - Current Role | Job title |
| Q2 - Career Switch | Whether they switched into data |
| Q3 - Salary | Salary range in USD |
| Q4 - Industry | Industry they work in |
| Q5 - Favorite Programming Language | Preferred language |
| Q6 - Happiness (Salary, Work/Life Balance, Coworkers, Management, Upward Mobility, Learning) | 0–10 ratings |
| Q7 - Difficulty to Break Into Data | Very Easy to Very Difficult |
| Q8 - Most Important Job Factor | Remote Work, Better Salary, Good Culture, etc. |
| Q9 - Gender | Male / Female |
| Q10 - Age | Respondent age |
| Q11 - Country | Country of residence |
| Q12 - Education | Highest education level |
| Q13 - Ethnicity | Self-reported ethnicity |

- Total responses: 630
- Average age: 29.87
- Time range: June 2022

## 3. Key Findings

### 3.1 Country Distribution
- United States: largest share
- India: second largest
- United Kingdom: third
- Canada: fourth
- Other countries: remaining share

**Insight:** The survey is heavily skewed toward the US and English-speaking countries.

### 3.2 Average Salary by Job Title
- Data Scientist: highest average salary
- Data Engineer: second
- Data Architect: third
- Other: fourth
- Data Analyst: fifth
- Database Developer: sixth
- Student/Looking/None: lowest

**Insight:** Specialized roles (Scientist, Engineer, Architect) pay more than generalist roles (Analyst).

### 3.3 Favorite Programming Language
- Python: dominant across all roles
- R: second
- Other: third
- C/C++, JavaScript, Java: minimal share

**Insight:** Python is the clear industry standard for data work.

### 3.4 Difficulty to Break Into Data
- Neither easy nor difficult: 42.7%
- Difficult: 24.76%
- Easy: 21.2%
- Very Difficult: 6.98%
- Very Easy: small share

**Insight:** Most people find entering data moderately challenging, not easy.

### 3.5 Happiness Scores
- Work/Life Balance: 5.74 / 10
- Salary: 4.27 / 10

**Insight:** Respondents are more satisfied with work/life balance than with salary.

## 4. Business Recommendations
- Learners should focus on Python and SQL.
- Career switchers should prepare for moderate difficulty entering data.
- Employers should review salary satisfaction, since it lags work/life balance.
- Salary benchmarks should be set by job title, not a single average.
