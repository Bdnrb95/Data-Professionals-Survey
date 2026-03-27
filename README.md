# Data Professionals Survey Analysis (Power BI Project)

## Project Overview

This project analyses survey data from data professionals to explore career roles, salary trends, demographics, programming language preferences, and satisfaction with work–life balance. The objective of the project was to demonstrate end-to-end Power BI skills, including data transformation using Power Query and building an interactive dashboard to present insights clearly.

All data preparation was completed directly inside Power BI to showcase the full analytics workflow without preprocessing in Excel.



## Tools Used

- Power BI
- Power Query Editor
- Data transformation using delimiters
- Calculated columns
- Interactive dashboard design



## Data Preparation (Power Query)

Before building the dashboard, the dataset was cleaned and transformed inside Power Query:

- Removed empty and unnecessary columns
- Standardised job role responses by splitting extra survey input using custom delimiters
- Cleaned favourite programming language responses by separating multiple formats into consistent values
- Processed salary ranges by:
  - Removing characters such as "K"
  - Splitting numeric ranges
  - Converting values into whole numbers
- Created a new Average Salary column for improved analysis and visualisation
- Standardised country and industry fields for clearer grouping and comparisons



## Dashboard Features

The dashboard includes several visualisations designed to highlight insights from the dataset:

- Total number of survey participants (card visual)
- Average participant age (card visual)
- Average salary by job role (stacked bar chart)
- Favourite programming languages (stacked column chart)
- Salary comparison by country
- Work–life balance satisfaction (gauge chart)
- Salary satisfaction (gauge chart)
- Average salary comparison by gender (donut chart)
- Custom layout and theme improvements for readability



## Key Insights

The dashboard enables exploration of:

- Salary differences across data roles
- Popular programming languages among professionals
- Geographic impact on compensation
- Gender-based salary comparisons
- Reported satisfaction with salary and work–life balance



## Dashboard Preview

Below is an overview of the Power BI dashboard analysing survey data from data professionals.

![Power BI Dashboard Preview](Screenshot%202026-03-27%20132637.png
)



## Project Purpose

This project demonstrates:

- Data cleaning using Power Query
- Creating calculated columns for analysis
- Transforming survey data into structured insights
- Building interactive dashboards
- Communicating findings through visual storytelling



## How to Use

Download the `.pbix` file from this repository and open it using **Power BI Desktop** to explore the interactive dashboard.


