# Employee-Insights-and-HR-Analytics

## Project Overview
This project involves SQL-based analysis of employee data from an organization spanning from 2009 to 2022, focusing on key workforce dynamics such as retention rates, demographic distributions, and employee surveys. The queries emphasize key HR metrics across the employee lifecycle, including joining and exit trends, salary distributions, retention rates across different age groups and job levels, as well as employee feedback to support data-driven HR decision-making.


## Database Description
The database consists of three tables:

__Employee__: Contains information about employees, including their ID, joining date, job title, exit date, and other relevant details.

__Diversity__: Contains demographic information about employees, such as race, gender, and other diversity-related data.

__Survey__: Contains survey responses from active employees within the organization.

## Data Structure
![Description of the image](ERD.png)

## Tools and Technologies  
- __Query Language:__ SQL
- __Database Management System:__ PostgreSQL


## Key Features of the project

__1. Active Workforce Analysis:__
- Determines the number of active employees in the organization.

__2. Joining and Exit Trends:__
- Identifies peak joining dates and months.
- Analyzes the number of exits per month.

__3. Yearly Hiring Trends:__
- Examines hiring patterns over the years.

__4. Salary Insights:__
- Calculates average salaries by country and job level to assess pay equity and market competitiveness.

__5. Workforce Diversity Analysis:__
- Shows the percentage of active employees by education level.
- Provides insights into workforce composition.

__6. Departmental Breakdown:__
- Highlights the total number of employees per department and their proportional representation.

__7. Retention and Exit Analysis:__
- Computes retention rates across age groups.
- Analyzes average tenure of exited employees by age group.

## SQL Techniques Demonstrated
- JUSTIFY_INTERVAL, AVG, COUNT, GROUP BY, ORDER BY.
- date_part, COUNT, GROUP BY, ORDER BY.
- JOIN, window functions, PARTITION BY, percentage calculation.
- CASE WHEN, conditional aggregation, retention rate, GROUP BY.
