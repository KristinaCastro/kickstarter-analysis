# Kickstarter-analysis
## An Analysis on Kickstarter Campaigns
## Overview of Project
Louise is an up & coming playwright who wants to start a fundraising campaign to fund her play “Fever.” Before she launches her campaign, we are analyzing the data to determine whether there are specific factors that make a project campaign successful. More specifically, Louise wants to know how different campaigns fared according to their launch dates & their funding goal. We'll use our findings to help Louise plan her own fundraiser and set her up for success.

## Analysis and Challenges
### Outcomes Based on Launch Date
With the Dataset, using the Years () Function I was able to pull the year of the campaign launch date, which is the information we need to make our analysis. I then inserted a pivot table to filter for the outcomes of only theater fundraisers and their launch dates. Once my pivot table displayed the needed data, I then created a line graph to further show the correlation between theater fundraisers that were successful, failed or canceled and the month the fundraisers were launched.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/81998045/115982292-e6f59200-a567-11eb-93bc-92bb29df8a0c.png)

### Outcomes Based on Goals
I created a chart in a new worksheet to pull the data that is needed for our analysis. The chart is organized to show the percentage of successful, failed and canceled plays based on their goal funding amount. Using the CountIfs () function, I organized the data of each outcome per their goal range. I then calculated the percentage of successful, failed & canceled fundraisers. To further show our findings, I created a line graph showing the percenatge of successful, failed & canceled fundraisers based on their goal amounts.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/81998045/115982321-2c19c400-a568-11eb-8664-8b345993f286.png)


### Challenges and Difficulties Encountered
Using the CountIfs () function was challenging. When figuring out the formula for the goal amount ranges, entering the range value in the correct place in the overall formula was the challenge. I would place the goal amount range value in the formula, then I would manually filter to check my answer and noticed it was incorrect. So, I went to the web to find examples and tutorials on using the CountIfs () function and was able to enter the formula correctly.

## Results
### In our Outcomes Based on Launch Date analysis we can conclude:
  1. Fundraisers launched in the months of May, June and July have higher success in meeting their fundraising goal.
  2. Fundraisers launched in May have the most success in meeting their fundraising goal.

### In our Outcomes Based on Goals analysis we can conclude:
  1. Fundraisers with a goal amount under $5000 are most successful in reaching their goal.

### Limitations of the dataset:
When making our analysis, the parent category and subcategory can skew our findings. On our Outcomes based on Launched date analysis, we gathered Theater    information which includes the subcategory of plays, musicals and space. With our analysis on outcomes based on plays we pulled data for plays only. So, the limitation is in identifying the specific data that’s needed to be able to provide Louise with a tailored analysis specific to her needs so she can successfully launch her play fundraiser.

### Other possible tables/graphs the we could create:
We could create bar charts to show the data more clearly than a line graph.
