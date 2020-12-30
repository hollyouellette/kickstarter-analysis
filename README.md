# Kickstarting with Excel

## Overview of Project

### Purpose

This Kickstarter Analysis was initiated to support a client, Louise, in developing a successful Kickstarter Campaign based on a Kickstarter data from 2009-2017. The purpose of the anlaysis below is to determine the success, failure and cancellations of previous Kickstarter Campaigns in the "Theatre" catergory in relaton to their launch dates and fundraiding goals. This analysis will be used to inform Louise's launch date and fundraising goal for her upcoming Kickstarter. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)
_Figure 1.1. This line chart showcases the Successful, Failed and Canceled outcomes of Theatre Kickstarters in relation to the month that they were launched._

### Analysis of Outcomes Based on Goals

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

_Figure 1.2. This line chart showcases the percentage of Successful, Failed and Canceled Outcomes of Kickstarters of the Plays Subcatogory in relation to their fundraising goal._

### Challenges and Difficulties Encountered

Prior to completing this analysis, there were two main challenges with the Kickstarter Data set that needed to be addressed and solved:

* **UNIX Timestamps**

  * In the Kickstarter Dataset provided, the Launch and Completion dates were showcased as UNIX Timestamps. In order to be able to produce a visual that could be read and understood as efficiently as possible, columns containing the conversions of "Date Created" and "Date Ended" to a short date format was essential. From here, the date could be isolated and analyzed in relation to Theatre Campaign outcomes.

* **Aggregrated Category and Subcategory**

  * The way that the data was presented in the orgininal dataset did not allow for analysis of subcategories within their parent categories. To solve for this, additional columns were added to the Kickstarter sheet using "Text to Columns" to separate the "Parent Category" from the "Subcategory". This enabled the collection of outcome and goal data for the "plays" subcategory. 

## Results

### Conclusions Based on Launch Date

Based on the data shown in _Figure 1.1_ I have drawn the following two conclusions:
  1. **Theater Kickstarters launched in the months of May and June are those most likely to be successful.** The data clearly showcases a significant increase in successful Theater Kickstarter Camptaigns that lauched in the months of May and June. 
  2. **Failed and cancelled theatre kickstarters do not vary significantly based on their launch date.** Based on this dataset, I conclude that the failed and canceled Theater Kickstarters do not have a relationship to the month they were launched. As such, further investigation would be required to discover what other variables in the dataset inlfuence the "failed" and "canceled" outcomes of Theater Kickstarters. 

### Conclusions about the Outcomes based on Goals

Based on the data shown in _Figure 1.2_ I have drawn the following conclusions:
 1. **Plays with fundraising goals over $45,000 saw the highest failure and the lowest success.** From this I concluded that plays with fundraising goals over $45,000 are significantly less likely to succeed.  
 2. **Plays with fundraising goals between $5000-$24,999 saw nearly 50/50 success:failure.** Based on this data, I conclude that setting fundraising goal for Play Kickstarters has a significant risk for failure. I would advise further investigation into other variable realtionships to see if there are other factors that might influence the success or failure of Play Kickstarters within this range of fundraising goals. 
 3. **Plays with fundraising goals of less that $4999 saw the greatest success.** From this I conclude that Play Kickstarters with a fundraising goal below $5000 have a high likelyhood of success.

### Limitations of this Dataset

Based on this assignment, I would identify the following as limitations to this dataset:

 1. **Recency of Data**
   This dataset contains information from Kickstarters from 2009 to 2017. This 9 year window covers signiviant social and technological changes. It is possibile that the dataset contains statistical relationships that might no longer be relavent in 2020, 2021 or that could potential skew relevant data.
 
 2. **UNIX Timestamps**

 3. **Kickstarters that never went live**
It contains a lot of data that requires sifting
UNIX timestamps 
it's an existing dataset - might not contain the data that we are looking for - tayloring our questions ot he fdata that exists.
this data only accounts for kickstarters that made it to the platform but does not include kickstarter ideas that never went live

- What are some other possible tables and/or graphs that we could create?
- Backers by Category & Subcategory  
- Country by Outcomes filtered by Category 
- Average donation by Category

