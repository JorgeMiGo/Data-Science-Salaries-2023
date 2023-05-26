# Data-Science-Salaries-2023
Salaries of Different Data Science Fields in the Data Science Domain

# Exploratory Data Analysis (EDA)

## Summary
The aim of this study is to investigate the factors influencing the salaries of Data Scientists. To achieve this, a dataset containing various relevant variables was utilized. This report describes the exploratory analysis conducted to understand the relationship between these factors and Data Scientists' salaries.

## Introduction
Data science is a rapidly growing field, and Data Scientists play a crucial role in analyzing and interpreting large volumes of data. As this profession becomes increasingly in demand, it is important to understand the factors that may influence Data Scientists' salaries. This analysis focuses on investigating these factors and their impact on salaries.

## Methodology
To conduct this analysis, a dataset containing relevant information about Data Scientists was used. The dataset includes the following variables:

1. `work_year`: The year the salary was paid.
2. `experience_level`: The experience level in the job during the year.
    - `EN` > Entry-level / Junior
    - `MI` > Mid-level / Intermediate
    - `SE` > Senior-level / Expert
    - `EX` > Executive-level / Director
3. `employment_type`: The type of employment for the role.
    - `PT` > Part-time
    - `FT` > Full-time
    - `CT` > Contract
    - `FL` > Freelance
4. `job_title`: The role worked in during the year.
5. `salary`: The total gross salary amount paid.
6. `salary_currency`: The currency of the salary paid as an ISO 4217 currency code.
7. `salaryinusd`: The salary in USD.
8. `employee_residence`: Employee's primary country of residence during the work year as an ISO 3166 country code.
9. `remote_ratio`: The overall amount of work done remotely.
10. `company_location`: The country of the employer's main office or contracting branch.
11. `company_size`: The median number of people that worked for the company during the year.

## Exploratory Analysis
Firstly, a descriptive analysis of the variables available in the dataset was conducted. The most frequent job roles, the distribution of experience levels, and the relationship between experience level and company size were examined. 
![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/bd06b97e-c391-4b7a-bf66-2ee8cba0b097)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/0256611d-7f74-47f5-8413-4e7d866f17d9)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/3672e87f-8b40-40ea-9869-ec65cac58370)


Additionally, the average highest salaries by job title and by country, along with the percentage of employees working abroad in each country, were analyzed.
![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/f01bc64b-90b8-4a11-9fa0-a6749f7123e0)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/028bc9a5-40c2-40b0-ae88-0dbdb228b5a6)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/980579b2-427a-4dc7-b63f-1f100aead4b3)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/cefcf092-8fa8-4c41-8e4a-af1d5b8655aa)


To focus the study on the most common job roles, the dataset was reduced to those representing over 80% of the population, reducing the number of job types from 93 to 8. These job roles included: Data Engineer, Data Scientist, Data Analyst, Machine Learning Engineer, Analytics Engineer, Research Scientist, Data Science Manager, and Applied Scientist. Subsequently, the highest salaries by job title and by country were reevaluated, as well as the percentage of remote work associated with each of these job roles.
![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/d9259fa1-03d0-4599-b3a9-6d304c050d48)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/63a14efd-134b-456b-847b-f662dcf7ee8d)

![image](https://github.com/JorgeMiGo/Data-Science-Salaries-2023/assets/127945994/d983db30-24fc-40e4-b13f-4e5c84d40621)



## Results Summary
- Among the most frequent job roles, Data Engineer, Data Scientist, and Data Analyst stood out prominently, with the highest presence.
- The most common experience level among data professionals was Expert, representing 67% of the sample, while the Director level accounted for only 3%.
- The highest average salary was for the position of Data Science Tech Lead, with a mean of over $350,000 per year, while the overall average salary was $137,570.
- Israel had the highest average salary by country, with a mean of over $250,000 annually, followed by Puerto Rico with a median salary of around $165,000.
- Regarding the presence of employees working abroad, India had the highest number of data professionals working overseas, followed by France.
- After reducing the dataset to analyze the most common job roles, it was observed that the highest-paying job within this subset was Data Science Manager, with an average salary of $190,000, while the lowest salary among these job roles was for Data Analysts, with $110,000.
- Puerto Rico had the highest average salary by country for this subset of job roles, with a mean of over $165,000 annually, closely followed by the United States.
- The only job role surpassing a remote work ratio of more than 50% was Analytics Engineer.

These results provide an overview of the most common job roles and associated salaries, as well as variations in salaries by country and the prevalence of remote work in the different analyzed job roles.
