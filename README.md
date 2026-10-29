# Data Job Market Analysis

## About
This project follows Luke Barousse's "Python for Data Analytics" course
(https://github.com/lukebarousse/Python_Data_Analytics_Course).
I worked through the course notebooks to practise data cleaning and
analysis in Python. The code is based on the course. The data is the
course's 2023 data jobs dataset (Hugging Face: lukebarousse/data_jobs).

## Questions answered
1. What do the job postings look like (roles, countries, companies)? (1_EDA_Intro)
2. Which skills are most in demand for each data role? (2_Skill_Demand)
3. How did in-demand skills for Data Analysts change month by month in 2023? (3_Skills_Trend)
4. Which skills pay well and are also in demand? (5_Optimal_Skills)

## What I did
- Converted posting dates and turned the skills column from text into lists
- Handled missing skill and salary values
- Filtered to US Data Analyst jobs
- Used groupby, explode, merge and pivot tables to count skills
- Made charts with Matplotlib and Seaborn
