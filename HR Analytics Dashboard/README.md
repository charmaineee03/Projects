## HR Analytics Project: Creating a Dashboard for Data Analysis 

The primary goal of this project is to analyze employee data and uncover patterns related to workforce demographics, performance, and attrition. To achieve this, I designed an interactive HR Analytics Dashboard that allows stakeholders to explore employee trends, monitor KPIs, and make data-driven HR decisions using Power BI. 
---

### Problem Overview 
In this modern world, organisations often face difficulties in managing and retaining their employees. Several corporate issues such as employee attrition, low job satisfation and low manpower can often affect the company's productivity and long-term growth. 

Hence, HR departments strive to investigate: 
- What are the key indicators to attrtion?
- Which department has the highest attrition rate?
- Does employee demographics influence workforce trends?

With that being said, this project aims to develop an HR Analytics Dashboard that consolidates employee data into an interactive and visual format. This allows HR leaders to be able to monitor key workforce metrics, identify at-risk groups in order to make proactive and informed deciosion making to improve employee's retention for their welfare and for the company's growth. 

### Dataset 
 - **Source**: HR Analytics Dataset (obtained from Kaggle) 

 This dataset consists of 1209 employees and 38 columns comprising several important attributes such as employee's demographics, job details, performance and company satisfaction, and status of attrition. 

 Before deploying an interactive dashboard, data preparation was initialised to improve accuracy. I utilised R for this process  to check and remove missing values and duplicates. A new csv file was created which consisted of the dataset after data cleaning. 

 In Power BI, the Attrtion Rate was created and calculated by dividing the Attrition Count by Employee Count. Other than that, Gender Ratio was also created by calcuting the ratio of men to women. This is to see if gender imbalance may play a role in the workforce distribution. 

### Dashboard Design: 

This dashboard consisted of two pages, "Overview" and "Attirtion". Several KPI cards was utilised such as the Attrition Rate, Work Job Satisfaction, Performance Rating and Gender Ratio to highlight several key workforce indicators. A slicer was included in the dashboard to allow a more interactive experience while mainfly focusing on specific departments to investigate their risks. 

The "Overview page" provides a well-rounded summary of the current workforce enviroment, displaying key employee demographics such as gender, age, and job position alongside with the key KPIs such as Gender Ratio and Work Job Satisfaction. 

Next, the "Attrtion" page primarily focuses on the current situation of employee turnovers. Essential visuals such as Attrition Headcount by Job Position, Attrtion by Gender and Age Group were incorporated to investigate the possibility of demographics-induced attrition. I also incorporated scatteerplots, to study the relationship of attrtion with key factors such as Job Satisfaction and Years Since Last Promotion. 

### Key Findings

- The **Sales department** has the highest attrition rate (21%),  compared to Human Resources and Research and Development. This coincides with the lowest average performance rating in Sales, suggesting the poor performance due to high turnovers.

- Attriton rates is **strongly correlated with lower job satisfaction scores**. This reinforces the need fot employee engagement initiatives from HR to increase employee retnetion. 

- **Employees with longer years since thier last promotion** exhibit higher rates of attrition. This may exhibit the importance of improvement in careeer advancement.

- There seems to be an **Age-related attrition**. Younger employees (26-35 years old) are more likely to leave, potentially due to lower salary bands and limited early career growth.

- **Male employees showed higher attrition rates** than female employees. This may be caused by differences in expectations and job scopes between the genders.

### Recommendations and Policy Interventions 

1. Implement targeted retention programs for Sales Department such as sales mentoring or performance suppport. For example, HR department can consider implementing higher rates of commission and reviewing their workload from time to time.

2. Conduct employee engagement surveys regularly to track satisfaction drivers of employees and investigate

3. Reconstruct the career progression system with a more structured promotion plan. HR needs to ensure that there is fair promotion policies, where every employee has the right to a promotion opportunity.

4. Review salary competitiveness as younger employees are leaving due to possible low salary band. Introduce more career opportunities to increase engagement such as mentorship, upskilling programs or recognition awards. 


