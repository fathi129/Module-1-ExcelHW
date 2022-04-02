# Module-1-ExcelHW
Performing analysis on the Kickstarter dataset to help Louise to know the trends of funding goals.



## Overview of Project
 Louise's play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared regarding their launch dates and funding goals. We visualized the campaign outcomes based on their launch dates and funding goals using the Kickstarter dataset. 
### Purpose
 We need to provide a visual summary of the data so that Louise can understand better the success rate of the campaigns based on the launch date and goals.


## Analysis and Challenges
 We need to understand the data types of the data. If required, we have to convert to readable data and organize it to generate insights based on the data, which helps in Louise's project. Here in this analysis, we have converted  the Unix timestamps to a more readable date.
 We have separated the categories and subcategories to analyze campaigns more efficiently. We have created a new column for the year of the launch date. Louise was going to launch her theater campaign, so we are analyzing the theater campaigns.
- Based on the pivot table and chart, We can see that  In the US, the theater campaigns were the most successful. We can see 912 theater campaigns; among them, 525 campaigns were successful.

![image](https://github.com/fathi129/Module-1-ExcelHW/blob/master/Kickstarter%20Analysis/Category.png)






- Further analysis based on the subcategory shows that there were Musicals, Plays, and Spaces, but Plays contributed more success than others. In the US, the Plays subcategory success was 412 out of 671. That is, 61% of campaigns were successful.
![image](https://github.com/fathi129/Module-1-ExcelHW/blob/master/Kickstarter%20Analysis/SubCategory.png)



### Analysis of Outcomes Based on Launch Date
- The analysis based on the launch date indicates more successful plays in May and June. In December, the number of successful campaigns was less. It shows that the best time to start a campaign would be in summer rather than winter. However, June, July, and October had roughly the same number of failed campaigns launched.  
![image](https://github.com/fathi129/Module-1-ExcelHW/blob/master/Resources/Theater_Outcomes_vs_Launch.png)



### Analysis of Outcomes Based on Goals
- Analysis based on the Goals indicates that the goals less than $1000 were 76% more successful, and the goals around $45000 to $49000 mainly were unsuccessful. The success and failure percentages were the same when the goal was around $15000 to $19999. 
We can see that the higher the goal, the higher the failure of campaigns.
![image](https://github.com/fathi129/Module-1-ExcelHW/blob/master/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
- We need to sort and organize the data.
- We need to apply filters to separate the parent and subcategory data.
- When performing the COUNTIFS formulas to calculate the successful, failed campaigns, we needed to enter the formulas manually, more errors were encountered, but it was solved.

### Conclusions Drawn from the Outcomes based on Launch Date
   - Launching the campaign in May and June (Summer) was more successful.
   - The success rate of the campaign was less in December (Winter).
   - The length of the campaign should also be short for success.

### Conclusion Drawn from the Outcomes based on Goals?
   - The campaigns with goals less than $1000 were more successful when compared to the campaigns with goals greater than $15000


### Limitations of the dataset
  - The dataset needs more information.
  - The Genre of the plays was not specified in the dataset, it would be further helpful to analyze which type of plays were more liked by the audience.
The dataset is only from Kickstarter crowdfunding campaigns. If we would get data from different funding campaigns, we can better understand the success of theater and plays.



### Other possible tables and/or graphs that we could create
  - We can create stacked column charts for outcomes based on the date.
  - We can determine the statistical data based on mean, mode, and median and draw boxer plots based on it.
