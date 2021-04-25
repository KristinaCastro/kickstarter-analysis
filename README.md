# Kickstarter-analysis
## An Analysis on Kickstarter Campaigns
## Overview of Project
Louise is an up & coming playwright who wants to start a fundraising campaign to fund her play “Fever.” Before she launches her campaign, we are analyzing the data to determine whether there are specific factors that make a project campaign successful. More specifically, Louise wants to know how different campaigns fared according to their launch dates & their funding goal. 

## Analysis and Challenges
### Outcomes Based on Launch Date
With the Dataset, using the Years () Function I was able to pull the year of the campaign launch date, which is the information we need to make our analysis. I then inserted a pivot table to filter for the outcomes of only theater fundraisers and their launch dates. Once my pivot table displayed the needed data, I then created a line graph to further show the correlation between theater fundraisers that were successful, failed or canceled and the month the fundraisers were launched.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/81998045/115982292-e6f59200-a567-11eb-93bc-92bb29df8a0c.png)

### Outcomes Based on Goals
I created a chart in a new worksheet to pull the data that is needed for our analysis. The chart is organized to show the percentage of successful, failed and canceled plays based on their funding amount. Using the CountIfs () function, I organized the data of each outcome per their goal range. I then calculated the percentage of successful, failed & canceled fundraisers.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/81998045/115982321-2c19c400-a568-11eb-8664-8b345993f286.png)


### Challenges and Difficulties Encountered
Using the CountIfs () function was challenging. When figuring out the formula for the goal amount ranges, entering the range value in the correct place in the overall formula was the challenge. I would place the goal amount range value in the formula, then I would manually filter to check my answer and noticed it was incorrect. So, I went to the web to find examples and tutorials on using the CountIfs () function and was able to enter the formula correctly.

## Results
## In Outcomes Based on Launch Date analysis we can conclude:
  1. Fundraisers launched in the months of May, June and July have higher success in meeting their fundraising goal.
  2. Fundraisers launched in May have the most success in meeting their fundraising goal.



