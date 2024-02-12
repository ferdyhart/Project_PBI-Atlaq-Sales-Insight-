# Project_PBI-Atlaq-Sales-Insight-
This is individual power BI project about Sales Dashboard from Atlaq Company, you can use other features like "How's Sales Trend in 2019" or "In which month and year we gain maximum revenue", you can also click on specific markets or customers

![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/28eb8939-f3f7-40ea-8830-33b2ad575227)

for processing i used SQL and Power BI, where SQL is used to see unrelated values such as "value -1 on Sales Amount", and Power BI to ETL Process, connect relationship on other table, and creating a dashboard.

## ETL Process
### Change Unrelated Values on "Sales Amount"
There is -1 values on Sales Amount, so i decided to drop these values because its not reasonable
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/acb2cdce-26e8-49bf-bd1a-437c77ca75a0)
Result\
you can see the query has changed
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/b294d3b2-7d9b-498a-98cf-e7f5f9f9d7c1)

On the image above you can see value on "Currency" column filled with INR and USD, we know INR and USD has different Kurs, so i decided to created a new Column "Norm_Sales_Amount", multiplied Sales Amount which has USD currency by *75, and change it's data type
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/aeccb031-5b51-4aec-a024-214e51299a94)

## Relationship Every Table
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/2238962a-39fb-4439-b410-b7bb3266214f)

## Create Base Measures
to processing dashboard i need to create new table called base measures, this table contains Revenue and Sales Qty\
Revenue
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/aca2d019-00e7-4d80-8e67-f62bef76a4cd)
Sales Qty\
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/6e19c9d5-3662-4af7-b44f-b45e417d8ffb)

## Dashboard 
this is every feature you can use on this dashboard
### Base Visualization
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/416a0913-2235-4e87-9a6e-ce9e33e3cb9c)

suppose you want to know sales insight on 2019\
you can simply click on 2019 year\
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/214547d6-5812-4a41-a25a-b599b6b83537)

or you want to know sales insight on June 2019\
just click on june 19\
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/6aa6c2eb-0a30-4dce-ab31-25fe2fa3b88d)

or you want to know Sales Qty by selected customer, you can just click on these customer\
![image](https://github.com/ferdyhart/Project_PBI-Atlaq-Sales-Insight-/assets/113347559/8459a4bb-ce25-4618-a0f0-09010c373fb3)
and boom! you can see how much this customer make a revenue in this company, and where's the most impactfull markets

thats all, thankyou for coming, see ya later...
