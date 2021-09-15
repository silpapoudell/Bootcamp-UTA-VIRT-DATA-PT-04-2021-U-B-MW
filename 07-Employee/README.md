# Employee Database with SQL 

Create entity relationship diagrams,and perform data modeling and analysis on an employee database using SQL.


## Overview of the analysis:


The purpose of this analysis is to analyze past experience of the retiring employees by title and then show eligible employees to participate for mentorship program. 


<img width="500" src = "https://github.com/silpapoudell/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/07-Employee/Pewlett-Hackard-Analysis/images/mentoring_titles.png">


## Results:

- SQL query that shows Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955.

<img width="500" src="https://github.com/silpapoudell/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/07-Employee/Pewlett-Hackard-Analysis/images/retirement_titles.png">


- Because some employees may have multiple titles in the Retirement Titles table due to promotions, the DISTINCT ON statement was used to create a table that contains the most recent title of each employee.

<img width="500" src="https://github.com/silpapoudell/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/07-Employee/Pewlett-Hackard-Analysis/images/unique_titles.png">


- The Number of Retiring Employees by Title:

<img width="500" src="https://github.com/silpapoudell/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/07-Employee/Pewlett-Hackard-Analysis/images/retiring_titles.png">


- SQL query to create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965:


<img width="500" src="https://github.com/silpapoudell/Bootcamp-UTA-VIRT-DATA-PT-04-2021-U-B-MW/blob/main/07-Employee/Pewlett-Hackard-Analysis/images/mentoring_titles.png">




#Summary 

As we are analysing the eligible candidate for mentorship, it requires some sort of experience in particular domain(title). 
Images for supporting this project is attached in images folder here itself.  