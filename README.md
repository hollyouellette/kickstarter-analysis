# Kickstarting with Excel

## Overview of Project

### Purpose

This Kickstarter Analysis was initiated to support a client, Louise, in developing a successful Kickstarter Campaign based on a Kickstarter data from 2009-2017. The purpose of the anlaysis below is to determine the success, failure and cancellations of previous Kickstarter Campaigns in the "Theatre" catergory in relaton to their launch dates and fundraiding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)
_figure 1.1. This line chart showcases the Successful, Failed and Canceled outcomes of Theatre Kickstarters in relation to the month that they were launched._

### Analysis of Outcomes Based on Goals

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

_figure 1.2. This line chart showcases the percentage of Successful, Failed and Canceled Outcomes of Kickstarters of the Plays Subcatogory in relation to their fundraising goal._

### Challenges and Difficulties Encountered

Prior to completing this analysis, there were two main challenges with the Kickstarter Data set that needed to be addressed and solved:

* **UNIX Timestamps**

  * In the Kickstarter Dataset provided, the Launch and Completion dates were showcased as UNIX Timestamps. In order to be able to produce a visual that could be read and understood as efficiently as possible, columns containing the conversions of "Date Created" and "Date Ended" to a short date format was essential. From here, the date could be isolated and analyzed in relation to Theatre Campaign outcomes.

* **Aggregrated Category and Subcategory**

  * The way that the data was presented in the orgininal dataset did not allow for analysis of subcategories within their parent categories. To solve for this, additional columns were added to the Kickstarter sheet using "Text to Columns" to separate the "Parent Category" from the "Subcategory". This enabled the collection of outcome and goal data for the "plays" subcategory. 

## Results

### Conclusions Based on Launch Date

Based on the data shown in _figure 1.1_ I have drawn the following two conclusions:
  1. **Kickstarters launched in the months of May and June are those most likely to be successful.** The data clearly showcases a significant increase in successful Kickstarter Camptaigns that lauched in the months of May and June. 
 2. **Failed and cancelled theatre kickstarters do not vary significantly based on their launch date.** Based on this dataset, I conclude that the failed and canceled kickstarters do not have a relationship to the month they were launched. As such, further investigation would be required to discover what other variables in the dataset inlfuence the "failed" and "canceled" outcomes of Theater Kickstarters. 

### Conclusions about the Outcomes based on Goals

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

