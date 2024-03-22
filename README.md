# HR Anaytics

### Dashboard Link : https://bi2developer-my.sharepoint.com/:u:/g/personal/sid-abhi0103_bi2developer_onmicrosoft_com/EXHFZzDYItpDtCo_GHTOi_UBSry-JkS50H9kVU5LfQ84Qg?e=HaO4Pg

## Problem Statement

The dashboard breaks down attrition by several factors including gender, education, age, years at company, salary, and job role. This data can be used to identify which groups of employees have the highest attrition rates. For example, the dashboard shows that employees with medical degrees have a much higher attrition rate (31.6%) than employees with technical degrees (5.6%).

Further analysis is needed to determine why these trends are occuring. Is there something about the work experience at company that is leading medical professionals to leave? Are there other factors, such as compensation or work-life balance, that are contributing to attrition among this group?

### Steps followed 

- Step 1 : Load the HR data containing employee information and their departure status (voluntary or involuntary) into Power BI Desktop. The data source can be a CSV file.

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.If necessary, select "column profiling based on the entire dataset" to ensure a comprehensive analysis.
  Identify and address any errors, empty values, or inconsistencies present in the data.

- Step 3 : In the report view, select a visually appealing theme that complements your company's branding or creates a professional presentation.

- Step 4 : Include slicers (visual filters) for relevant employee attributes that might influence attrition, such as department, job title, location, tenure, and compensation level. This allows users to explore trends within specific employee segments.

- Step 5 : Add card visuals to the dashboard to display key metrics related to attrition, such as: Overall attrition rate (percentage of employees leaving in a specific timeframe)    
     Time to replace an employee (average time it takes to fill a vacant position)
     Cost per hire (average financial resources spent on recruiting and onboarding new employees)
- Step 6 : Create bar charts or other visualizations to explore attrition rates across different employee categories. Examples include:
           
         Attrition rate by department,Attrition rate by tenure (years with the company),Attrition rate by age group.
- Step 7 : Consider enabling drill-down features within visualizations. This allows users to click on specific data points and access more granular details about that category. For instance, clicking on a department with high attrition might reveal reasons for employee departures within that department.
- Step 8 : Text boxes displaying insights or key findings based on the data analysis. Calculated columns or measures to create new insights, such as time to promotion or employee satisfaction ratings.
- Step 9 : Once your dashboard is finalized, publish it to Power BI Service to share it with relevant stakeholders within your organization. This allows for wider access and data-driven decision-making regarding employee retention strategies.
 
 # Report Snapshot (Power BI DESKTOP)

 
![HR ANALYTICS DASHBOARD](https://github.com/Sidhant-abhi/HR-Analytics-Report/assets/146129693/d54bcdd1-91e9-4c68-8d7c-942c3ee563be)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1]  Attrition Rate and Cost Analysis:
The overall attrition rate sits at 18.5%, exceeding the industry benchmark of 15%. This translates to 74 employees leaving the company annually. (Assuming a company size of 400)

The cost per hire metric reveals an average expense of $5,200. With the current attrition rate, this translates to a potential annual loss of $384,800 due to employee turnover.
           
### [2] Attrition by Department or Job Title:

The Marketing department has a concerning 25% attrition rate, significantly higher than the company average. This equates to 10 departing employees annually from a team of 40.

Software Developers, a critical role, show a 15% attrition rate, highlighting a potential talent gap that needs addressing.
  
 
  
  ### [3] Time to Replace Analysis:
 
 The current average time to replace an employee is 4.2 months. Coupled with the high attrition rate, this extended timeframe suggests inefficiencies in the recruitment process, potentially leading to additional costs and lost productivity.

 ### [4]  Tenure and Age Group Trends:
 
Employees within their first 2 years at the company exhibit a 22% attrition rate. This highlights the importance of focusing on onboarding and early-career development programs to improve retention.

The 25-34 age group has the highest attrition rate of 21%. Investigating the reasons behind this trend could be crucial for retaining younger talent.


## Recommendations
- Conduct an in-depth analysis of the Marketing department to identify factors contributing to the high attrition rate.

- Implement a targeted retention program for Software Developers, including competitive compensation packages and career development opportunities.
- Streamline the recruitment process to reduce the time to replace employees, potentially saving on costs and minimizing productivity gaps.
- Develop a robust onboarding program for new hires, particularly within the first two years, to enhance engagement and reduce early departures.
- Investigate the specific needs and motivations of the 25-34 age group to create a more attractive work environment and improve retention rates.


