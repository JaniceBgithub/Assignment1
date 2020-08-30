# Kickstarting with Excel

## Overview of Project

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

### Purpose

The purpose of this project was to analyze kickstarter campgaigns for theaters and determine the launch month and fundraising goals that are more likely to succeed. 


## Analysis and Challenges
Excel analysis was used with a pivot table used to determine the best launch month.  The data was filtered for parent category "theatre" and then sorted by launch month for successful, canceled and failed. 

The countifs function was used for the best fundraising goal.  The data was split into categories ranging from less than 1000 to >50,000 in $5000 increments.  The total campaigns were summed and used to determine percentages. 

### Analysis of Outcomes Based on Launch Date

May, June, July and August are hte most sucessful times to launch a kickstarter campaign.  
Decemember is the worst month to launch! 

![Outcomes_based_Launch_date](https://github.com/JaniceBgithub/Assignment1/blob/master/Theatre_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
The lower the fundraising goal, the more successful it was. Goals of <10,000 were 60 to 70% successful.  Greater than 50,000 was particularly bad with only a 16% chance of success.  There was also a high portion of cancelled campaigns at the >50,000 level at 25%.  Cancelled campaigns were positively linked with higher goal amounts. 


![Outcomes_Goals](https://github.com/JaniceBgithub/Assignment1/blob/master/Outcomes_based_on_goals.png)

### Challenges and Difficulties Encountered

No challenges encountered, although pivot tables can often be a bit confusing and take a bit of moving things around to get the right things happening. 

The countif function is a bit limiting and used the countifs for better functionality and to save some time!
 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May, June, July and August are hte most sucessful times to launch a kickstarter campaign.  
Decemember is the worst month to launch! 


- What can you conclude about the Outcomes based on Goals?

The lower the fundraising goal, the more successful it was. Goals of <10,000 were 60 to 70% successful.  Greater than 50,000 was particularly bad with only a 16% chance of success.  There was also a high portion of cancelled campaigns at the >50,000 level at 25%.  Cancelled campaigns were positively linked with higher goal amounts. 

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

This analyis included quite a few entries for theatre "spaces" which is inherently different than a play or musical.  The theater "space" data could have been removed for a better analysis. 

This analysis did not look at currency.  A more complete analysis would have converted currencies all into one currency. 

It would have also been good to look at average donation and how that was linked with success.  ie - it is more useful to find a few bigger donors, or lots of smaller donors.

