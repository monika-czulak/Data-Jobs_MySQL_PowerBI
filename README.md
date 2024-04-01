# Job-Market-Analysis_PowerBI
In this case study, I explored a real-world job posting dataset to uncover insights for a fictional recruitment company called DataSearch. I used Power Query to investigate and clean the data to find out what skills are most in-demand for data scientists, data analysts, and data engineers. Then I used DAX to build insightful visualizations of the findings. Finally, I created a business dashboard so that I could answer questions for the DataSearch team.

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
- Cleanup and skills analysis - split skills listed in one column into separate rows
- Likelihood of skills in job posting - create new measures for skill count, postings count and then % Skill in Posting
- Trends in skills over time
- Experience analysis across different industries and job positions
- Job titles with similar requirements

### Building job market analysis dashboard
Q: Who is the audience? </br>
A: DataSearch recruiters </br></br>
Q: What do they need? </br>
A: Identify optimal opportunities for qualified candidates </br></br>
Q: How can a dashboard help? </br>
A: Transform insights from this data into a usable form for the recruiters </br></br>

Dashboard is a combination of already prepared charts presented in four pages: Home, Jobs, Skills, and Company. Home page contains links to the main pages. Main pages contain link to the Home page. There is a filter pane on the left enabling to narrow down the results, and also search by date. The visual aspect has been provided by using personalized backgrounds designed in MS PowerPoint.

## Summary
My dashboard streamlines the recruitment process for DataSearch recruiters by centralizing key information and providing actionable insights. It empowers recruiters to make data-driven decisions, optimize candidate searches, and ultimately find the perfect candidates for job postings more efficiently.
