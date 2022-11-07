# Pewlett-Hackard-Analysis

## Overview of the analysis:
### The Purpose of the Analysis
To determine the number of retiring employees per title and identify employees who are eligible to participate in mentorship program. These determinations will help management prepare for the "silver tsunami", in which many current employees will reach retirement.

## Results:
### Four Major Points from Analysis
![Image](images/retiring_titles.png)
- From the query titled "distinct_retire_titles", 72,458 people are currently up for retirement at Pewlett-Hackard based on a birthdate criteria for people born between January 1, 1952 and December 31, 1955.
- From the query titled "retiring_titles", The largest group, at about 36%(25,916) of the people retiring hold the title Senior Engineers. Senior Staff follows as the second largest group at about 34%
- There are only 2 managers who are eligible for retirement.
![Image](images/mentorship_eligibility_table.png)
- 1,549 people are eligible to be mentors based on the criteria that they are still working for the company and were born in 1965.

## Summary:
### Questions
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Out of the 240,124 people (data found in current_dept_emp querie) who currently work for Pewlett-Hackard, 72,458 of them are eligible for retirement. Of those eligible to reiture, 70% of them are either Senior Engineers or Senior Staff. 


Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
There are only 1,549 employees who are eligible for mentorship program. In comparison to the amount retireing, I would conclude there are not enough to mentor all of the new positions. 

### Additional Queries
- the count of titles in mentorship program, titled 'mentor_title'.
![Image](images/mentor_title_image.png)
- current employees working based on to_date being '9999-01-01' which is titled 'current_dept_emp'.
![Image](images/current_dept_emp_image.png)
