# python-capstone
**Employee Data Analysis Project**

This project aims to analyze employee data from a company to uncover key insights and patterns related to employee distribution, salary expenditure, position allocation, and the relationship between age and salary. The analysis leverages data preprocessing, statistical techniques, and visualization to offer a comprehensive view of employee dynamics and trends. This report covers preprocessing steps, analysis tasks, graphical representations, insights gained, and any additional observations derived from the data.

**Dataset**

The dataset contains 458 rows and 9 columns describing various attributes of employees across different teams and positions. 
 https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link

**Preprocessing Steps**

Handling Missing or Inconsistent Data: The "height" column was identified as containing inconsistent or missing values. These values were replaced with random numbers between 150 and 180 to ensure consistency and integrity in the dataset.

**Data Cleaning:**

After the replacement of missing height values, the dataset was checked for any other inconsistencies. This step was critical to ensure that the data was ready for analysis without errors that could skew the results.

**Analysis Tasks**

1. Distribution of Employees Across Teams :The analysis identified how employees are distributed across various teams. Teams with the highest employee representation include the New Orleans Pelicans and Memphis Grizzlies, while teams like Minnesota Timberwolves and Orlando Magic had the smallest number of employees.
2.Percentage Split: The analysis calculated the percentage split of employees across each team relative to the total number of employees.
3. Employee Segregation by Position
The dataset was segmented based on employee positions such as SG (Shooting Guard), PF (Power Forward), PG (Point Guard), SF (Small Forward), and C (Center).
SG had the highest number of employees, while C (Center) had the lowest.
4. Predominant Age Group
The age distribution analysis revealed that the predominant age group was 20-30, which made up the largest portion of the workforce. The company predominantly hires younger employees, which might indicate a more dynamic and innovative work environment.
5. Team and Position with Highest Salary Expenditure
Cleveland Cavaliers emerged as the team with the highest salary expenditure at $106,988,689, and C (Center) was the position with the highest salary expenditure at $466,377,332.
This highlights teams and positions where the company invests the most in terms of compensation.
6. Correlation Between Age and Salary
The correlation between Age and Salary was calculated to be 0.21, indicating a weak positive correlation. This suggests that while older employees tend to earn more, age is not a strong predictor of salary, and factors like experience, position, and performance play more significant roles.

**Insights Gained**

Young Workforce: The majority of employees are in the 20-30 age group, indicating a young and potentially dynamic workforce.
Balanced Team Distribution: The employee distribution across teams is relatively even, with a few teams like Cleveland Cavaliers standing out in terms of employee numbers and salary expenditures.
Role-Specific Salary Trends: The C (Center) position requires specialized skill sets, reflected in the higher salary expenditure.
Low Correlation Between Age and Salary: Age has only a weak positive correlation with salary, suggesting that other factors (such as experience, position, and skills) play a more significant role in salary determination.

**Conclusion**

This analysis provides a clear understanding of employee distribution, salary allocation, and the relationship between age and salary within the organization. Key trends such as a young workforce and significant salary investments in certain teams and positions offer valuable insights into the company's structure and staffing strategy. The findings can help the company optimize resource allocation, improve workforce planning, and refine its salary structure based on a deeper understanding of employee dynamics.
