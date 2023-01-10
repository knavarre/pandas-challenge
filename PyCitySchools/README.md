# PyCity Schools Data Analysis 
By Kiana Navarre

**Programming Language Used: Python/Pandas**

## Description
This project combines 2 data sets, both looking at the same schools, to examine if school size, budget, and type (public district or charter) has any notable influence on those schools reading and math scores.  This combined dataframe is then used to examine the factors listed below. 

## Analysis Summary
- Contrary to expectations, the amount spend per student had a negative relation to overall student grades.  Students in the <$585 spending per student category had an overall passing percentage of of 90.37% and students in the $645-680 spending per student category had an overall passing percentage of 53.53%
- Large schools had significtanly lower passing grades than both the Medium and Small Size schools.  Large schools having an overall passing percentage of 52.29% and the medium and small schools having overall passing percentages of 90.62% and 89.88% respectively.  
- Charter schools had significanly higher passing grades than District schools, both in overall scores and math scores. Charter schools having a passing math percentage of 93.62% and an overall pssing percentage of 90.43%, whith District schools having a passing math percentage of 66.55% and an overall pssing percentage of 53.67%.

## PyCity School Analysis Details: 
These conclusions were made by looking at the results of the analses listed below. 

### District Summary
This summary examines the following data for all schools in the district: 
- Total Schools
- Total Students
- Total Budget 
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading 
- % Overall Passing 

### School Summary
This summary examines the following data for all schools in the district individually: 
- School Type 
- Total Students
- Total School Budget
- Per Student Budget
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading 
- % Overall Passing 

### Highest-Performing Schools (by % Overall Passing)
This table shows the school summary data for the top 5 highest performing schools by % Overall Passing.  The top school revealed to be "Cabrera High School" with an Overal Passing percentage of 91.335%.   

### Lowest-Performing Schools (by % Overall Passing)
This table shows the school summary data for the bottom 5 performing schools by % Overall Passing.  The bottom school revealed to be "Rodriguez High School" with an Overal Passing percentage of 52.988%.


### Math and Reading Scores by Grade
The two tables in this section break down the math and reading scores for all schools in the district by grade.  

### Scores by School Spending
This summary examines the following data for all schools in the distrinct with relation to the amount spend per stunent per school:
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading 
- % Overal Passing

The spending ranges (per student) used in this analysis are:
- <$585
- $585-630
- $630-645
- $645-680

### Scores by School Size
This summary examines the following data for all schools in the distrinct with relation to school size:
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading 
- % Overal Passing

The school sizes were defined as:
- Small (< 1000 students)
- Medium (1000-2000 students)
- Large (2000-5000 students)

### Scores by School Type 
This summary examines the following data for all schools in the distrinct with relation to school type (charter or district):
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading 
- % Overal Passing