# 🔍 Data Science Job Market Analysis — Power Query & Pivot Tables

An Excel project analysing the data science job market using **Power Query** and **Pivot Tables**. Built as part of my data analysis learning journey, this workbook explores skill demand, salary trends, and job role distributions across a large dataset of real job postings.

---

## 🎯 Project Overview

This workbook answers key questions about the data science job market:
- Which skills are most in demand?
- How does salary vary by job title, location, and skill?
- Is hourly or yearly pay better for different roles?
- How many skills does each role typically require?

---

## 📁 Workbook Structure

| Sheet | Description |
|---|---|
| `Data_Jobs_skills` | Raw data imported and transformed via Power Query |
| `Data_Jobs_skill_count` | Top skills ranked by how often they appear in job postings |
| `Job Analysis` | Pivot table — job postings count broken down by job title |
| `Skill_Job_Analysis` | Skill likelihood per job posting (how often each skill appears) |
| `Salary vs Skills` | Median salary and average skills required per job title |
| `Salary_Analysis` | Median salary breakdown — overall, US only, and non-US |
| `Skill_Salary_Analysis` | Median salary and demand likelihood per skill |
| `Salary_VS_Hourly_Salary` | Comparison of hourly-adjusted vs yearly salary by job title |

---

## 🔢 Key Techniques Used

- **Power Query** — data import, transformation, and cleaning
- **Pivot Tables** — summarising and slicing large datasets
- **Calculated fields** — skill likelihood ratios, adjusted salaries
- **Cross-sheet analysis** — combining multiple pivot outputs for comparison

---

## 📈 Key Findings

### Top 10 Most In-Demand Skills
| Skill | Job Postings Mentioning It |
|---|---|
| SQL | 18,500 |
| Python | 17,689 |
| Tableau | 7,043 |
| R | 6,929 |
| AWS | 6,844 |
| Excel | 6,260 |
| Spark | 5,290 |
| SAS | 4,806 |
| Azure | 4,760 |
| Java | 3,827 |

### Median Salary by Job Title (USD)
| Job Title | Median Salary | Avg Skills Required |
|---|---|---|
| Senior Data Scientist | $155,000 | 5.2 |
| Senior Data Engineer | $150,000 | 8.3 |
| Machine Learning Engineer | $150,000 | 4.7 |
| Data Scientist | $130,000 | 5.0 |
| Software Engineer | $125,000 | 5.1 |
| Data Engineer | $125,000 | 6.9 |
| Cloud Engineer | $115,000 | 4.8 |
| Senior Data Analyst | $110,000 | 4.4 |
| Data Analyst | $90,000 | 3.6 |
| Business Analyst | $90,000 | 3.3 |

### US vs Non-US Salaries
Most roles pay significantly more in the US. Notable gaps:
- Machine Learning Engineer: $150k US vs $101k non-US
- Software Engineer: $125k US vs $89k non-US
- Data Engineer: $125k US vs $123.5k non-US (smallest gap)

### Hourly vs Yearly Pay
Yearly-salaried positions consistently pay more than hourly-adjusted equivalents across all roles. The biggest gaps are in Data Scientist ($135.8k yearly vs $102.7k hourly) and Senior Data Scientist ($154k yearly vs $112k hourly).

### Skill Likelihood vs Salary
| Skill | Likelihood | Median Salary |
|---|---|---|
| SQL | 52.5% | $90,000 |
| Excel | 41.5% | $84,500 |
| Tableau | 28.7% | $92,500 |
| Python | 27.7% | $97,087 |
| Power BI | 16.8% | $90,000 |

> Python is the best ROI skill — not the most common, but among the highest paying.

---

## 🛠️ Tools & Skills Practiced

- **Excel 2019**
- Power Query (data import & transformation)
- Pivot Tables & Pivot Charts
- Calculated fields and custom aggregations
- Cross-table salary and skill analysis

---

## 📚 Learning Journey

This is part of my ongoing Excel for Data Analysis training. This project focuses on Power Query and Pivot Tables — two of the most important tools in any data analyst's Excel workflow — applied to a real-world job market dataset.

---

*Dataset contains data science job postings. Salaries in USD.*
