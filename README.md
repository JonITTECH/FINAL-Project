![IronHack Logo](IronHackimage.png "IronHack Logo")

# Ironhack Final Project: Why do people leave their job?


**Author:** Jonatan Aguilera

**Course:** Data Analytics-Part Time | DA-PT-Oct-23 


## Introduction

In my current job as a headhunter, one of the most frequent conversations with clients is about the possibility of a new addition to their team leaving them soon. To address this, we rely on hundreds of conversations with candidates, as well as articles on the subject, in order to advise companies.

This project is a great opportunity to base our analysis on real data with abundant variables to analyze, as well as to create a predictive model that helps us understand the trend of employees leaving the company and their most significant reasons for doing so.

These are the main challenges I faced:
- Lack of sufficient samples for analysis and robust predictive modeling.
- Difficulty finding datasets with adequate variables for the intended measurements.
- Samples often insufficient and influenced by their origin or environment.
- Utilized a sample from IBM in the United States, making the analysis specific to that country.

Despite these drawbacks, we will focus on thoroughly analyzing our sample to find interesting relationships and will create the best possible predictive model.

## Table of Contents

- [Project Description](#project-description)
- [Project Workflow](#project-workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

The project consists of the exploratory analysis of the IBM workers dataset, where we aim to thoroughly understand the sample we have, the groupings we can make, and interesting data we can extract.

Once we have identified interesting relationships related to gender, marital status, department they belong to, overtime, etc., we will look at a model that helps us predict if an employee is going to leave us soon.



### Dataset

The dataset comes from a study conducted by IBM for its employees in the United States. It has a total of 1470 employees and 35 variables analyzed.

These are the variables:

- **Age**: The age of the employee.
- **Attrition**: Indicates whether the employee has left the company (`Yes` or `No`).
- **BusinessTravel**: Frequency of business travel for the employee (`Travel_Rarely`, `Travel_Frequently`, `Non-Travel`).
- **DailyRate**: The employee's daily salary rate.
- **Department**: The department the employee belongs to (`Sales`, `Research & Development`, `Human Resources`).
- **DistanceFromHome**: The distance from home to the workplace in miles.
- **Education**: The employee's level of education (1: 'Below College', 2: 'College', 3: 'Bachelor', 4: 'Master', 5: 'Doctor').
- **EducationField**: The field of study of the employee.
- **EmployeeCount**: A constant number indicating the count of employees. Can be dropped as it has the same value for all rows.
- **EmployeeNumber**: A unique identification number for the employee.
- **EnvironmentSatisfaction**: The employee's satisfaction level with their work environment.
- **Gender**: The gender of th
 employee.
- **HourlyRate**: The employee's hourly salary rate.
- **JobInvolvement**: The level of involvement the employee has with their job.
- **JobLevel**: The level of the employee's job (1: 'EntryLevel', 2: 'MidLevel', 3: 'SeniorLevel', 4: 'Manager', 5: 'Director').
- **JobRole**: The role of the employee in the company.
- **JobSatisfaction**: The employee's satisfaction level with their job.
- **MaritalStatus**: The marital status of the employee.
- **MonthlyIncome**: The employee's monthly income.
- **MonthlyRate**: The employee's monthly rate of payment.
- **NumCompaniesWorked**: The number of companies the employee has worked for.
- **Over18**: Indicates whether the employee is over 18 years old.
- **OverTime**: Indicates whether the employee works overtime (`Yes` or `No`).
- **PercentSalaryHike**: The percentage of salary hike the employee received.
- **PerformanceRating**: The performance rating of the employee.
- **RelationshipSatisfaction**: The employee's satisfaction level with their work relationships.
- **StandardHours**: A constant number indicating the standard number of working hours. Can be dropped as it has the same value for all rows.
- **StockOptionLevel**: The employee's level of stock options.
- **TotalWorkingYears**: The total number of years the employee has worked.
- **TrainingTimesLastYear**: The number of times the employee received training last year.
- **WorkLifeBalance**: The employee's work-life balance.
- **YearsAtCompany**: The number of years the employee has been with the current company.
- **YearsInCurrentRole**: The number of years the employee has been in the current role.
- **YearsSinceLastPromotion**: The number of years since the employee's last promotion.
- **YearsWithCurrManager**: The number of years the employee has been under the supervision of the same manager.


---


## Project Workflow

#### 2.1 EDA

#### 2.2 Data Wrangling

- Explore Data
- Clean Data
- Remove useless columns
- Plots
- Group Data
- Data Splitting

#### 2.3 Feature Selection

- Feature importance

### Train Models (ML)

- Logistic Regression
  - Also tried: Decision Trees, Random Forest, Support Vector Machines (SVM), Neural Networks

## Next steps
- Finding a dataset with valid and reliable surveys covering a larger number of employees.
- Finding a dataset that also includes the impact of teleworking on 'Attrition'.
- That the dataset consists of employees residing in Spain.
- That there is a greater difference in the sector of the companies where the employees work.

## Organization

 Organize a Project GitHub project board with main tasks  
 Create a repository including a Readme.md  
 Data Preparation  
 Modeling  
 Tuning  
 Tableau  
 Canva for presentation  
 Streamlit website with prediction model

## Links

Canva: https://www.canva.com/design/DAF__SQyVhY/Rf9eM7lXGewZiVmWOh6ZiA/edit?utm_content=DAF__SQyVhY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton  

Tableau: https://public.tableau.com/views/FINALPROJECT_17104369152550/JobRoleEmployeenumber?:language=es-ES&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

Website: through Tableau Dashboard
