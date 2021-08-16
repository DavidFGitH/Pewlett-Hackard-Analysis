# Pewlett-Hackard-Analysis
Employee Databases with SQL

## Overview of Project

To pull data on the number of retiring employees and identify employees that are eligible for the mentorship program.

### Purpose

We will use SQL to pull the number of retiring employees and count them based on their title. Then, we will pull the current employees born in the year 1965 to create a list of employees that qualify for mentorship program. Finally, we will do data analysis with the data.

## Results

![Retiring Titles](https://github.com/DavidFGitH/Pewlett-Hackard-Analysis/blob/main/Resources/Retiring%20Titles.png)
- According to the count of employees in the unique titles folder number to 90398, which is over 20% of all the employees contained among all the data. Looking at the above table, we can see the count of employees with the specified titles.

![Mentorship Titles](https://github.com/DavidFGitH/Pewlett-Hackard-Analysis/blob/main/Resources/Mentorship%20Titles.png)
- If we count the number of employees that are eligible for mentorship, the number we get is 1549 eligible employees. In the table above made separately we can see of the number of employees with a specific title.

- The distribution of the employees that qualify for the mentorship program is relatively on par with the employees that are retiring. However, counting the staff on mentorship program, we can see no managers as part of the mentors, while looking at the people at risk to retire have both managers from the data. Other than that, of the people potentially retiring, over 30% are going to be Senior Engineers and Senior Staff each, which is not to far from the distribution of employees with the same titles for the mentorship program.

- Both groups contain employees that worked since the year 1985, which is the oldest date in which employees started working for the company. This could make an interesting argument whether the focus of the mentorship program being date of birth should be reconsidered and mentorship based on experience in the company should be looked as a pool for candidates.

## Summary

As we found in our results, we can count over 90000 employees potentially retiring out of a total of about 400000, a little over 20% of the people in the list. This vastly outdwarfs the number of people that qualify for mentorship program, which is made up of around 1549 employees. Assuming the mentors are directly training to replace all the people that are potentially retiring, this means if each person that qualify for the mentorship program would have to mentor over 58 people to make up for all the people that would potentially retire. This doesn't even include the fact that none of them are Managers. One of the things that stood out was the emphasis on age versus experience working for the company. The pool of potential employees that qualify for the mentorship could be improved by creating queries to search for employees with the desired amount of experience using the from date, as well as increasing the age range of the mentorship program. We could also look for specific titles such as the senior positions from the potential pool of employees not close to retirement range to see if that could increase the number of people qualifying for the mentorship program. Finally, there still is the issue that we haven't counted the departments for the retiring employees and the mentorship eligible employees, which could be another point of interest for more queries and analysis.
