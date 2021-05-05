# DSI Project 1: SAT-ACT-Participation-Rate-Analysis-
-----------------------------------------
# Problem Statement

After the new SAT was released in 2016, it was found that some states were more likely to switch the standardized test to the SAT. The purpose of this project is to explore states that have converted to SAT with participation rate at 100% to look for what happens after they have changed.

# Executive Summary

To explore the participation rate of SAT and ACT, I used SAT and ACT datasets in 2017, 2018 and 2019. These dataset contains participation rate and all part of test score  in each US states. This project aims to explore the participation rate for SAT in each states after the new SAT has been released. Now, some states have switched from ACT to SAT, so I'm curious to find out how that change affects scores in that state. I also use an outside research in this analyze.

-----------------------------------------
# Data Dictionary

| Feature           | Type         | Dataset           | Description                                |
| :---------------: | :----------: | ----------------: | -----------------------------------------: |
|state             | object       | sat_all           | US State name                              |
|participation_17  | float        | sat_all           | The participation rate of SAT test in 2017 |
|ebrw_17           | int          | sat_all           |Average SAT Reading and Writing Score in 2017  |
|math_17           | int          | sat_all           |Average SAT Math Score in 2017              |
|total_17          | int          | sat_all           |Average SAT Total Score in 2017             |
|participation_18  | float        | sat_all           | The participation rate of SAT test in 2018 |
|ebrw_18           | int          | sat_all           |Average SAT Reading and Writing Score in 2018 |
|math_18           | int          | sat_all           |Average SAT Math Score in 2018              |
|total_18          | int          | sat_all           |Average SAT Total Score in 2018             |
|participation_19  | float        | sat_all           | The participation rate of SAT test in 2019 |
|ebrw_19           | int          | sat_all           |Average SAT Reading and Writing Score in 2019 |
|math_19           | int          | sat_all           |Average SAT Math Score in 2019              |
|total_19          | int          | sat_all           |Average SAT Total Score in 2019             |
|code              | object       | act_all           | US State code                              |
|state             | object       | act_all           | US State name                              |
|participation_17  | float        | sat_all           | The participation rate of ACT test in 2017 |
|english_17        | float        | sat_all           |Average ACT English Score in 2017           |
|math_17           | float        | sat_all           |Average ACT Math Score in 2017              |
|reading_17        | float        | sat_all           |Average ACT Reading Score in 2017           |
|science_17        | float        | sat_all           |Average ACT Science Score in 2017           |
|composite_17      | float        | sat_all           |Average ACT Composite Score in 2017         |
|english_18        | float        | sat_all           |Average ACT English Score in 2018           |
|math_18           | float        | sat_all           |Average ACT Math Score in 2018              |
|reading_18        | float        | sat_all           |Average ACT Reading Score in 2018           |
|science_18        | float        | sat_all           |Average ACT Science Score in 2018           |
|composite_18      | float        | sat_all           |Average ACT Composite Score in 2018         |
|english_19        | float        | sat_all           |Average ACT English Score in 2019           |
|math_19           | float        | sat_all           |Average ACT Math Score in 2019              |
|reading_19        | float        | sat_all           |Average ACT Reading Score in 2019           |
|science_19        | float        | sat_all           |Average ACT Science Score in 2019           |
|composite_19      | float        | sat_all           |Average ACT Composite Score in 2019         |

-----------------------------------------------------------------------------------------------------
# Outside Research

**Colorado**
   
- Participation rate for SAT increased from around 11% in 2017 to 100% 2018
- Since 2011, Colorado has required every high school junior to take ACT as their college entrance exam, but in 2015 a      selection committe composed of educators, counselors and administrators from diverse geographic regions across the state voted to adopt SAT as the required test.
- The English and Math of SAT test are aligned to the common standard of the Colorado Academic Standards.
- In 2015 College Board partnered with Khan Academy to provide free, personalized test prep for any student with computer access.

**Illinois**

- Participation rate for SAT increased from around 9% in 2017 to 99% in 2018 and 100% in 2019
- Illinois has use ACT for 15 years until 2018
- One of the reason that the state decides to change is because the state has changed the composition of its mathematics curriculum when Illinois adopted the Common Core State Standards for Mathematics.

**West Virginia**

- The West Virginia Department of Education announced Wednesday the SAT will be taken as the statewide summative assessment by high school juniors.
- Department of education said that each test presented a proposal to the decision-makers at the department and, the SAT made the most sense for the state.
- SAT test fees is cheaper
- Each year the cost per student is increasing reference to the ACT'fees.

**SOURCE**
- https://www.coloradokids.org/wp-content/uploads/2016/01/ACTvsSAT_FINAL.pdf
- https://opus.govst.edu/cgi/viewcontent.cgi?referer=https://www.google.com/&httpsredir=1&article=1333&context=capstones
- https://www.wsaz.com/content/news/All-WVa-high-school-juniors-to-begin-taking-SAT-exam-beginning-Spring-2018-444248263.html

----------------------------------------------------------------------------------------------------------------------------------------------------------
# Conclusions and Recommendations

Some states like Colorado, Illinois and West Virginia change their test from ACT to SAT in recent years for the reason that the test aligned to their academic standard. However, when we look at the score test for each state,it is found that after they have changed to SAT their SAT score in each part are decreasing in each year. In other hand, when we look at ACT composite score for these three states found that their composite score are increasing in each year.

This might be because of the participation rate that has negative correlation with the score, which mean that if the participation rate is increasing the test score will decreasing. This negative correlation have in both SAT and ACT test.

As we all know, these three states have been running the ACT test for a long time, switching to a different test can make students feel unfamiliar and result in a lower scores. Therefore, I would suggest that if any states want to change the standardized test, they should have a program that will make their student ready for a new kind of test.

