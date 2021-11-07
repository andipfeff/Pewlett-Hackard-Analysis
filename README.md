# Pewlett Hackard Analysis

## Overview
An analysis was performed to look at the upcoming retirement eligibility for Pewlett Hackard's current employees. Using PostgresSQL, in pgAdmin4, queries were performed to determine how many employees were born between 1952-1955 and will be entering retirement age, along with a list of employees born in 1965 who would be eligible to participate in an upcoming mentorship program for the new staff resulting from the retirements. 

## Results
- Retirement Titles table was created to hold all employees born between 1952-1955

![retirement_titles_table](https://user-images.githubusercontent.com/90863226/140664460-b437079f-fdc0-4082-9605-4092562bd6b6.png)

- Unique Titles table was created from the above table to narrow down the list to the employees with their current title

![unique_titles_table](https://user-images.githubusercontent.com/90863226/140664555-b02e79fc-400c-443c-a091-98541ece3224.png)

-  Retiring Titles table was created to count the number of retirees by title

![retirement_by_title](https://user-images.githubusercontent.com/90863226/140658991-c969ac80-6792-4d94-95ae-ed085db02764.png)

- Mentorship Eligibility table was created to hold all employees born in 1965 that would be eligible to participate in the mentorship program 

![mentorship_eligibility_table](https://user-images.githubusercontent.com/90863226/140664676-f6141956-0618-4091-bf88-92d93e9320ba.png)

## Summary
The "silver tsunami" is about to create a huge wave of open positions within PH. There are just over 90,000 employees who are retirement eligible and will create open roles needing to be filled.  There are only just over 1,500 employees who are eligible to be in the mentorship program to mentor new employees. This leaves a very large gap to fill in terms of mentoring the new employees.

## Additional Analysis Recommendation
Due to the large number of upcoming retirees, I would highly recommend some additional analysis along with recalibrating the eligibility requirements for the mentorship program.

1. My first suggestion would be to create a new query that creates a table summarizing current employee counts by department and title and compare this to the upcoming retirees by department and title to get a better picture of where and how the "silver tsunami" is going to affect PH the most. This will also shed some light on how many lower-level employees there will be that may be eligible for promotions. I would suggest starting succession planning programs right away to mitigate the some of the pain when the "silver tsunami" hits. 

2. My second suggestion would be to alter the eligibility requirements for the mentorship program. I would refactor the current query to extend the birth year to look at employees born between 1960-1965 (and extend once more to 1970 if the numbers still do not come close to closing the gap). I would also limit the list to employees who have senior/leader/manager tiered titles, and who have been with the company for at least 5 years.
