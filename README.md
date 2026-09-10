# Data Professional Survey Dashboard

Interactive Power BI dashboard analyzing survey responses from 630 data professionals worldwide. The dashboard explores salary by job title, favorite programming language, difficulty breaking into data, work/life balance, and country distribution.

## Tools
- Power BI
- Excel
- DAX

## Dataset
- `data/9_Power BI - Final Project.xlsx`
- 630 survey responses
- Fields include: job title, salary range, industry, favorite programming language, happiness with salary, happiness with work/life balance, difficulty breaking into data, country, age, education, ethnicity

## Dashboard Features
- KPI cards: Count of Survey Takers, Average Age
- Country of Survey Takers (treemap)
- Average Salary by Job Title (bar chart)
- Favorite Programming Language (stacked bar chart)
- Difficulty to Break Into Data (donut chart)
- Happiness with Work/Life Balance (gauge)
- Happiness with Salary (gauge)

## Key Insights
- Python is the most popular programming language across all data roles, followed by R and Other.
- Data Scientists report the highest average salary, followed by Data Engineers and Data Architects.
- Data Analysts make up the largest share of survey takers.
- 42.7% of respondents found it "Neither easy nor difficult" to break into data, while 24.76% found it "Difficult" and 21.2% found it "Easy".
- Average happiness with work/life balance (5.74/10) is higher than happiness with salary (4.27/10).
- Most survey takers are from the United States, followed by India, the United Kingdom, and Canada.

## Business Recommendations
- Learners should prioritize Python and SQL, as they dominate across data roles.
- Career switchers should expect moderate difficulty entering data; only a small share found it "Very Easy".
- Employers should note the salary vs. happiness gap: pay satisfaction is lower than work/life balance satisfaction.
- Salary benchmarks vary significantly by job title, which is useful for negotiation and hiring.

## Limitations
- Self-reported survey data, not verified salary records.
- Salary is provided in ranges, not exact figures.
- Sample is skewed toward the United States and English-speaking countries.
- Only 630 responses, so results are not globally representative.
- Some fields have inconsistent or free-text entries.

## Repository Structure
```text
data-professional-survey-dashboard/
├── README.md
├── data_professional_survey.pbix
├── data/
│   └── 9_Power BI - Final Project.xlsx
├── screenshots/
│   └── dashboard.png
└── docs/
    ├── analysis.md
    └── data-dictionary.md
