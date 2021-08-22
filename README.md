# Pewlett-Hackard Analysis

## Overview
I analyzed a mock Pewlett-Hackard employee database to find out how many employees were close to retiring based on birth year. This information will help the company moving forward on assessing what to do about the amount of older employees that are entering retirement and how to keep the company surging forward into the future. I created an Entity Relationship Diagram (ERD) and used PostgreSQL to dig deep into the data.

## Results
I created 4 tables from the 6 CSV files provided by the company. The first 2 tables took the data and filtered it to retrieve all employees that are coming up on retiring and leaving the company. The third table took the second table and grouped them by employee titles. The last table was filtered to find all employees that could be eligible for a newly designed mentor program to help the company transition in this time into the future. 

<img width="504" alt="Screen Shot 2021-08-22 at 5 29 56 PM" src="https://user-images.githubusercontent.com/86524863/130370640-89e1ad15-32b6-4f4a-83e3-a3df27b7141f.png">

   - As we can see above, the largest group of employees coming into retirement are Senior Engineers at 29,414 while there are only 2 Managers coming into retirement soon. 
   - The total number of employees about to retire is 90,398 so something should be put in place now to help the company transition.


To help with the transition I analyzed the data and filtered it to find out how many employees would be eligible for a mentorship program in the table shown below:

<img width="1304" alt="Screen Shot 2021-08-22 at 5 31 00 PM" src="https://user-images.githubusercontent.com/86524863/130370739-aeb9217a-5582-4326-bb3a-389382bd0a77.png">

  - This table shows the employee name, employee number, how long they've worked for the company, and most importantly their title.
  - I queried these rows and found there are 1,550 employees eligible for the mentorship program. 

## Summary
Combining the data into filtered tables showed us that there are more than 90,000 employees close to retiring, but only around 1,500 are eligible for the mentorship program. This is concerning and should be handled with revising the mentorship program requirements. The company needs more people eligible so I recommend expanding the year born to include more employees that could then be eligible to enter the program. Increasing the year born from 1965 to 1960 would make over 93,000 employees eligible for the program. Since the most employees retiring are Senior Engineers, I queried the data and found that there are over 145,000 employees in the company that are engineers. My recommendation would be to look at promoting more engineers into senior positions and hiring young engineers to replace the positions they've left behind to help the company transition into the future. 
