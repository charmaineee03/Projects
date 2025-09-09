## HR Analytics Project: Creating a Dashboard for Data Analysis 

The primary goal of this project is to analyze employee data and uncover patterns related to workforce demographics, performance, and attrition. To achieve this, I designed an interactive HR Analytics Dashboard that allows stakeholders to explore employee trends, monitor KPIs, and make data-driven HR decisions using Power BI. 

### Problem Overview 
In this modern world, organisations often face difficulties in managing and retaining their employees. Several corporate issues such as employee attrition, low job satisfation and low manpower can often affect the company's productivity and long-term growth. 

Hence, HR departments strive to investigate: 
- What are the key indicators to attrtion?
- Which department has the highest attrition rate?
- Does employee demographics influence workforce trends?

With that being said, this project aims to develop an HR Analytics Dashboard that consolidates employee data into an interactive and visual format. This allows HR leaders to be able to monitor key workforce metrics, identify at-risk groups in order to make proactive and informed deciosion making to improve employee's retention for their welfare and for the company's growth. 

### Dataset 
 -**Source**: HR Analytics Dataset (obtained from Kaggle) 

 This dataset consists of 1209 employees and 38 columns comprising several important attributes such as employee's demographics, job details, performance and company satisfaction, and status of attrition. 

 Before deploying an interactive dashboard, data preparation was initialised to improve accuracy. I utilised R for this process  to check and remove missing values and duplicates. A new csv file was created which consisted of the dataset after data cleaning. 

 In Power BI, the Attrtion Rate was created and calculated by dividing the Attrition Count by Employee Count. Other than that, Gender Ratio was also created by calcuting the ratio of men to women. This is to see if gender imbalance may play a role in the workforce distribution. 

### Dashboard Design: 


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

4. Review salary competitiveness, 



📌 Recommendations Based on Findings
1. High Attrition in Sales Department

Finding: Sales has the highest attrition rate (21%) and lowest average performance rating.

Recommendation: Implement targeted retention programs such as sales mentoring, clearer career paths, and performance support. Consider reviewing workload and commission structures to improve engagement.

2. Attrition Increases with Longer Promotion Gaps

Finding: Employees are more likely to leave when they have not been promoted for several years.

Recommendation: Develop a structured promotion and career progression plan. HR should ensure fair and transparent promotion policies, with regular skill development opportunities to keep employees engaged.

3. Younger Employees (26–35) More Likely to Leave

Finding: Younger staff, especially in lower salary bands, have higher attrition.

Recommendation: Review salary competitiveness for early-career employees and introduce career development initiatives (mentorship programs, training, upskilling opportunities).

4. Higher Attrition Among Male Employees

Finding: Male employees show a higher attrition rate compared to females.

Recommendation: Investigate job roles and working conditions predominantly held by men (e.g., sales, field roles). Consider tailored retention strategies like better work-life balance options, flexible scheduling, and targeted engagement programs.

5. Attrition Linked to Low Job Satisfaction

Finding: Employees with low job satisfaction are most likely to leave.

Recommendation: Regularly conduct employee engagement surveys to track satisfaction drivers. Introduce initiatives such as recognition programs, improved manager communication, and wellness programs to boost morale.





