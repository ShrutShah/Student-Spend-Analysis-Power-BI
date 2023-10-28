# Student-Spend-Analysis-Power-BI

## Overview
This project involves the analysis of student spending habits in various stores. A survey was conducted to collect data on how much students spend on different types of purchases such as Video games, Indoor games, Toys, Books, Gadgets, and more. The dataset, named "Student Survey," contains information about the stores, their locations, and the spending habits of students. The primary objective is to extract meaningful insights from this dataset using Power BI.

## Dataset
- Data set: Student survey

## Problem Statement
Create a Power BI Report that includes the following visualizations and features:

1. **Tabular Visualization**
    - Format the total amount of purchase (TAP) based on 'Store location' and 'Store setting':
      - If 0 < TAP < 35000, then records should be displayed in red.
      - If 35000 <= TAP < 60000, then records should be displayed in yellow.
      - If TAP >= 60000, then records should be displayed in blue.

2. **Matrix Visualization**
    - Create a Matrix Visualization to show the amount spent on Outdoor sports across different ages and 'Store setting'. Apply color formatting for the amount spent in total outdoor sports.

3. **Funnel chart**
    - Create a Funnel chart to display the Total amount of purchase by 'Store setting'. Show the data labels as a percentage of the first step.

4. **Pie chart**
    - Show the total amount of purchase by different 'Store location' for Suburban 'Store setting' only. Hint: Use Filter context.

5. **a) Scatter plot**
    - Visualize the relationship between Video games purchases and Outdoor sports spending across different age groups.
    **b) Sand dance plot**
    - Visualize the relationship between Indoor sports and Video games spending across different age groups.

6. **Data Access Restriction**
    - Restrict data access for given users in the User mapping table. For example, Mani deals with Rural areas only, so she should be able to view the data that belongs to Rural areas only, not urban and suburban data.

7. **Publishing**
    - Publish the report on Power BI cloud service.
    - Design the Master Dashboard consisting of the Funnel chart and scatter plots.
    - Create a schedule refresh for six times every 4 hours for the Dashboard in a day.

8. **Q&A Feature of Power BI**
    - Utilize the Q&A feature to:
        a) Show the average age of students
        b) Create a Donut chart for total amount of purchases by 'Store location'
