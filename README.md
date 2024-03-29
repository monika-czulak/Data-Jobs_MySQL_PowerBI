# Job-Market_PowerBI
In this Power BI case study, I’ll explore a real-world job posting dataset to uncover insights for a fictional recruitment company called DataSearch. I’ll use Power Query to investigate and clean the data to find out what skills are most in-demand for data scientists, data analysts, and data engineers. Then I'll use DAX to build insightful visualizations of the findings. Finally, I’ll create a business dashboard so that I can answer questions for the DataSearch team.

## Dataset
Dataset is a part of DataCamp.com Case Study: Analyzing Job Market Data in Power BI.

## Steps
### Exploratory Analysis
- Data Import with Power Query - data types adjustment
- Initial EDA with Power Query - column distribution & profile
- Job posting trend analysis across years
- Data cleanup of job titles - focus on most relevant: Data Analyst, Data Scientist, Data Science Manager, Data Engineer, Machine Learning Engineer
- Effect of years experience on salary - create new column Average Pay, and new metric Average of Average Pay to determined avg salary trends for each job title

Findings:
1. Job postings for data science roles are raising in demand over years.
2. Out of five jobs to investigate, Data Engineers, Data Scientists, and Data Analysts are the most needed jobs.
3. Salaries are trending upward as expected.
   
### Analyzing Market Trends
- Cleanup and skills analysis - split skills from one column into separate rows
- Likelihood of skills in job posting - create new measures for skill count, postings count and then % Skill in Posting
- 
Investigate the following:
- Correlation between skills and job title
- Top industries and companies
- Potential recommendations to share with the client


