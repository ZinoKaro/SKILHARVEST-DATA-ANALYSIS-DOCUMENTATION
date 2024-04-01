# SKILHARVEST STATIONARY SUPPLIES
SkilHarvest Stationary Supplies Data Analysis project aims to extract valuable insights and trends, shedding light on the dynamics of the stationary supplies market.
In this endeavor, we delve into a comprehensive exploration of the provided dataset from SkilHarvest.

## CONTENT OUTLINE

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Data Analysis](#data-analysis)

[Result / Findings](#result-findings)

## Project Overview
The SkilHarvest Stationary Supplies Data Analysis project aims to unravel the intricate details of the stationary supplies market through a comprehensive exploration of a curated dataset from SkilHarvest Stationary Supplies. This endeavor combines data science methodologies, exploratory data analysis (EDA), and insightful visualizations to extract meaningful patterns, trends, and actionable insights.

The primary objective of this project is to provide stakeholders, business analysts, and enthusiasts with a detailed understanding of the dynamics within SkilHarvest Stationary Supplies. Through data-driven analysis, we seek to answer key questions about product popularity, customer behavior, and market trends, ultimately contributing valuable knowledge to the business strategy.

## Data Sources
- Data Source: SkilHarvest Stationary Supplies internal sales and customer database.
- File Format: Comma-separated values (CSV).
- File Name: SkilHarvest_Stationary_Supplies.csv
- ![SkilHarvest_Stationary_Supplies](SkilHarvest_Stationary_Supplies)

## Tools Used
- **Ms Excel**: For Data Cleaning, Exploration and aggregation. [Download Here](https://www.microsoft.com/excel)
- **Google Sheet**: For Collaborative Analysis and Cloud Based Storage. [Download Here](https://www.google.com/sheets/about/)
- **Ms SQL Server**: For Advanced Data Transformation and Modeling, Data Storage and Integration with Power BI. [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- **PowerBI**: For Interactive Data Visualization and Integration with Other Microsoft Tools. [Download Here](https://powerbi.microsoft.com)
- **Ms PowerPoint**: For Storytelling and Presentation. [Download Here](https://www.microsoft.com/PowerPoint)
  
## Data Cleaning and Preparation
Exploratory Data Analysis (EDA) - This critical phase involves a systematic exploration of the dataset to uncover patterns, relationships, and key insights. By leveraging various statistical and visual techniques, we aim to gain a deeper understanding of the dynamics within SkilHarvest Stationary Supplies.
Using Google Query Sheet, these queries were analysed
- Sales of Binder items and Pencil in 2015
- Sales in Central and East region in 2014
- Sales in August and September 2014
- Sales of items that starts with Pen, including their region, sales rep and year
- Sales of items that ends with 'sk', including their region, sales rep and year.
  


## Data Analysis
Sales of Binder items and Pencil in 2015
```
=QUERY(A:H,"SELECT C,F,H WHERE (C = 'Binder' OR C = 'Pencil') AND F = 2015",1)
```
Sales in Central and East region in 2014
```
=QUERY(A:H, "SELECT A,F,H WHERE (A = 'East' OR A = 'Central') AND F = 2014" , 1)
```
Sales in August and September 2014
```
=QUERY(A:H, "SELECT C,E,F,H WHERE (E = 'Aug' OR E = 'Sep') AND F = 2014 ", 1)
```
Sales of items that starts with Pen, including their region, sales rep and year
```
=QUERY(A:H, "SELECT A, B, C, F, H WHERE C LIKE 'Pen%'", 1)
```
Sales of items that ends with 'sk', including their region, sales rep and year
```
=QUERY(A:H, "SELECT A, B, C, F WHERE C LIKE '%sk'", 1)
```

## Result / Findings
QUERY RESULTS

 ![Query 1]("1.jpg")
- ![Query 2](2)
- ![Query 3](3)
- ![Query 4](4)
- ![Query 5](5)

Add file
![](uploaded file)

