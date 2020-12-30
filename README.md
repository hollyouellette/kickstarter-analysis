# Kickstarting with Excel

## Overview of Project

### Purpose

This Kickstarter Analysis was initiated to support a client, Louise, in developing a successful Kickstarter Campaign based on a Kickstarter data from 2009-2017. The purpose of the anlaysis below is to determine the success, failure and cancellations of previous Kickstarter Campaigns in the "Theatre" catergory in relaton to their launch dates and fundraiding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

Prior to completing this analysis, there were two main challenges with the Kickstarter Data set that needed to be addressed and solved:

* **UNIX Timestamps**
 * In the Kickstarter Dataset provided, the Launch and Completion dates were showcased as UNIX Timestamps. In order to be able to produce a visual that could be read and understood as efficiently as possible, columns containing the conversions of "Date Created" and "Date Ended" to a short date format was essential. From here, the date could be isolated and analyzed in relation to Theatre Campaign outcomes.

* **Aggregrated Category and Subcategory**
  * The way that the data was presented in the orgininal dataset did not allow for analysis of subcategories within their parent categories. To solve for this, additional columns were added to the Kickstarter sheet using "Text to Columns" to separate the "Parent Category" from the "Subcategory". This enabled the collection of outcome and goal data for the "plays" subcategory. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The month of May  and June saw the greatest amount of successful kickstarter campagins. From this, we can conclude that launching a Kickstarter campaign in May/June would increase the likelihood of that capaign meeting and/or exceeding it's fundraising goal. 
2. Failed theater outcomes do not see significant fluctuations based on the launch date. From this we can concluded that the theatre kickstarters that failures were likely the result of a different variable or a combination of the launch date and another factor. I advise digging further into the specific associations with the failed kickstarters to discover other potential relationships. 

- What can you conclude about the Outcomes based on Goals?
Plays with fundraising goals over $45,000 saw the highest failure and the lowest success. 
Plays with fundraising goals between $5000 - $24,999 saw nearly 50/50 success: failure
Plays with fundraising goals of less that $4999 and $35,000 to $44,999 saw the greatest success.

- What are some limitations of this dataset?

Data ends in 2017
It contains a lot of data that requires sifting
UNIX timestamps 
it's an existing dataset - might not contain the data that we are looking for - tayloring our questions ot he fdata that exists.
this data only accounts for kickstarters that made it to the platform but does not include kickstarter ideas that never went live

- What are some other possible tables and/or graphs that we could create?
- Backers by Category & Subcategory  
- Country by Outcomes filtered by Category 
- Average donation by Category

