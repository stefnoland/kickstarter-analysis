# Kickstarting with Excel
 
## Overview of Project

Using the Kickstarter dataset, visualize campaign outcomes based on their launch dates and their funding goals. 

The documents are the result of the analysis:

*Outcomes Based on Launch Date Chart

*Outcomes Based on Goals Chart

*A written analysis of the results

### Purpose

*The purpose of this analysis is to use Excel to view the kickstarter data based on goals and launch date to assist client in crowdfunding make choices that are most likely to make her campaign a success


## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

The first step in this analysis to look at the success of campaigns based on the month of launch required converting dates using Unix time stamps.  

A pivot table was created to view Theater Outcomes by Launch Date.  Then a line-graph was generated to visualize the number in each outcome category (successful, failed and canceled) by month.




### Analysis of Outcomes Based on Goals

An analysis was then performed of Outcomes Based on Goals and a table was created with ranges of $ amounts pledged by $ goal. 

The COUNTIFS function was used to find the ranges for each of three categories: successful, Failed and Canceled specifically for the subcategory of plays.  A percentage was generated for each $ goal range.  

A chart was created to visualize the Outcomes Based on Goals.  This helped to determine if the $ values of the goals impacted the eventual outcome of the campaign.



### Challenges and Difficulties Encountered

Challenges included having enough information to assist the client in making decisions with more certainty.  The goals did not appear to predict the outcomes, with a few exceptions.  More information about amount raised, even for failed campaigns, may have been helpful to view.


## Results

- Conclusions about the Outcomes based on Launch Date:

-- May, June and July are the months that have the highest success rate to launch a kickstarter campaign for theater.  

-- May has the highest overall success rate. 

-- Launching a campaign in December appears to only give the campaign a 50% chance of success. 



- Conclusions about the Outcomes based on Goals:

--Generally, there is an inverse relationship between the size of the goal and the percentage of failure, such that campaigns under 1000 had an 76% success rate, compared to those with greater than 50000 having a 13% success rate. 

--35000-49000 is the most stable goal-range, with a 67% success rate across three $ goal ranges.



- What are some limitations of this dataset?

There are many variables not accounted for that would contribute to the success of a campaign's funding.  Other factors being included in the data set would allow for a much more precise analysis of the variables influencing the probability of success. 



- What are some other possible tables and/or graphs that we could create?

--Demographics and location of each campaign, who was included in exposure, who was solicited for donations and where in the country was the project located

--Rating on the quality of the campaign proposal for major factors needed for potential investors

--Percent of goal funded (even if a failed campaign) to see if an adjusted goal would have improved percentage of successful campaigns.
