# Salary-Prediction

.

## Stratregy : 4D of Data Science 

**Define** 
- The objective of Salary Prediction project are to perfrom EDA, create models and  uncover factors that contribute most to the salary

**Discover**
- Tools Used : Google Colab
- Packages : pandas, numpy, matplotlib, seaborn, sklearn
- Directories : datasets - test, train data used in the project, images - Graphs of EDA and models
- Data
*train_features.csv*: Each row represents an observation for each individual job posting. The "jobId" column is unique to each job posting and the other columns are the different features of the job postings. The file has eight(8) columns.

train-salaries.csv: Each row is a unique job posting with its corresponding salary. The file contains two (2) columns. The file is combined with train_features.csv to train the machine learning models.

test_features.csv: Similar to train_features.csv, each row in this file is metadata for each individual job posting. The file has eight (8) columns and is used to predict the new salaries. 

## Features

* JobId: unique identifier for each job positing
* companyId: unique identifier for each company posting the job position
* jobType: type of job position (e.g janitor, manager, CEO)
* degree: highest degree earned (e.g Bachelor, Doctoral)
* major: major of the degree obtained (e.g. Businesss, Literature, engineering)
* industry: field or industry of the job posting (e.g education, oil, finance)
* yearsExperience: years of experience required/obtained for the job
* milesFromMetropolis: distance away from the metropolis, in miles(mi)
* salary: salary paid for the job, in thousands US dollars; target variable



# Salary Distribution
![images](https://github.com/min-tee/Salary-Prediction/blob/af47add8e46a1290d559eb301869e34444e0a52f/images/salary_dist.png)



