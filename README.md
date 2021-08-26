# Kickstarting with Excel

## Overview of Project
Our client, Louise, wants to know how various theater-related kickstarter campaigns fared based on the month they were launched and the various funding goals.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To investigate any potential trends based on kickstarter campaign launch dates, I first organized the data available through kickstarter. I created a pivot table focusing on only the “theater” campaigns and counted the number of successful, failed, and cancelled campaigns within each month. This is a graph of those outcomes by the month the campaigns were launched.

![Theater_Outcomes_vs_Launch](khttps://raw.githubusercontent.com/mdwilliams11/kickstarter-analysis/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Since the analysis based on launch date didn’t take into account the target fundraising goal it would benefit our analysis to focus on the outcomes of campaigns based on their goal amount. I started by only looking at campaigns in the subcategory of “plays”, which is a subcategory included in the parent category of the “theater” campaigns, and breaking them up into ranges of goal amounts. This is a graph of the percentage of successful and failed campaigns over the various goal ranges.


### Challenges and Difficulties Encountered
One challenge was reformatting the data related to start and end dates of the campaigns. Using a conversion formula I was able to get the time data into a format which made it possible to analyze the data based on month and year.


## Results

- From the analysis based on launch dates it seems theater-related campaigns tend to fare better in the May-Jul months. The number of campaigns are lower in the non-summer months; perhaps others are aware of this trend and are strategically timing their campaign to start over summer.

- From the analysis based on goal amount it seems that campaigns of the “plays” subcategory have a higher success rate the lower the goal amount is. Aside from a handful of successful larger goal campaigns there is a very strong negative correlation between goal amount and percentage successful.

- The distribution of “plays” campaigns based on the goal amount skews to the right, meaning there are far fewer data points on campaigns with higher goals. The percentage successful for campaigns with goals between $35000 and $45000 may seem high but there are only 6 successful campaigns in that range.

- We could further analyze the data by creating additional tables and/or graphs. We could focus on the outcomes of the campaigns based on launch date while drilling down on the subcategory of “plays” instead of all “theater” campaigns. We could include a bar graph of campaigns over the various goal amounts to see the shape of that distribution. This would give us a better idea of which sections of the data to weight more heavily.
