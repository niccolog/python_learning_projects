# Job Salary Research
## Project Overview
### Project Goal
Understand the current job market for data/scientists roles, the objective is feeding these datapoints into a ML model to and understanding how much my own resume is worth and I should demand as a fair compensation for my services.
### Tenets
We are going to look into salaries for different job roles at individual contributor level:
- Applied Scientists
- Research Scientist
- Data Scientists
- ML Scientists/Engineers
- Data Analysts
- Business Intelligence Engineers
- Business Analysts
### Data Sources
We are going to use Glassdoor and scrape it with Selenium. We are not going to use Linkedin as we don't have a ready to go scraper as we do for Glassdoor. Also LinkedIn does not provide salary ranges like Glassdoor does.
This project should be revisited in the future to account for Linkedin job salary estimates as well.
We will follow some steps from [Ken Jee's Github project](https://github.com/PlayingNumbers/ds_salary_proj).
### Data Description
We are initially interested in looking at:
- Job Title/Position Estimate
- Job Description
- Hard Skills required
- YoE
- TC/BC
- Location
- Industry
- Size
- Company Age
- Rating
- Headquarters
- Shareholders: Private vs Public
- Company Size (Revenues)
- Competitors
## Project Findings
![](https://github.com/niccolog/python_learning_projects/blob/main/own_projects/Job_salary_search/avg_salary_seattle.png)

![](https://github.com/niccolog/python_learning_projects/blob/main/own_projects/Job_salary_search/job_corr.png)
## Project Conclusions
Based on the data observed a Sr Data Scientist should command at least a $160k base salary. Looking into specific skills did not flag any edge on salary.
