# Pewlit-Hackard-Analysis

## Overview of Analysis
The purpose of this analysis is to address the incoming “silver tsunami” of retiring aged employees that are currently employed by Pewlett Hackard. The project will collect the names of current employees born in the years of 1952 to 1955 and displays their employee numbers, their names, and their retiring title. In order to be prepared for which titles will be leaving the company, there is also a table that shows the amount of employees from each title that are retirement eligible. Finally, in order to train the new employees entering the company a full table of employees of a younger age eligibility has been collected in order to form a mentorship program. These projects demonstrate proficiency in manipulating large sets of data from multiple sources through SQL using the program Postgre Admin.

##Results
* There are a substantial number of Senior Engineers and Senior Staff that are of retiring age.
* There have been a significant number of Engineers and Staff who are of retiring age who left before retiring.
* There is a small number of retiring age managers.
* There are a larger proportion of the mentors that hold non-senior positions.
## Summary
The silver tsunami is an urgent matter that will drop a substantial amount of employees into retirement. According to the retiring titles table that was created the retiring numbers that will need to be replaced are as follows:

![image](https://user-images.githubusercontent.com/103979048/178896672-2ce8a609-0487-4661-8c52-0102c6249aeb.png)

By repeating the retiring counts query on the mentorship table, we can get an idea of how many eligible mentors there are at each title. 

![image](https://user-images.githubusercontent.com/103979048/178898750-36860d3a-877a-4909-a5b1-2b71511fdf11.png)


The number of mentors eligible for the program is only 1 to 5 percent of the number of retiring age staff members. This may be a problem as some mentors may need to mentor as many as 100 employees into significant positions. Additionally, there is not enough eligible mentors that are senior positions. Expansion of the mentorship program eligibility age to include those born in 1960-1965 would likely greatly increase the number of mentors available to train employees and would allow for at least 5 years before these mentors begin to age into retirement. 


Additionally, to understand how deeply this silver tsunami will affect Pewlett Hackard an additional set of queries should be added that will find the unique titles of all current employees and then make a table counting each title.

![image](https://user-images.githubusercontent.com/103979048/178898872-1cd51480-fcba-4f35-be84-c5018a8467ad.png) 

In doing this the magnitude of the silver tsunami starts to set in. The proportion of retiring age employees are as follows:
 30.16% of Senior Engineers
30.34% of Senior Staff
29.97% of Engineers
29.91% of Staff
29.88% of Technique Leaders
30.38% of Assistant Engineers
22.22% of Managers 
