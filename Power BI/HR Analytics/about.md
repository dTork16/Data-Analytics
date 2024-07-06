# HR Analytics 

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZGEwMGVhZGItMTZkYy00YWJiLWE5MGEtOWQ3MjQ1ZTU2YmIyIiwidCI6IjA5MjcxZjU4LWI2NGUtNGUxYS1hMDIxLTk5ZDE1M2QyMTRhOSIsImMiOjh9&embedImagePlaceholder=true

## About Project

This dashboard helps the company understand its attrition rate better. It helps the comapny know the trends of their attrition. Through different categories, they get to know their improvement area.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 7 : A measure was created to count the total number of employees  
- Step 8 : Another measure was created to count the number of employees who have left the company.
- Step 9 : The attrition rate measure was then calculated by dividing the total number of employees who have left the company by the total number of employees in the company.
- Step 10 :All the visuals showing the relevant KPIs were then added 

        
Snap of some of the measures ,

![image](https://github.com/dTork16/Data-Analytics/assets/122377710/e6c886d4-6d55-4866-97aa-569ec8fa46d5)

 
 # Report Snapshot (Power BI DESKTOP)

 
![image](https://github.com/dTork16/Data-Analytics/assets/122377710/33dc5885-6d9e-4257-8d5e-63c026f5db10)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

   Total Number of Employees = 1,470

   Number of employees (Male) = 882

   Number of employees (Female) = 588
   
   Total number of employees who have left the company = 237
   This is an attrition rate of 16%

   Attrition was prevalent with those between 26 years and 35 years

   5 years work experience had the most number of employees (196)
