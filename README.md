# 🔎💵 Data_Science_Salary_Analysis
## ☞ Introduction  
This is a group project for the end of term in LIS 705 at the University of Wisconsin-Madison. The task is to analyze data science salaries. The dataset includes several key pieces of information such as job title, experience level, remote work ratio, and more. We chose this dataset to explore salary trends, the impact of remote work, and salary differences across countries. As future data analysts, understanding these patterns will help us prepare for the job market and make better career decisions.  

## ☞ Data Overview
| **Column Name**                          | **Description**                                                                                             |
|------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| **work_year**                            | Represents the year of employment.                                                                          |
| **experience_level**                     | Represents the level of work experience.                                                                     |
| **job_title**                            | The title of the job.                                                                                        |
| **salary_in_usd**                        | Salary in USD.                                                                                                |
| **remote_ratio**                         | The ratio of remote work.                                                                                    |
| **company_location**                     | The location of the company.                                                                                 |
| **company_size**                         | The size of the company.                                                                                     |
| **employee_residence**                   | The residence of the employee.                                                                               |
| **is_cross_country**                     | Indicates if the employee works cross-country, determined by comparing `employee_residence` and `company_location` (i.e., `df_cleaned['employee_residence'] != df_cleaned['company_location']`). |
| **salary_level**                         | Derived data, indicating the salary level (Low, Medium, and High).                                       |
| **role_category**                        | Derived data, categorizing the role (Managerial, Technical, and Analytical).                   |
| **avg_salary_per_role_and_company_size** | Summary data representing the average salary for each "role_category × company_size" combination.           |
  

## ☞ Data Visualization

- **Research Question 1:** How is the distribution of salary levels (Low, Medium, High) across different experience levels (Entry, Mid, Senior, Executive) and role types (Technical, Analytical, Managerial)?

  **Conclusion:** Salary levels increase with experience. Entry-level positions have lower salaries, while senior and executive roles offer higher compensation. Managerial roles consistently have the highest salaries, reflecting their leadership value in the industry.

  ![Salary Distribution](https://github.com/user-attachments/assets/e4b92ab8-27a3-46d4-b37d-dd93e08a97e2)

- **Research Question 2:** How did the proportion of remote work change from 2020 to 2023?

  **Conclusion:** Remote work surged in 2020 and 2021 due to the pandemic, reaching a peak. However, as the pandemic situation improved, remote work declined in 2022 and 2023, with more companies adopting hybrid or in-office models.

  ![Remote Work Trends](https://github.com/user-attachments/assets/1739a19a-3602-4bcd-9a53-218c127b54fd)

- **Research Question 3:** What is the proportion of cross-border employment in the United States, Canada, Germany, and India?

  **Conclusion:** Germany had the highest proportion of cross-border employment, while the U.S. had the lowest. Canada and India showed moderate levels, likely due to differences in labor market conditions and recruitment strategies.

  ![Cross-Border Employment](https://github.com/user-attachments/assets/4f76b960-cd84-4f76-bddd-09fd5d5f7484)

- **Research Question 4:** Do larger company sizes tend to offer higher average salaries within the same role category?

  **Conclusion:** Small companies offered higher salaries for entry-level managerial roles, likely due to the need for managerial talent. Medium-sized companies offered the highest salaries for experienced-level managerial employees, while large companies were less competitive in salary offerings.

  ![Company Size Salary Comparison](https://github.com/user-attachments/assets/9385876b-1be3-4c5f-a069-275f048b47fe)

  *Note: We focused on managerial roles for this analysis, as they have a broader impact on a company's performance compared to technical and analytical roles.*
 

## ☞ Data Sources  
- [Dataset](dataset.csv)  

## ☞ For More Detailed Information  
For more detailed information on the project, please see the [document here](code.ipynb).
