# Recruitment-analytics-of-USA JOBS

Used API to collect the data. Web APIs provide a means of communication between websites and users, structured by rules.
Requesting data using API is considered to be easier than web scraping technique, but trust me it was very difficult to convert 
“Complex Nested JSON” into a DataFrame. To get into a normal Data Frame consumed the maximum time.


It’s a US Government’s website for listing civil service job opportunities with federal agencies. 
This site is operated by United States Office of Personnel Management. 
There are are many different types of jobs available in federal service. I tried to obtain the jobs that are related to data science 
and data analytics. 

Number of columns : Jobtitle, OrganizationName, DepartmentName, Location, Country, PositionURL, ApplyURL, QualificationSummary, 
MinimumSalaryRange, MaximumSalaryRange, PublicationStartDate, ApplicationCloseDate, JobType, PositionOfferingType, JobSummary, Skillset, Experience Required

Data Preprocessing:

Most of the businesses collect real life data which is going to be raw data.Hence, it becomes a costly affair to do analysis using the raw data 
Therefore prepping the data by cleaning/scrubbing allows businesses to do better analysis which is also cost effective.
Data cleaning means finding and eliminating errors in the data. 
Data cleaning involved:
Dropping unwanted rows & columns : filtered certain JOb Titles out of 3000 records
Filling missing values with NA
Standardizing categorical column data

Data manipulation using Regex:
Created 2 new columns using the free text in Summary Column

Interpretation:
The range of salaries for Data Scientist is maximum compared to any other job titles.
The Job openings for Program Analyst is avaliable in almost all the sates.
