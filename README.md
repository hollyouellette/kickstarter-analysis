# Kickstarting with Excel

## Overview of Project

### Purpose

This Kickstarter Analysis was initiated to support a client, Louise, in developing a successful Theatre Kickstarter Campaign based on a Kickstarter data from 2009-2017. The purpose of the anlaysis below is to determine the success, failure and cancellations of previous Kickstarter Campaigns in the "Theatre" category and "Play" subcategory in relaton to their launch dates and fundraiding goals. This analysis will be used to inform Louise's launch date and fundraising goal for her upcoming Kickstarter Campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)
_Figure 1.1. This line chart showcases the Successful, Failed and Canceled outcomes of Theatre Kickstarters in relation to the month that they were launched._

### Analysis of Outcomes Based on Goals

![](https://github.com/hollyouellette/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

_Figure 1.2. This line chart showcases the percentage of Successful, Failed and Canceled Outcomes of Kickstarters of the Plays Subcatogory in relation to their fundraising goal._

### Challenges and Difficulties Encountered

Prior to completing this analysis, there were two main challenges encountered with the Kickstarter Data set that needed to be addressed and solved:

* **UNIX Timestamps**

  * In the Kickstarter Dataset provided, the Launch and Completion dates were showcased as UNIX Timestamps. In order to be able to produce an effective visual that could be read and understood efficiently, columns containing the conversions of "Date Created" and "Date Ended" to a short date format was essential. From here, the date could be isolated and analyzed in relation to Theatre Campaign outcomes.

* **Aggregrated Category and Subcategory**

  * The data formatting in the orgininal dataset did not allow for analysis of subcategories within their parent categories. To solve for this, additional columns were added to the Kickstarter sheet using the "Text to Columns" function to separate the "Parent Category" from the "Subcategory". This enabled the collection of outcome and goal data for the "plays" subcategory specifically. 

## Results

### Conclusions Based on Launch Date

Based on the data shown in _Figure 1.1_ I have drawn the following two conclusions:
  1. **Theater Kickstarters launched in the months of May and June are those most likely to be successful.** The data clearly showcases a significant increase in successful Theater Kickstarter Camptaigns that lauched in the months of May and June. 
  2. **Failed and cancelled theatre kickstarters do not vary significantly based on their launch date.** Based on this dataset, I conclude that the failed and canceled Theater Kickstarters do not have a relationship to the month that they were launched. As such, further investigation would be required to discover what other variables in the dataset inlfuence the "failed" and "canceled" outcomes of Theater Kickstarters. 

### Conclusions about the Outcomes based on Goals

Based on the data shown in _Figure 1.2_ I have drawn the following conclusions:
 1. **Plays with fundraising goals over $45,000 saw the highest failure and the lowest success.** From this I concluded that plays with fundraising goals over $45,000 are significantly less likely to succeed.  
 2. **Plays with fundraising goals between $5000-$24,999 saw nearly 50/50 success:failure.** Based on this data, I conclude that Play Kickstarters with fundraising goals between $5000-$24,999 have a significant risk for failure. I would advise further investigation into other variables to see if there are other factors that might influence the success or failure of Play Kickstarters within this range of fundraising goals. 
 3. **Plays with fundraising goals of less that $4999 saw the greatest success.** From this I conclude that Play Kickstarters with a fundraising goal below $5000 have a high likelyhood of success.

### Limitations of this Dataset

Based on this assignment, I would identify the following as limitations to this dataset:

 1. **Recency of Data**
   This dataset contains information from Kickstarters from 2009 to 2017. This 9 year window covers signiviant social and technological changes. It is possibile that the dataset contains statistical relationships that might no longer be relavent for 2020/2021 or that could potential skew relevant data from the more recent years.
   
 2. **Kickstarters that never went live**
   This could be described as a type of sampling bias in that this dataset is only able to showcase the Kickstarters that were canceled after going live on the platform. It is a limitation because it does not account for/capture Kickstarter Campaigns that were canceled prior to going live on the Kickstarter platform.

### Other Possible Tables and or/Graphs that we could Create

In examining the relationship between the outcomes of Theatre Kickstarters in relation to their Launch Date and Fundraising Goal, we could also greate the following tables and graphs:

1. **Theater Outcomes Based on Average Donation and Launch Date**
 This table/graph visualizes, by outcome, the average donation made based on launch date. This would enable us to explore whether backers are historically more likely to donate more or less depending on what month the Kickstarter is launched.
 
2. **Theater/Play Outcomes Based on Backers and Launch Date** 
 This table/graph visualizes, by outcome, the average number of backers based on launch date. This would enable us to explore whether Theater/Play Kickstarters are historically more likely or less likely to gain backers depending on what month the Kickstarter is launched.
 
3. **Outcomes based on Campaign Length - Filtered by Campaign Goal**
 This table/graph would enable us to explore the historical realationship between the campaign length of Play Kickstarters and their outcome. This could help us dig in further to the 50:50 successful:failed outcomes of Kickstarter Plays with goals between $5000 - $25000. 
 
4. **Outcomes Based on Goal, Fitered by Country**
 This table/graph would be the same as that in _Figure 1.2_ with a "Country" filter introduced to see if specific countries might see more success in relation to certain goal ranges.

