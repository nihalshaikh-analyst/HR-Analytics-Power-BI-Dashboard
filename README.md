# HR-Analytics-Power-BI-Dashboard
HR Analytics dashboard data cleaning, analyzing, data analysis with dax query by using Power BI to provide insights to the HR team.



## Objective

The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization.
This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis.


- Dive deep into HR data to uncover valuable insights.
- Develop interactive dashboards to visualize key HR metrics.
- Provide data-driven recommendations for strategic decision-making.

### Key Questions of the Dashboard :

    What is the Total Employee Count ?
    What is the employee's Average Age & Average Salary ?
    What is the Attrition Count of men and women ?
    What is employees Working years at the Company ?
    Which Department has maximum employee ?
    What is the Gender distribution ?
    Which Education Field has maximum employees ?
    Which Business Travel has maximum employees 

[Download the dataset from here](https://github.com/nihalshaikh-analyst/HR-Analytics-Power-BI-Dashboard/blob/main/HR_Analytics.csv)


## Step following:

**1. Data Gathering:** 
  - Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
          
**2. Data cleaning:**
  - Cleaning is done by removing empty column, removing duplicates, errors etc.
  - Replacing values in column with proper values and naming.
  - Detecting data type of every column, using the auto detect data type function in Power query editor.
          
**3. Data processing:**
  - In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
  - This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
          
**4. Data analysis:**
  - Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
  - These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.


### Learned about:
1. Calculated Field: To Calculate Attrition Rate & Active Employees
2. Matrix table: To show Job Satisfaction rating
3. Donut chart and Pie Chart
4. Bar Chart and Cluster chart 
5. KPI(Key Performing Indicators) and Slicer.
6. Filters: Used to filter data according to different education fields.

[ Dashboard](https://github.com/nihalshaikh-analyst/HR-Analytics-Power-BI-Dashboard/blob/main/HR%20Analytics%20Power%20BI%20Dashboard.pbix)

![HR Analytics dashboard](https://github.com/nihalshaikh-analyst/HR-Analytics-Power-BI-Dashboard/blob/main/HR%20Analytics%20Power%20BI%20Dashboard.png)

## Key Performance Indicators (KPIs):
```
Employee Count: The total number of employees in the organization.
Attrition Count: The number of employees who have left the organization.
Attrition Rate: The percentage of employees who have left, indicating the attrition rate.
Active Employees: The count of currently employed staff members.
Average Age: The average age of employees in the organization.
```
 
### Key Insights Summary:

1. **Total Employees:** The organization has grown significantly, currently employing 1470 individuals, indicating substantial growth and scale.
2. **Attrition Analysis:** A total of 237 employees left the organization. Among them, 150 were male, and 87 were female, indicating a higher attrition rate among males.
3. **Departmental Attrition:** The Research and Development Department experienced the highest attrition rate at 56.13%, suggesting potential areas for improvement in employee retention strategies in this department.
4. **Education Field Impact:** Employees in the life sciences field had the highest attrition rate, emphasizing the need to address retention challenges in this specific area.
5. **Job Role Affected:** The sales role had the highest attrition rate, indicating a need for focused retention efforts in this department to reduce turnover.
6. **Education wise Attrition**: The attrition rate of High School is 18.24% which is maximum among the other education. 
7. **Attrition Rate by Gender for Different Age Group:**  The attrition count among the age group of 25-34 years 112 which is maximum among the other age groups.




# Description :-
- The HR Data Analysis Dashboard using Power BI project is tailored for HR managers and business leaders to comprehensively analyze and oversee employee data. Its aim is to empower HR professionals to make informed decisions regarding employee retention, development, and recruitment strategies.

-  The project includes trendlines and target lines, enabling HR managers to effectively monitor the progress made in reducing attrition. It features detailed charts that illustrate employee distribution and attrition rates categorized by gender, age groups, job satisfaction levels, and educational backgrounds. These charts come equipped with legends and interactive filters, allowing HR managers to delve deeper into the data and gain comprehensive insights.

-  The HR Analytics Dashboard is a powerful tool designed for HR professionals to analyze and understand employee attrition patterns within an organization. This comprehensive Power BI solution provides insights into attrition rates, active employee counts, and attrition trends based on gender and different age bands. By visualizing these key metrics, HR professionals can make data-driven decisions, optimize workforce management, and foster a diverse and inclusive workplace environment.


## Visualizations:
1. Attrition by Gender (Lollipop Chart):
A lollipop chart visually represents attrition rates based on gender. It provides a clear comparison between male and female employee turnover, aiding in gender-specific attrition analysis.

2. Department-wise Attrition (Pie Chart):
A pie chart illustrates attrition distribution across different departments. Each slice represents a department's proportion in the total attrition count, enabling HR managers to identify departments with higher turnover rates.

3. Number of Employees by Age Group (Bar Graph):
A bar graph categorizes employees into different age groups, offering insights into the age demographics of the workforce. This visualization helps in understanding the age diversity within the organization.

4. Job Satisfaction Rating (Square Chart):
A square chart displays job satisfaction ratings of employees. Each square represents an employee's satisfaction level, providing a visual overview of job satisfaction across the organization.

5. Education Field-wise Attrition (Vertical Bar Graph):
A vertical bar graph compares attrition rates across various education fields. This visualization helps in identifying patterns related to specific educational backgrounds, aiding in targeted retention strategies.

6. Education Field-wise Attrition (Donut Plot):
A donut plot offers an alternative representation of attrition rates based on education fields. It provides a more detailed view by displaying both the overall attrition rate and the individual contribution of each education field to the attrition count.


Any query connect to us nihalshaikh.analyst@gmail.com

----Thank you....



   
