# Pewlett Hackard Analysis

## Overview
An analysis was performed to look at the upcoming retirement eligibility for Pewlett Hackard's current employees. Using PostgresSQL, in pgAdmin4, queries were performed to determine how many employees within each job title will be at retirement age, along with a list of employees who will be eligible to participate in the upcoming mentorship program.

## Results
- Retirement Titles table was created to hold all employees born between 1952-1955

![retirement_titles_table](https://user-images.githubusercontent.com/90863226/140664460-b437079f-fdc0-4082-9605-4092562bd6b6.png)

- Unique Titles table was created from the above table to narrow down the list to the employees with their current title

![unique_titles_table](https://user-images.githubusercontent.com/90863226/140664555-b02e79fc-400c-443c-a091-98541ece3224.png)

-  Retiring Titles table was created to count the number of retirees by title

![retirement_by_title](https://user-images.githubusercontent.com/90863226/140658991-c969ac80-6792-4d94-95ae-ed085db02764.png)

- Mentorship Eligibility table was created to hold all employees born in 1965 that would be eligible to participate in the mentorship program 

![mentorship_eligibility_table](https://user-images.githubusercontent.com/90863226/140664676-f6141956-0618-4091-bf88-92d93e9320ba.png)

- 90,398 employees are about to retire
- 1,549 employees are eligible to participate in the mentorship program

## Summary
Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are just over 90,000 employees who are retirement eligible and will created open roles needing to be filled at PH.  There are only just over 1,500 employees who are eligible to be in the mentorship program to mentor new employees.

Additional tables/queries:
1. one
2. two
