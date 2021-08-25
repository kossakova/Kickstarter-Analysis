# kickstarter-analysis
Performing analysis for Kickstarter project to uncover trends.

## Overview of Project
This analysis was made for Louise to help her start a crowdfunding campaign for her new play Fever. 
With her estimating budget of over $10000 she was hesitant about her first fundraising campaign and needed deep analysis of Kickstarter worksheet data.

### Purpose
We helped Louise to gain a greater understanding of the project campaign from start to finish.
We analyzed and visualized the Kickstarter worksheet to make the thousands of hidden data more readable to help her easily understand trends and set her new play for success. 

## Analysis and Challenges
We were able to:
Make data more precise by separating main and subcategories into two distinct categories, this gave us additional data to use in our analysis. 
Apply visualization to outcomes of each categories using pivot charts and tables. 
Project a valuable piece of data by the length of fundraising campaign, to find out if the length of the campaign correlate with success and outcome.
Make the data readable using Unix timestamp to determine what month launched the most successful Kickstarter campaign. 
Organize, sort and analyze crowdfunding data to determine whether there are specific factors that make project campaign successful. 

### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/88459985/129804055-a1a0f95e-acc2-4ff4-9d58-47632104d29f.png)
We did our first analysis by creating a pivot table and graph for “Outcomes by Launch Date”. 
We applied filters to our pivot table to look up specific category and a year. 
We also created a line chart from the pivot table to visualize the relationship between outcomes and launch months. 

### Analysis of Outcomes Based on Goals
https://github.com/kossakova/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png
We visualized the percentage of successful, failed, and canceled plays based on the funding goal amount in play subcategory. 
Created Goal column to determine number of campaigns in every outcome category. 
Based on our tubular data we created a line chart to expose relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.

### Challenges and Difficulties Encountered
One of the challenges I had while working on the project is that data file was too big to work with. 
The Kickstarter worksheet had over 4000 campaigns, applying data analysis and creating more charts and lines made it much more difficult to navigate around. 
I overcome this challenge by separating some charts and graphs to a folder where we stored the rest of analysis for this project, it made worksheet more organized and easier to work with.

## Results
By looking at the “Theater Outcomes by Launch Date” pivot table we can make a few conclusions. 
The theater category has over 61% of success outcomes. 
The month of May has higher success rate over other months. 

Our “Outcomes Based on Goals” chart tells us that campaigns with lower goal amount have a higher chance for success rather than campaigns with high goals.

The data we worked with seemed whole and had enough data to work with for purpose of analysis, furthermore some of the data in this Kickstarter sheet can be omitted for future analyses to make it easier to work with.

There can be a few more charts added that will help expose the overall condition of these campaigns. We can add pie charts to see which campaign categories were outperformed the most. 
We could also create more pivot tables for each category to look at their success and fail ratio. 
