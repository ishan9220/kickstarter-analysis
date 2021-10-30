# KickStarter-Analysis

## Project Overview : 

### Purpose -

This analysis aims to provide insights and recommendations to Louise, to be able to acertain when she should begin her first crowdfunding campaign for her upcominig play 'Fever" for which she has a estimate budget of $10,000. The insights and recommendations have been sourced from a kickstarter dataset which comprises of 4114 campaigns which were launched between 2009-2017, across 9 entertainment categories, with a focus on theaters. 

### Background - 
Louise, a playwirght and our client is looking to come up with her first kickstarter crowdfunding campaign for her play 'Fever'. She would  like to know how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges - 

The Analysis includes working with Excel over a dataset containing 4114 Kickstarter  campaign IDs,  9 parent categories and 41 subcategories,  funding goals of campaign IDs,  pledged amount of campaign IDs, and outcomes of each of them. (i.e success, canceled, failed) across 12 countries. There is a focus within the theater parent category where we are observing the volume of outcome types of the theater campaigns by monthly launches and comparing the success/failure rate of the theater campaigns across these months to better understand which months had the most successes. 

### Challenges 

Some of the challenges encountered with the data was the unixtimestamp formats of the goal deadline and launched deadlines which needed to be converted to date format and splitting the category and subcategory data into parent category and subcategory to effectively view the data of the theater campaigns which is relevant to Louise. 

[Excel Analysis Reference Sheet](https://github.com/ishan9220/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

## Results : 

### Theater Outcomes by Launch Date -

![Theater_Outcomes_vs_Launch](https://github.com/ishan9220/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

**Conclusion 1** -
 Campaigns under the Theater category which began during the summer months of May, June and July were much more successful with May being the most successful month (111). 

**Conclusion 2** -
The winter months of Nov, Dec and January had the lowest performance in terms of successes  along with very low volume of launched campaigns - 147 total across these months while 298 campaigns were launched across May, June and July.  

### Outcomes based on Goals - 

![Outcomes_vs_Goals](https://github.com/ishan9220/kickstarter-analysis/blob/main/Outcomes%20vs%20Goals_png.png).

**Conclusion** -
The Most number of succesful theater campaigns were for ones which had funding goals below $15K (889 campaigns) followed by campaigns which had funding goals between $35K to $45K.

### Data Set Limitations - 

THis data set doesn't provide the totat funding amount per campaign during each month which can be an important piece of information for Louis to understand which month brought in the most funds per campaign. 
Addtionally we are also not clear of the average funding time of each campaign which is another important metric for Louise to know how long she can expect to wait to hit her funding goals. 

### Recommendations -

Recommend craeting a new column in the Kickstarter data set which provides the total active time of each campaign in terms of days. This can tell usthe time it took for each camapign in the theater category to meet or fail it's campaign fund goals and we will be able uncover the average success time for each theater campaign, the standard deviation of campaigns across the funding levels ($1-$50K. 


