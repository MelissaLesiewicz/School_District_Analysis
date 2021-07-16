# School_District_Analysis
## Overview of Project
After recent state testing, I received the math & reading scores for all high school students in the city and was asked to analyze the test scores.  Using the average math and reading scores and the percentage of passing math, reading, and both math and reading scores I looked at outcomes for each school, per student spending, school size, and school type.
District wide there are 15 schools serving a total of 39,170 students with a total annual budget of $24,649,428.00. There are 7 district schools and 8 charter schools:

Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
15	39,170	$24,649,428.00	79.0	81.9	75%	86%	65%
![image](https://user-images.githubusercontent.com/86027932/125873439-fc4edbd6-6635-470e-b4c5-64b6fa247973.png)

After completeing the initial analysis we can conclude that charter shools have better testing outcomes than district schools regardless of their smaller per student spending.
Information to support this conclusion follows:

Top 5 Schools									
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Cabrera High School	Charter	1,858	$1,081,356.00	$582.00	83.1	84.0	94%	97%	91%
Griffin High School	Charter	1,468	$917,500.00	$625.00	83.4	83.8	93%	97%	91%
Pena High School	Charter	962	$585,858.00	$609.00	83.8	84.0	95%	96%	91%
Thomas High School	Charter	1,635	$1,043,130.00	$638.00	83.4	83.8	93%	97%	91%
Wilson High School	Charter	2,283	$1,319,574.00	$578.00	83.3	84.0	94%	97%	91%
![image](https://user-images.githubusercontent.com/86027932/125873776-69f30e68-3fc8-4616-a72a-a0982a282aa3.png)

Bottom Five Schools									
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Figueroa High School	District	2,949	$1,884,411.00	$639.00	76.7	81.2	66%	81%	53%
Rodriguez High School	District	3,999	$2,547,363.00	$637.00	76.8	80.7	66%	80%	53%
Ford High School	District	2,739	$1,763,916.00	$644.00	77.1	80.7	68%	79%	54%
Hernandez High School	District	4,635	$3,022,020.00	$652.00	77.3	80.9	67%	81%	54%
Huang High School	District	2,917	$1,910,635.00	$655.00	76.6	81.2	66%	81%	54%
![image](https://user-images.githubusercontent.com/86027932/125873889-c0b58a62-d769-4629-8aa0-f7b2c4a277a6.png)

School Type Summary					
School Type	Average Math Scores	Average Reading Scores	% Passing Math	% Passing Reading	% Overall Passing
Charter	83.5	83.9	94%	97%	90%
District	77.0	81.0	67%	81%	54%
![image](https://user-images.githubusercontent.com/86027932/125874061-d7747ad6-92fe-4c72-945d-0244ec76ad9f.png)

Outcomes by Spending per Student					
Spending Ranges (Per Student)	Average Math Scores	Average Reading Scores	% Passing Math	% Passing Reading	% Overall Passing
<$584	83.5	83.9	93%	97%	90%
$585-629	81.9	83.2	87%	93%	81%
$630-644	78.5	81.6	73%	84%	63%
$645-675	77.0	81.0	66%	81%	54%
![image](https://user-images.githubusercontent.com/86027932/125874182-99f946ec-164c-43dc-a53f-70df72034ed2.png)

Outcomes by School Size					
School Size	Average Math Scores	Average Reading Scores	% Passing Math	% Passing Reading	% Overall Passing
Small (<1000)	83.8	83.9	94%	96%	90%
Medium (1000-2000)	83.4	83.9	94%	97%	91%
Large (2000-5000)	77.7	81.3	70%	83%	58%
![image](https://user-images.githubusercontent.com/86027932/125874268-2827457a-6d93-4b52-a43e-3788da1c8302.png)

### Updated Outcomes
After completing the initial analysis, it was discovered that math and reading scores for 9th graders at Thomas High School appear to have been altered. I removed all scores for these students and redid the analysis excluding these students from the calculations. 

The subsequent calculations revealed that the manipulated test scores didn't make much of an impact on the overall outcomes per school or districy wide. Thomas High School remains the 2nd highest performing school in the district. 

The updated calculations:

Top Five Schools									
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Cabrera High School	Charter	1858	$1,081,356.00	$582.00	83.1	84.0	94	97	91
Thomas High School	Charter	1635	$1,043,130.00	$638.00	83.4	83.9	93	97	91
Griffin High School	Charter	1468	$917,500.00	$625.00	83.4	83.8	93	97	91
Wilson High School	Charter	2283	$1,319,574.00	$578.00	83.3	84.0	94	97	91
Pena High School	Charter	962	$585,858.00	$609.00	83.8	84.0	95	96	91
![image](https://user-images.githubusercontent.com/86027932/125874895-9a9cc9fa-76e5-4596-a96f-9393d21594a2.png)

Bottom Five Schools									
	School Type	Total Students	Total School Budget	Per Student Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Johnson High School	District	4761	$3,094,650.00	$650.00	77.1	81.0	66	81	54
Hernandez High School	District	4635	$3,022,020.00	$652.00	77.3	80.9	67	81	54
Huang High School	District	2917	$1,910,635.00	$655.00	76.6	81.2	66	81	54
Figueroa High School	District	2949	$1,884,411.00	$639.00	76.7	81.2	66	81	53
Rodriguez High School	District	3999	$2,547,363.00	$637.00	76.8	80.7	66	80	53
![image](https://user-images.githubusercontent.com/86027932/125875026-7e009587-911b-432b-a0bc-c124a796702d.png)

School Type Summary					
School Type	Average Math Scores	Average Reading Scores	% Passing Math	% Passing Reading	% Overall Passing
Charter	83.5	83.9	94%	97%	90%
District	77.0	81.0	67%	81%	54%
![image](https://user-images.githubusercontent.com/86027932/125875126-1918ed5f-7789-4eeb-9a5e-4bf085227c95.png)

Outcomes by Per Student Spending					
Spending Ranges (Per Student)	Average Math Scores	Average Reading Scores	% Passing Math	% Passing Reading	% Overall Passing
<$584	83.5	83.9	93	97	90
$585-629	81.9	83.2	87	93	81
$630-644	78.5	81.6	73	84	63
$645-675	77.0	81.0	66	81	54
![image](https://user-images.githubusercontent.com/86027932/125875260-3ce10763-f166-4d48-b79d-d3b766d6e023.png)

Outcomes by School Size					
School Size	Average Math Scores	Average Reading Scores	% Passing Math	% Passing Reading	% Overall Passing
Small (<1000)	83.8	83.9	94	96	90
Medium (1000-2000)	83.4	83.9	94	97	91
Large (2000-5000)	77.7	81.3	70	83	58
![image](https://user-images.githubusercontent.com/86027932/125875374-8fe36c10-5246-4a04-aa9c-570ac01c2794.png)

### Summary of Changes
Removing the math & reading scores from ninth graders at Thomas High School:
District Summary: no changes district wide
School Summary: 
•	Average Math Score ecreased by .07 points.
•	Average Reading Score decreased by .09 points.
•	% Students passing Math decreased by .08%.
•	% Students passing Reading decreased by .29%.
•	% Overall passing decreased by .32%.

Scores by Grade:
	Math: mean 9th grade math score for the district decreased by .25 points.
	Reading: mean 9th grade reading score for the district decreased by .09 points.
Scores by School Spending: Thomas High School spends $638/student, which puts them in the 2nd highest spending “bucket” per/student in the district. There was no impact on spending per student outcomes.
Scores by School Size: Thomas High School has 1635 students. There was no impact on school size outcomes for Middle Sized schools.
Scores by School Type: Thomas High School is a Charter School; there was no change in outcomes for Charter Schools.

### Analysis Summary
While it was important to remove these grades to maintain the integrity of the analysis, it made litle to now impact on the results of our analysis. Which remains that charter schools have better overall testing outcomes; while school size and spending per student seems to have very little to no impact on test scores.







