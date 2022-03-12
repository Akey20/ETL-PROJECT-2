# ETL-PROJECT-2
**April Key, Markus Shipley, Catharine Romero, Eric East, Helen Tan**

![image](https://user-images.githubusercontent.com/94247881/157790014-a92befd8-0bb1-4450-9ee4-a0fdf1458953.png)

Project Title 
Working Title: “ETL PROJ 2”

Team Members 
Helen Tan
Catharine Romero
Markus Shipley
Eric East
April Key




Project Desc/Outline 
In the financial field, growth may be the single most discussed metric, it is the goal of companies from the smallest start-ups to the largest titans. While finance industry analysis more typically revolves around analyzing publicly traded companies due to greater interest from investors as well as greater availability of data, we are focusing on private companies. 
Our intent is to create a database of the fastest growing private companies in America, which could be analyzed to find common trends among the companies over time: number of employees, sector, and location. 
We will create a connected relational database for the fastest growing industries through BLS data for comparison so that the private companies can be compared relative to the sectors in which they are competing.
Research Questions this Database could Answer:
What are the most common and least common industries for the fastest growing private companies in America?
What cities and states are the most common locations for the fastest growing companies in America?
How many employees are typically found in the fastest growing private companies, and what does that say about the growth curve for growing businesses?
Among the fastest growing private companies, how does their growth compare to the overall growth of their industries? Which companies would be ranked higher or lower if compared relative to their industries and not in absolute terms?


Datasets to be Used:
Data World
https://data.world/aurielle/inc-5000-10-years 2007 - 2017 INC 5000 companies 
https://data.world/aurielle/inc-5000-2018 2018 INC 5000 companies
https://data.world/aurielle/inc-5000-2019 2019 INC 5000 companies

Bureau of Labor Statistics API
Getting Started : U.S. Bureau of Labor Statistics (bls.gov)

Rough breakdown of tasks:
Extract
APIs will be used to retrieve data from the Bureau of Labor statistics.  
Data from Data World will be in .csv format.  

Transform 
Joining the 2018 and 2019 data into the main 2007 - 2017 dataset by adding the years to the earlier data and merging so that every row from every year is combined into a single dataset.
Review dataset above and commence cleaning, dropping, irrelevant columns
Add BLS data to database for annual sector growth for each industry, may require manually adjusting names to align sectors as foreign keys
Utilizing QuickDBD to structure related data by sector

Load 
Loading transformed data from Jupyter Notebook into PostgreSQL.  
Tables to be determined once all of the data is extracted and analyzed.  
An Entity Relationship Diagram with Primary and Foreign Keys will be provided. 

Assignment of Tasks
The team anticipates that much of the work for Project 2 will be collaborative during class time with some outside sessions possible. As or if needed, some tasks may be assumed by individuals periodically throughout the short project.  

