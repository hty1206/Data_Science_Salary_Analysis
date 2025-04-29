# 🔎💵 Data_Science_Salary_Analysis
## ☞ Introduction  
This is a group project for the end of term in LIS 705 at the University of Wisconsin-Madison. The task is to analyze data science salaries. The dataset includes several key pieces of information such as job title, experience level, remote work ratio, and more. We chose this dataset to explore salary trends, the impact of remote work, and salary differences across countries. As future data analysts, understanding these patterns will help us prepare for the job market and make better career decisions.  

## ☞ Data Overview
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

## ☞ Data Visualization  
- **Research Question 1:** How is the distribution of salary levels (Low, Medium, High) across different experience levels (Entry, Mid, Senior, Executive) and role types (Technical, Analytical, Managerial)?  
**Conclusion:** As experience levels increase, salary levels also rise significantly. Entry-level positions tend to have lower salaries, while senior and executive roles offer considerably higher compensation. Among the different job roles, managerial positions consistently have the highest salaries, reflecting the market value placed on leadership in the data science field. This suggests that both experience and role type are strong determinants of salary within the industry.  
<img width="950" alt="image" src="https://github.com/user-attachments/assets/e4b92ab8-27a3-46d4-b37d-dd93e08a97e2" />  
- **Research Question 2:** How did the proportion of remote work change from 2020 to 2023?  
**Conclusion:** The proportion of remote work saw a dramatic increase during 2020 and 2021 due to the pandemic, with both fully remote and hybrid models reaching their peak during this time. However, as the pandemic situation improved in 2022 and 2023, there was a decline in the proportion of remote work, with more companies either returning to in-office work or adopting a hybrid model. This shift highlights the temporary surge of remote work during the pandemic and suggests that companies are now finding a balance between remote and in-person work in the post-pandemic world.  
<img width="680" alt="image" src="https://github.com/user-attachments/assets/1739a19a-3602-4bcd-9a53-218c127b54fd" />  
- **Research Question 3:** What is the proportion of cross-border employment in the United States, Canada, Germany, and India?  
**Conclusion:** Germany had the highest proportion of cross-border employment, reflecting its strong global hiring practices and remote work opportunities. The United States had the lowest proportion of cross-border employment, indicating a more localized hiring approach. Canada and India showed moderate levels of cross-border employment, suggesting that both countries engage with global talent but to a lesser extent than Germany. These differences likely stem from variations in labor market conditions and recruitment strategies in each country.  
<img width="847" alt="image" src="https://github.com/user-attachments/assets/4f76b960-cd84-4f76-bddd-09fd5d5f7484" />  
- **Research Question 4:** Do larger company sizes tend to offer higher average salaries within the same role category?  
**Conclusion:** For managerial roles, we observed that small companies tend to offer higher salaries for entry-level positions, possibly due to their need to attract and retain managerial talent to drive growth. In contrast, medium-sized companies offered significantly higher salaries for experienced-level managerial employees, suggesting that they may have a stronger competitive edge in attracting top talent. Large companies, on the other hand, were less competitive in salary offers for both entry-level and experienced-level managerial roles. This finding indicates that company size can influence salary offerings, but the effect varies depending on experience level.
<img width="522" alt="image" src="https://github.com/user-attachments/assets/9385876b-1be3-4c5f-a069-275f048b47fe" />  
*We focused on managerial roles for the company size salary analysis because, compared to Technical and Analytical roles, managerial positions have a broader impact on a company's overall direction and performance.*  

## ☞ Data Sources  
- [Dataset](dataset.csv)  

## ☞ For More Detailed Information  
For more detailed information on the project, please see the [document here](code.ipynb).
