# NBA-Player-Attributes-Analysis
Here’s a structured README content for your NBA Player Analysis project, which you can use for your GitHub repository.

# Project Overview
The NBA Player Analysis project focuses on analyzing physical characteristics such as height, weight, wingspan, agility, and vertical jump of NBA players to determine how these metrics influence their draft position and potential success in the league.

Dataset: Contains 403 NBA players’ physical attributes from the years 2009 to 2017.<br>
Goal: To provide insights into which physical attributes are critical for success in the NBA draft.<br>
Dashboard: The interactive dashboard visualizes player data to help scouts and analysts make data-driven decisions.<br>

# Data Cleaning & Preparation
Steps Involved:<br>
1.Missing Values Handling:<br>

Columns like Bench, Sprint, and Agility had missing values, which were filled using the average values.
Formula used: =IF(ISBLANK(Q2), ROUND(AVERAGE($Q$2:$Q$518), 0), Q2)<br>
2.Power Query in Power BI:<br>

Null values were filtered out during data loading and transformations were applied to ensure clean, usable data.<br>
3.Data Transformation:<br>

Columns like height and weight were categorized into ranges using the SWITCH() function in DAX.<br>

# Tools & Technologies

->Power BI: Used for building interactive dashboards and generating insights.<br>
->DAX (Data Analysis Expressions): Used for calculating averages, measures, and creating KPIs.<br>
->Excel: Utilized for initial data cleaning and handling missing values.<br>
->SQL: (Optional, if you ran any queries to handle data before importing to Power BI).<br>
# DataSet
<a href=https://github.com/Aarthi-1301/data-analysis-dashboard/blob/main/nba.csv>Dataset</a>
# Dashboard
<a href="https://github.com/Aarthi-1301/data-analysis-dashboard/blob/main/Screenshot%20(14).png"> Dashboard</a><br>
<br><br><br>![Screenshot (14)](https://github.com/user-attachments/assets/25bc2342-f786-4c4b-b6ae-17af94eead38)

