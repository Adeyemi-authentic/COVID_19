
# COVID_19

### PROJECT OVERVIEW
   This project is to give us an insight of the deadly virus called COVID_19.Through analysing we found varous ratios , infection rate
,death rates , test rate across the globe.

    ###  DATA SOURCE 
   Worl covid data: a CSV file from kaggle containing detailed information about the Covid_19 acroos various continents.


  ###  TOOLS

Excel - Data cleaning.

SQL Workbench - Data Analysis.

Tableau - Data Visualization.


### Data cleaning/preparations 

In the initial data preparation phase , the following task were performed ;

- Data loading and inspection.

- Removing duplicates .

- Handling missing values.

- Data cleaning and formatting .

   ### EXPLORATORY DATA ANALYSIS 

- What is the overall total case?

- What is the total death cases?

- Continents with the highest death rate?


 ### DATA ANALYSIS

- This includes some interesting code/features worked with.
    
   ```sql
   select country,continent,max(total_death)
   as death_rate from covid_countries
    group by 1,2;
   ```


   ### RESULTS/FINDINGS.

-  The top 5 countries with the highest infection rate in Europe are Russia,Spain,UK,Italy and Germany.

-  Countries with the highest death rate are Brazil,United states ,India, Russia, South Africa .

- Death percentage in Ukraine is about 2.368% .

- Covid case percentage i.e the total case to population ratio is about 0.999% .

- Continents with the highest volume of cases are Africa,Europe, Asia, South America and North America.

- Countries where treatments are effective(recovery rate)  are US, Brazil, India, Russia, South Africa, Mexico .

-  Countries with high critical cases are US, Brazil, India, Russia and South Africa.   
