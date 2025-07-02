# HR-Analytics-Tableau
In this project, the HR Manager wanted the development of an interactive Tableau dashboard that
provides both high-level summaries and detailed employee records for comprehensive workforce
analysis. The summary section is organized into three sections: Overview, Demographics, and Income
Analysis, which highlight the workforce composition, diversity, and salary distribution trends across
departments and job titles. To complement the summary insights, the dashboard includes a detailed
table listing all employees along with essential information such as name, department, job title,
gender, age, education, employment status, and salary. This dual-layered approach ensures that
users can easily switch between broad organizational views and granular employee-level data.

## Dataset
The human resource data has 8950 rows and 15 columns.
The columns are:
Employee_id,
First_name,
Last_name,
Gender,
State,
City,
Hiredate,
Department,
Job_title,
Education_level,
Salary,
Performance_rating,
Overtime,
Birthdate,
Termdate

## Loading and Transforming the dataset
Loaded the HumanResources-Kenyan data in Tableau and checked the columns and that the
data types are correctly listed.

![image](https://github.com/user-attachments/assets/7bf47d21-f8be-4829-9145-434fe0f5c593)


## Calculated Measures
Created measures such as total hired, total terminated, total active, %total hired, age, length
of hire etc.

![image](https://github.com/user-attachments/assets/4a642401-3de6-4b9f-883b-0ce1e12397b7)


## Build Visualizations
Visualized data by important features such as hired and terminated year, employees by departments, location, gender, salary, age, education level, and performance. 

#### Area chart of hired and terminated by year
The hiring rate in the company increased recently, while the termination rate decreased in
recent years.

![image](https://github.com/user-attachments/assets/1a23ace5-dcb3-45bb-9a25-fb8cb81f53b4)

![image](https://github.com/user-attachments/assets/325d489c-2916-46f6-b363-f3008ea53569)

#### Departments
The operations department has the largest number of employees.

![image](https://github.com/user-attachments/assets/684c0314-a2bf-4392-9a72-056abae2d710)

#### Location
A large number of employees work at the headquarters.

![image](https://github.com/user-attachments/assets/d19f63e7-4878-4743-ab0f-50c9046aa16f)

#### Map
Nairobi, which is the headquarters, has the most employees.

![image](https://github.com/user-attachments/assets/19459e63-c6c3-4175-81c8-133d2933c0d1)

#### Gender
The male and female employees are relatively balanced.

![image](https://github.com/user-attachments/assets/1dbf1d16-f071-4dc5-9dfe-ff6975d01a71)

#### Salary vs Age
The employees earning above the mean salary and their average age is less than 40, are of the job
titles: HR Manager, Operations Manager, Software Developers, while Finance Managers earn the
highest and are way older.

![image](https://github.com/user-attachments/assets/b6183023-ba90-4a7e-9ea3-b33c4eeb79fe)

#### Age vs Education Level
Most employees are in the age bracket of 35-44 and have a bachelor's degree.

![image](https://github.com/user-attachments/assets/db65163e-6e4f-4e0b-be22-144445aaa3a5)

#### Performance vs Education Level
51% of the employees are performing well in their jobs and have a bachelor’s degree.

![image](https://github.com/user-attachments/assets/ceac9f39-f880-4976-b8cb-99b5cd59d592)

## Dashboard
Created a compelling and interactive dashboard report from the analysis of the data set that
would speak clearly to the business needs for decision-making. 

![image](https://github.com/user-attachments/assets/8b629f51-aec3-4a80-8624-73470777ebfc)

![image](https://github.com/user-attachments/assets/992e65dd-0158-4a62-8dd1-88e7dd9ca350)



# Conclusion
The interactive HR dashboard provided valuable insights into the organization's workforce structure
and compensation trends. From the Overview section, it was observed that the company employs a
total of 8950 individuals, with the largest department being Operations, accounting for 27% of the
workforce.
Demographics analysis revealed a relatively balanced gender distribution, with 54% male and 46%
female employees. The majority of staff fall within the 35-44 age group, indicating a predominantly
mid-career workforce. Additionally, 61% of employees hold a bachelor's degree, followed by 20% with
a high school certificate, 14% with a master's degree, and 5% holding a PhD.
Income analysis showed that most employees earn within the mid-salary band (KES 79,900–100,000).
A role such as Finance Manager falls into the highest salary tier (above KES 125,000), and an HR
assistant earns the least income. Notably, PHD holders earn the highest salary, followed by Master's
holders.
Overall, the dashboard enables HR stakeholders to quickly identify patterns in workforce
demographics, assess departmental composition, and monitor income distribution for better strategic
planning and equitable policy development.
