# Project_Head_Hunter: Resume Data Transformation for the HeadHunter Portal

## Table of contents
[1. Project Description](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#project-description)

[2. What case we are solving?](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#what-case-we-are-solving)

[3. Short data information](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#short-data-information)

[4. Project work stage](__)

[5. Result](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#result)

[6. Conclusions](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#conclusions)

### Project Description
* HeadHunter aims to develop a model capable of automatically estimating an applicant's approximate salary range based on the information provided in their resume. However, before building the model, the data must be thoroughly explored and cleaned

* We used following instruments in the project: Python (pandas, psycopg2), SQL
* We worked with 4 difrient tables: vacancies, employers, areas, industries.
:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#table-of-contents)

### What case we are solving?
The project consists of 4 main parts:

1 Preliminary Data Analysis: We performed an initial exploration of the data to identify its key characteristics and structure.

2 Detailed Job Analysis: Conducted an in-depth review of job postings to uncover the most common employer requirements and calculate average salaries

3 Employer Analysis: Identified the top 5 companies with the highest number of job postings.

4 Domain-Specific Analysis: Analyzed job postings related to Data Science (DS) professionals, including the number of requested skills, and calculated average salaries for both entry-level and experienced specialists.



**Competition conditions**


**Quality metric**
The goal of the project is to gain an understanding of the data and evaluate its alignment with the objectives for building a machine learning model.

**What we practice**
Throughout the project, SQL queries were used to interact with the database. All queries were documented and organized within a Jupyter Notebook.


:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#table-of-contents)

### Short data information
Job postings from the HeadHunter portal.

### Project work stage
1. Preliminary Data Analysis:
   1.1.  count the number of job postings in our database (vacancies table)
   1.2. count the number of employers (table employers)
   1.3. count the number of regions (table areas)
   1.4. count the number of industries in the database (table industries)
   Conclusions: We identified the main quantities in our databases
2. Detailed Job Analysis
   2.1. find out how many job postings (cnt) there are in each region (area)
   2.2. determine how many job postings have at least one of the two salary fields filled
   2.3. find the average values for the lower and upper salary range limits
   2.4. display the number of job postings for each combination of work schedule type (schedule) and employment type (employment) used in the job postings
   2.5. display the values of the "Required work experience" (experience) field
   Conclusions: We identified which jobs are offered.
3. Employer Analysis
   3.1. find out which employers are in the first and fifth positions by the number of job postings
   3.2. display the number of employers and job postings for each region
   3.3. for each employer, count the number of regions where they post their job vacancies
   3.4. count the number of employers who do not have an industry specified
   3.5. write a query to find the name of the company that is in third place in the alphabetical list (by name) of companies that have four industries specified.
   3.6. find out how many employers have "Software Development" listed as their industry
   3.7. for the company "Yandex," display a list of million-plus cities where the company has job postings, along with the number of job postings in each region
   Conclusions: We identified TOP-5 employers.
4. Subject Matter Analysis
   4.1. find how many job postings are related to data
   4.2. find how many job postings are suitable for a Junior Data Scientist
   4.3. find how many job postings are there for DS where SQL or Postgres is listed as a key skill
   4.4. check how popular Python is in employers' requirements for DS
   4.5. find average quantity of key skills are listed in job postings for DS
   4.6. calculate the average salary indicated for DS positions for each required experience level
   Conclusions: We identified quantity positions in data, number of requested skills and top skills, the salary randge for DS.
   
### Result
The final conclusions and outcomes of the project can be found [here](https://github.com/Evgi23/dst_gigio/blob/main/Projects/SQL/Project_2_eng.ipynb)



### Conclusions
In this project, we learned how to write SQL queries, properly document them in a notebook, create clear documentation, and successfully add another project to our portfolio.

:arrow_up: [To Table of contents](https://github.com/Evgi23/dst_gigio/tree/main/Projects/SQL#table-of-contents)
