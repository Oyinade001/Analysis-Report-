**Introduction** 

This report presents a comprehensive analysis of employee demographics, workforce distribution, hiring trends and work arrangements, using the Human Resources dataset. The analysis aims to support data-driven HR decision-making by highlighting key workforce characteristics, identifying trends, and uncovering insights that guide strategic planning in recruitment and employee engagement.

**Objectives of the Analysis**

The major objectives of the analysis are to:
understand the demographic structure of employees 

examine departmental workforce composition  
	
assess employee location trends

evaluate hiring trends over time

measure workforce stability and engagement using indicators such as average employment duration and the status of employees (active vs inactive).

**Data Collection**

The data was downloaded online. Link to the dataset is presented below.

[Link to Dataset. ](https://drive.google.com/file/d/1dmBu3nE218tvf1pwV6M6Sc-14f1x85ZW/view?usp=sharing)

**Information/ Description of Dataset**

The dataset consists of 22214 rows and 13 columns. Each row consists of unique information about each employee while the columns include: 
Id, First Name, Last Name, Birthdate, Gender, Race, Department, Job Title, Location, Hire Date, Termination Date, Location City, Location State.
All the columns except Termination Date have complete data points. 82.3% of the Termination Date column was missing.

**Data Cleaning and Modification**

The dataset was clean so there were no data cleaning processes involved. However, data modification include addition of three columns namely: Age, Employment Duration, and Employment Status.

**Challenges**

The challenges faced while performing the analysis are as follows:
Missing values in the Termination Date column created confusion because it was hard to determine if employees with those missing values are still active or not. However, during the analysis, it was assumed that employees with the missing termination date are still active since they are not yet assigned termination date.
Also, in year 2000, the total number of hired employees was very low compared with other years. The reason for this sudden drop is unknown yet. Probably the company started operation in year 2000. 

**Result of the Analysis**

•	**Demographic Structure of Employees**

Age groups, gender distribution, racial diversity, and average age were examined to understand the demographic structure of employees.
Figure 1 shows the age group of employees in the organization. The chart revealed that the highest number of employees falls within age group between 30 and 39 years, while the smallest number of employees are between 20 and 29 years. However, the average age of the workforce is 41years. 
50.81% of the workforce is male, 46.46% is female while 2.72% is non-conforming (Figure 2).  

 <img width="446" height="264" alt="image" src="https://github.com/user-attachments/assets/f8bbd0f7-d8e2-44ed-8ef4-47cd1491b3a9" /> 

 Figure 1: Age group of employees

<img width="444" height="331" alt="image" src="https://github.com/user-attachments/assets/5a14ffa1-74f8-4e1c-b06e-72854d48c7d3" />

Figure 2: Percentage of Employees by Gender

To further understand the gender diversity in each department, analysis was carried out to show the distribution of gender in each department (Figure 3). Engineering Department had the highest percentage of females (20.33%), male (21.97%) and non-conforming (1.26%) which was followed by the Accounting Department with 9.97%, 11.15% and 0.59% of female, male and non-conforming respectively. The smallest percentage of male (5.59%) and female (5.14%) was in the training department while the smallest percentage  (0.27%) of non-conforming was in the Human Resources Department.   
Analysis on racial diversity also revealed that the White dominates the workforce in the organization while Native Hawaiian or Other Pacific Islander was the smallest racial group.

<img width="435" height="286" alt="image" src="https://github.com/user-attachments/assets/ccbc101a-7701-4baf-be0d-1be3eea4e2fe" />

Figure 3: Gender Distribution in each Department

<img width="452" height="277" alt="image" src="https://github.com/user-attachments/assets/a0319ffe-5cad-4cb5-af78-625ec6f54716" />

Figure 4: Distribution of employees by race   

•	**Departments and Job Titles**

Departmental workforce composition was examined by reviewing employee distribution per department, most common job titles, and gender balance within each department.
The most common Job Title was Research Assistant II (754) followed by Business Analyst (708) (Figure 5). The least Job Title is Account Executive (505).
Engineering (30.1%) and Accounting (15.0%) Departments have the highest workforce concentration while Auditing and Legal Departments constitute less than 2% each of the total workforce (Figure 6). 
Engineering and Accounting also have highest number of remote workers compared with other departments (Figure 7).

 <img width="496" height="303" alt="image" src="https://github.com/user-attachments/assets/5d65bc1a-865e-407d-8305-405b966ae64e" />

Figure 5: Most Common Job Titles

 <img width="491" height="373" alt="image" src="https://github.com/user-attachments/assets/a3a1192f-2768-4b7d-9751-384980b5ff3d" />

Figure 6: Percentage of employees in each Department

 <img width="453" height="279" alt="image" src="https://github.com/user-attachments/assets/d36099b0-57be-4989-b575-0dfcf4c96dba" />

Figure 7: Department with most Remote Workers

•	**Employment Duration & Turn over**

The average employment duration is 10 years and yearly hiring trend shows a stable pattern across the years except in year 2000 (Figure 8).
About 87% of the workforce are still active while 12.51% are inactive (Figure 9). 

 <img width="496" height="268" alt="image" src="https://github.com/user-attachments/assets/6b6cafd3-90a4-4e33-8197-150e70805cad" />

Figure 8: Total Number of Hired Employees Yearly

 <img width="465" height="326" alt="image" src="https://github.com/user-attachments/assets/4dcf6f00-5ed5-4c4a-b3f0-2e12da7037ec" />

Figure 9: Status of employees

•	**Work Arrangement & Location Insights**

The highest number of employees are located in Ohio (18,025), followed by Pennsylvania (1115) and Illinois (868). Some states such as Michigan and Kentucky have smaller employee populations compared with the rest (Figure 10). 75.25% of employees work onsite (headquarters), while 24.75% work remotely (Figure 11). Departments with the most remote workers include; Engineering, Accounting and Sales (Figure 7). 
 
 <img width="448" height="316" alt="image" src="https://github.com/user-attachments/assets/96394c8f-dc61-4e66-b125-8d027b6a27d1" />

Figure 10: Distribution of Employees by State

 <img width="498" height="314" alt="image" src="https://github.com/user-attachments/assets/9b3c8cea-87e9-42cd-a2ed-77463e8c3825" />

Figure 11: Employees’ Work Arrangement

**Take Away**

•	The average employment duration (10 years) indicates strong employee retention and long-term workforce stability.

•	Employees’ age distribution shows that majority (30-39 and 50-60 years) of the employees are experienced with strong mid-career representation.

•	Analysis also showed that the organization is racially diverse, however, the organisation is gender bias as only 2% of the employees represent the non-conforming gender.

•	There are high staffing needs in research, Business Analysis and HR

**Recommendations**

•	The organization should encourage entry level/graduate recruitment to balance age distribution and younger workforce.

•	Since there is success of remote work in departments such as Engineering, accounting and sales, the organization should encourage flexible work policies that allows remote role.	




