# KickStarter-Analysis

## Project Overview : 

### Purpose -

This analysis is an attempt to provide clear insights and recommendations to Louise,  the client to allow her to compare her campaign's performance to thousands of other  kickstarter campaigns on the basis of how successfully the campaigns were funded, failed to received funding and were canceled, between 17th May 2009 to 3rd March 2017 across each month during this time period. 

### Background - 
Louise, the client's play 'Fever' came close to its fundraising goal in a short amount of time. She would now like  to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, this analysis aims to visualize campaign outcomes based on their launch dates and their funding goals.

## Analysis and Challenges

Analysise performed using Excel over a dataset containing 4114 Kickstarter entertainment campaigns,  9 parent categories and 41 subcategories, $ target funding (goals) of each title, $ pledged amount of each title, outcome of the kickstarter campaigns (i.e success, canceled, failed) across 12 countires. 

Able to draw further data points such as average donation per campaign, color code outcomes, percentage funded for each campaign, break up Category and Subcategory by Parent Category and Subcategory. 

Some of the challenges encountered with the data was the unixtimestamp formats of the goal deadline and launched deadlines which needed to be converted to date format. 

[Excel Analysis Link](https://github.com/ishan9220/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

## Results : 

### Theater Outcomes by Launch Date -

![Theater_Outcomes_vs_Launch](https://github.com/ishan9220/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

Conclusion 1 
Campaigns which began during the summer months of May, June and July were the most successful with May being the most successful month for campaigns to hit funding goals. These months also had the most volume of campaigns launched at 298. 

Conclusion 2 
The winter months of Nov, Dec and January had the lowest performance in terms of successes  along with very low volume of launched campaigns - 147. 

### Outcomes based on Goals - 

![Outcomes_vs_Goals](https://github.com/ishan9220/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png).

Conclusion - 
Most number of succesful campaigns were for ones which had funding goals below $15K, at 889 total successful campaigns. 

### Data Set Limitations - 

Required converting unix timestamps of launched and deadline time of funding into date format to use in pivot and line graphs. The categoriees and subcategories taxonomies were also merged so it required the data to be divided further in parent and sub-categories. 

THis dataset doesn't provide the totat funding amount during each month which can be an important piece of information for Louis to decide success of the campaigns listed. 

### Recommendations -

Primary addition would total funds rasied in each month by 
Addition of stacked graph which shows success, failure and canceled campaigns over years can inform us better of which years were the most successful in term of funding. 


