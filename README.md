# Salary Analysis and Insights - README

This repository contains a Python script for analyzing salary data using the pandas library. The script reads a CSV file containing salary information and performs various analyses to extract insights about employee salaries and related factors. Here's a breakdown of the script and its functionality:

## Prerequisites
- Python 3.x
- pandas library

## Getting Started
1. Clone the repository or download the script file (`salary_analysis.py`).
2. Ensure that the `ds_salaries.csv` file is present in the same directory as the script.

## Functionality
The script performs the following analyses and provides insights into the salary data:

1. **Which role has the highest salary employment wise?**
   - Calculates the average salary for each job title and employment type.
   - Identifies the job titles with the highest average salary for each employment type.

2. **Which employment types do employers prefer to hire?**
   - Counts the occurrences of each employment type.

3. **Which role are entry level employees generally hired for?**
   - Filters the DataFrame to include only entry-level employees.
   - Counts the occurrences of each job title among entry-level employees.

4. **Which countries pay the highest for which roles?**
   - Calculates the mean salary for each job title in each country.
   - Identifies the job titles with the highest mean salary in each country.

5. **What insights can you find regarding employee demographics?**
   - Determines the percentage of employees residing in the same location as the company.
   - Calculates the mean salary for the top 5 company locations with the highest mean salary.
   - Analyzes the distribution of work culture ratios.

6. **Which experience level has the highest hiring?**
   - Counts the occurrences of each experience level.

7. **Does company size affect the rate of hiring and pay scale?**
   - Calculates the number of hires and hiring rate for each company size.
   - Calculates the mean salary and growth rate for each company size.

8. **What is the year over year (YoY) salary growth at different levels?**
   - Calculates the mean salary for each experience level and work year.
   - Calculates the salary growth rate (percentage change) for each experience level.

## Additional Information
- The script assumes that the `ds_salaries.csv` file follows a specific format with columns like 'employment_type', 'job_title', 'salary_in_usd', etc. Make sure the file matches the expected format.
- The script provides various insights into the salary data and can be customized or extended based on specific requirements.

Feel free to modify and enhance the script according to your needs. If you have any questions or suggestions, please don't hesitate to reach out. Happy analyzing!

Aayush Doshi.

