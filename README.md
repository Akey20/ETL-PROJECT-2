# ETL-PROJECT-2
**April Key, Markus Shipley, Catharine Romero, Eric East, Helen Tan**

![image](https://user-images.githubusercontent.com/94247881/157790014-a92befd8-0bb1-4450-9ee4-a0fdf1458953.png)

**Project Title 
“Sector Comparison of the top growing 1,000 private companies from 2007 - 2019”**

**Project Desc/Outline**
In the financial field, growth may be the single most discussed metric, it is the goal of companies from the smallest start-ups to the largest titans. While finance industry analysis more typically revolves around analyzing publicly traded companies due to greater interest from investors as well as greater availability of data, we are focusing on private companies. 
Our intent was to create a database of the fastest growing private companies in America, which could be analyzed to find common trends among the companies over time: number of employees, sector, and location. 
We created a connected relational database for the fastest growing industries through BLS data for comparison so that the private companies can be compared relative to the sectors in which they are competing.

### Research Questions this Database can Answer:
     1. What are the most common and least common sectors for the fastest growing private companies in America?
     2. What cities and states are the most common locations for the fastest growing private companies in America? 
        Analysis may also be performed by Sector. Are there any burgeoning hubs for any of these sectors?
     3. How many employees are typically found in the fastest growing private companies,
        and what does that say about the growth curve for growing businesses?
     4. Among the fastest growing private companies, how does their growth compare to the overall growth of their industries? 
     5. Which companies would be ranked higher or lower if compared relative to their industries and not in absolute terms?  


**Datasets to be Used:**
Data World
https://data.world/aurielle/inc-5000-10-years 2007 - 2017 INC 5000 companies 
https://data.world/aurielle/inc-5000-2018 2018 INC 5000 companies
https://data.world/aurielle/inc-5000-2019 2019 INC 5000 companies
Three csv data files used from Data World dataset.

Bureau of Labor Statistics csv files
Getting Started : U.S. Bureau of Labor Statistics (bls.gov)
Twenty CSV data files formatted using Pandas in Jupyter Notebook. 

**Breakdown of tasks:**

**Extract:**
Retrieved data from the data Bureau of Labor statistics levergaing their "data finder" tool.  
Data from Data World was in .csv format.  

**Transform:**
Joining the 2018 and 2019 data into the main 2007 - 2017 dataset by adding the years to the earlier data and use the "concat" function in Pandas so that every row from every year is combined into a single dataset. Columns were renamed and standardized. 
Review dataset above and commence cleanin and dropping irrelevant columns.
Add BLS data to database for annual sector growth for each industry, rerquired mapping industry in the DataWorld data to the sectors in the BLS data.
Utilizing QuickDBD to structure related data by sector.

**Schemata used in final database:**
See ERD (Entity Relationship Diagraam) in the SQL folder.  SQL used to create tables also included in the SQL folder.

**Load:** 
Loading transformed data from Jupyter Notebook into PostgreSQL.  
Tables loaded into tables based on final data structure of data frames.
An Entity Relationship Diagram is provided in the SQL Folder.

**Assignment of Tasks:**
Much of the work for Project 2 was collaborative during class time with some tasks completed individually between groups sessions.  

**###Additional Notes**
 1. All CSV files are in CSV folder and BLS_CSVs Folder*
 2. ERD and SQL to create database and related tables are in SQL Folder*
 3. All Final Jupyter Notebooks are in the Final Notebooks Folder*
 4. All Images are in the Images Folder*
 

