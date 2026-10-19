DIVERSITY AND INCLUSION ANALYSIS

An interactive workforce analytics dashboard that turns complex HR data into clear insights on hiring, promotions, turnover, performance and age mix, to support informed people decisions.

Tools: SQL, Tableau
Domain: HR / People Analytics
Dataset: ~500 employee records (add the source, e.g. Kaggle or Maven Analytics)


BUSINESS PROBLEM

HR leadership needs to understand whether gender representation changes across job levels, where the gap appears, and whether performance explains it. The goal is to give stakeholders reliable, data-backed insights to guide workforce and talent decisions.

KEY QUESTIONS

What is the gender split in hiring?
How does female representation change from Junior Officer to Executive?
Are promotions and executive appointments balanced across genders?
Do performance ratings differ by gender?
What does the age profile of the workforce look like?

APPROACH

Data extraction and preparation: queried and transformed the HR data using SQL (joins, aggregations) and cleaned inconsistent records.
Data modelling: structured the data by employee, job level, department, region, age group and fiscal year (FY19 to FY21).
Analysis: compared gender mix at each job level, before and after promotion cycles, and tested performance ratings by gender.
Visualisation: built an interactive Tableau dashboard with filters for Department, Job Level, Region Level and Age Group.
Insights and recommendations: summarised findings into actions for HR stakeholders.

DASHBOARD SECTIONS

Hiring: gender split of hires and employee count by job level and gender.
Promotions: employee count and % female by job level after FY20 and FY21 promotions, plus average time in job level by gender.
Turnover: performance ratings of FY20 leavers by job level and gender.
Performance Rating: average rating by gender and rating distribution by gender.
Executive Gender Balance: gender split of executives, executive hires and promotions to executive.
Age Group: workforce distribution by age group and job level.

KEY FINDINGS

Hiring: 41% of hires are female and 59% are male.
Representation drops at every level: female share falls from 53% (Junior Officer) to 47% (Senior Officer), 37% (Manager), 18% (Senior Manager), 14% (Director) and 13% (Executive).
Biggest single drop: Manager to Senior Manager, about 19 percentage points.
Executive balance: women make up 12.5% of executives after FY20 promotions and 15.79% after FY21. All FY20 executive hires and promotions to executive were male.
Performance is not the driver: average rating is almost identical (2.42 female vs 2.41 male), so the gap is not explained by performance.
Workforce profile: most employees are aged 20 to 39, so the senior pipeline is thin overall.

CONCLUSION

Women are well represented at entry level but sharply under-represented at senior and executive levels, even though performance ratings are equal across genders. This points to a leadership pipeline and promotion issue, mainly at the Manager to Senior Manager transition.

RECOMMENDATIONS

Target the Manager to Senior Manager step with sponsorship, mentoring and succession planning.
Use diverse shortlists for senior and executive hiring and promotions.
Review promotion criteria and time-in-level for consistency across genders.
Track retention and turnover of high-performing women through regular reporting.
Improve data quality by resolving records with a blank job level.

DATA QUALITY NOTES

Some FY21 records have a blank job level and should be cleaned or investigated.
Figures are based on the sample dataset and are for portfolio and learning purposes.



SKILLS DEMONSTRATED

SQL, Tableau, Data Analysis, Data Visualisation, Data Modelling, Data Transformation, Data Quality, Problem Solving, Storytelling, Requirements Analysis
