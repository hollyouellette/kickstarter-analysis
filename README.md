# Kickstarting with Excel

## Overview of Project

### Purpose

This Kickstarter Analysis was initiated to support a client, Louise, in developing a successful Kickstarter Campaign in Theatre based on a dataset of previous Kickstarter Campaigns. Once Louise Launched her campaign for her play, _Fever_, in a short amount of time she came close to her fundraising goal. After this, Louise requested analysis on the success, failure and cancellations of previous campaigns in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

Original data set did not include subcategories as it's own metric - isolated this in order to analyze the outcomes based on goals specifically within the subcategory of plays.

Isolating the data required for this analysis from the orginial dataset. 

Tydying data - the orignial set included UNIX timestamps that did not support analysis. Required creating addition colums to the corsheet to create use-able data. Same with isolating the year of the kickstarter campaign in order to analyze outcomes based on launch date. 

In the analysis of Outcomes Based on Goals, adjusted the "under 1000" row to < 1000 so that it appeared first in the Line Chart when organized in ascending order (otherwise it would show up at the end). 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The month of May  and June saw the greatest amount of successful kickstarter campagins. From this, we can conclude that launching a Kickstarter campaign in May/June would increase the likelihood of that capaign meeting and/or exceeding it's fundraising goal. 
2. Failed theater outcomes do not see significant fluctuations based on the launch date. From this we can concluded that the theatre kickstarters that failures were likely the result of a different variable or a combination of the launch date and another factor. 

- What can you conclude about the Outcomes based on Goals?
Plays with fundraising goals over $45,000 saw the highest failure and the lowest success. 
Plays with fundraising goals between $5000 - $24,999 saw nearly 50/50 success: failure
Plays with fundraising goals of less that $4999 and $35,000 to $44,999 saw the greatest success.

- What are some limitations of this dataset?

Data ends in 2017

- What are some other possible tables and/or graphs that we could create?
- Backers by Category & Subcategory  
- Country by Outcomes filtered by Category 
- Average donation by Category

