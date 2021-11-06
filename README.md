# Salary-Prediction

## Define
The objective of Salary Prediction project are to perfrom EDA, create models and  uncover factors that contribute most to the salary

## Discover
- Tools Used : Google Colab
- Packages : pandas, numpy, matplotlib, seaborn, sklearn
- Directories : datasets - test, train data used in the project, images - Graphs of EDA and models

**Data**

train_features.csv: Each row represents an observation for each individual job posting. The "jobId" column is unique to each job posting and the other columns are the different features of the job postings. The file has eight(8) columns.

train-salaries.csv: Each row is a unique job posting with its corresponding salary. The file contains two (2) columns. The file is combined with train_features.csv to train the machine learning models.

test_features.csv: Similar to train_features.csv, each row in this file is metadata for each individual job posting. The file has eight (8) columns and is used to predict the new salaries. 

**Features**

jobId : unique identifier for each job positing.

companyId : unique identifier for each company posting the job position.

jobType : Type of job position. It contains 8 different categories - CEO, CFO, CTO, Janitor, Junior, Manager, Senior, Vice President.

industry : Job field. It contains 7 different categories - Health, Web, Auto, Finance, Education, Oil, Service.
		   
degree : Highest eduction obtained. It consists 5 different categories - None, High School, Bachelor's, Master's, Doctoral.
		   
major : Degree major. It contains  9 unique categories - None, Literature, Biology, Chemistry, Physics, Computer Science, Math, Business, Engineering.
		   
yearsExperience : Experience in years.

milesFromMetropolis : Distance from the Metropolitan city, in miles. 

salary : Target variable. Salary paid in thousands US dollars. 

**EDA**
Salary Distribution
![images](https://github.com/min-tee/Salary-Prediction/blob/af47add8e46a1290d559eb301869e34444e0a52f/images/salary_dist.png)

Salary vs Features

Degree : ![degree] (https://github.com/min-tee/Salary-Prediction/blob/fefa8e64c7f47780b179644c6d58ed239d627fe7/images/salary_vs_degree.PNG)



