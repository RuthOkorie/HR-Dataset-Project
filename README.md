# Employee Attrition Analysis 

## [Table of outline]
## [Project Overview](#project-overview)
## [Data Sources](#data-sources
## [Tools Used]
## [Data Cleaning and Preparation]
## [Exploratory Data Analysis]
## [Data Analysis] 
## [Visualisation]
## [Inference and Insight]
## [Recommendations for Reducing Attrition]
---
### Project Overview
The Employee Attrition Analysis is a data-driven visualization designed to uncover key insights into workforce attrition. This dashboard aggregates and presents data on employee turnover, department-based attrition, education level, gender distribution, age groups, and job roles to identify patterns and potential drivers of employee attrition.

### Data Sources
 The primary source of Data used here is HR Data.csv and this is an open source data that can be freely downloaded from an open source online such as kaggle. [Download here](http://www.kaggle.com) 

---
### Tools Used
- Microsoft Excel [Download Here](http://www.microsoft.com)
  1. This is used for initial data cleaning, formatting, and exploratory data analysis.
  2. It enabled me to pivot and analyze my data.
- Microsoft Power BI
  1. I leveraged Power Bi for data visualization and dashboard creation.
  2. This is used for transforming raw data into clear and insightful visuals.
- SQL
  1. This is used for querying and extracting relevant data from the the database.
  2. I employed SQL for  data manipulation.
- Google sheet     
  1. This is used to integrate multiple tools for comprehensive analysis.
  2. It is used to develop supplementary charts and graphs.
--- 
### Data Cleaning and Preparation
In the initial phase of Data cleaning and preparation, I perform the following actions;
  1. Data loading and inspection
  2. Handling missing values
  3. Data normalization
  4. Data cleaning and formatting
  5. Data quality check.
---
### Exploratory Data Analysis
EDA involves the exploring of the Data to answer some questions about the data such as;
  - What are the causes of attrition
  - What is the rate of attrition.
  - What is the attrition count by department
---
### Data Analysis 

This is where I include some basic line of codes, queries or even DAX expressions used during my analysis. 

 - Total Number of Employees: 1,470 employees in total.
 - Total Current Employees: 1,233 are still active, implying that 237 employees have left.
 - Attrition Count: 237 employees have left the company, indicating a significant turnover.
 - Attrition Rate: 16%, which is relatively high and might need attention.
 - Average Age: The average age of employees is 37 years, providing insight into the workforce demographic.

  ```SQL
SELECT * FROM TABLE 1
WHERE CONDITION = TRUE
```

---
### Visualisation

![attrition chart](https://github.com/user-attachments/assets/a114a4b2-98f1-4a3e-9daf-a163e1a22c5b)

![employee attrition dashboard](https://github.com/user-attachments/assets/1c949ebd-06da-47f8-bc8a-a564372ebdb3)

---
### Inference and Insight
This is where I provide key findings from the analysis

  1. High Turnover in R&D and Sales: Attrition in these departments highlights the need for role-specific interventions. This may include adjusting workloads, reviewing compensation, or providing more training opportunities.
  2. Younger Employees Leaving: Younger employees in the 25-34 age range are more likely to leave. This suggests the need for career advancement programs and competitive benefits that appeal to this demographic.
  3. Impact of Education on Attrition: High attrition among employees with advanced degrees (Bachelor’s and Master’s) may indicate a mismatch between job expectations and actual roles, pointing towards the need for career alignment.
  4. Attrition Rate: 16% of the workforce has left the company (237 employees out of 1,470). This percentage is relatively high, warranting further investigation into causes.
  5. Age Distribution: Average age is 37 years, indicating a mid-career workforce. Exploring attrition by age helps identify if younger or older employees are leaving at higher rates.
  6. Gender Distribution: Analysis reveals a higher attrition rate among male employees (63%), suggesting potential gender-specific issues impacting turnover.
  7. Education Level: Employees with Bachelor’s degrees exhibit the highest attrition rate, followed by Master’s degree holders. This could indicate dissatisfaction among those with higher qualifications, perhaps due to unmet career expectations. Moreover, it can suggest that the employees under these category are going for greener pastures.

### Recommendations for Reducing Attrition
 - Enhance Retention Programs in R&D and Sales: Given the high attrition rates in these departments, focus on improving employee satisfaction. Implement surveys to identify specific issues and offer targeted benefits or career development programs.

 - Reassess Role Alignment for Bachelor’s Degree Holders: The high attrition among Bachelor's degree holders suggests a possible mismatch between job roles and their career goals. Offering career growth opportunities, mentorship programs, or further training could reduce turnover in this group.

 - Increase Engagement for Younger Employees (25-34 Age Band): Younger employees have higher attrition rates, possibly due to limited advancement opportunities. Providing structured career paths, skill development workshops, and open communication channels for feedback may improve retention in this age group.

 - Address Gender Disparities: With higher attrition among males, explore if factors such as workplace culture, role expectations, or compensation structures contribute to the gender difference. Ensuring equitable treatment and tailored benefits could improve retention across genders.

 - Examine Job Role-Specific Issues: The high attrition in Healthcare Representatives suggests job dissatisfaction. Conduct exit interviews or satisfaction surveys in this role to understand root causes and address potential challenges like workload, work-life balance, or compensation.



   
