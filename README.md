# 🔎💵 Data_Science_Salary_Analysis
## ☞ Introduction  
This is a group project for the end of term in LIS 705 at the University of Wisconsin-Madison. The task is to analyze data science salaries. The dataset includes several key pieces of information such as job title, experience level, remote work ratio, and more. We chose this dataset to explore salary trends, the impact of remote work, and salary differences across countries. As future data analysts, understanding these patterns will help us prepare for the job market and make better career decisions.  

## ☞ Data Overview
### Columns Used in the Dataset  
1. **work_year**: Represents the year of employment.  
2. **experience_level**: Represents the level of work experience.  
3. **job_title**: The title of the job.  
4. **salary_in_usd**: Salary in USD.  
5. **remote_ratio**: The ratio of remote work.  
6. **company_location**: The location of the company.  
7. **company_size**: The size of the company.  
8. **employee_residence**: The residence of the employee.  
9. **is_cross_country**: Indicates if the employee works cross-country, determined by comparing `employee_residence` and `company_location` (i.e., `df_cleaned['employee_residence'] != df_cleaned['company_location']`).  
10. **salary_level**: Derived data, indicating the salary level (calculated or categorized).  
11. **role_category**: Derived data, categorizing the role (usually based on the job title or responsibilities).  
12. **avg_salary_per_role_and_company_size**: Summary data representing the average salary for each "role_category × company_size" combination.  

## ☞ Data Sources  
- [Dataset](dataset.csv)  

## ☞ For More Detailed Information  
For more detailed information on the project, please see the [document here](code.ipynb).
