# An analysis of a kickstarter campaigns 

## Overview of the project
Performing analysis on Kickstarter data to uncover trends

###Purpose
Since Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals two charts have been created using the Kickstarter dataset. Two graphs were created to better visualize campaign outcomes based on their launch dates and their funding goals. 

##Analysis and Challenges

In order to create two graphs to better visualize the outcomes and understand the data, Kickstarter data set was used to create a pivot table which allowed to create two filters to identify the months based on the year of the campaigns, and plays subcategory. Pivot table also allowed me to add columns to organize cancelled, failed and successful number of plays. Once the pivot table was created and filtered in the alphabetical order, a line graph was created to provide visual outcomes and narrow down the analysis. 

For the second graph, Excel skills were utilized to find the percentage of successful, failed and canceled plays based on the funding goal amount. A new sheet was created to reflect dollar amount ranges in a left column and 8 columns to reflect a Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, and Percentage Failed. Then, using the function countifs() and function sum() data was populated to reflect Outcomes Based on Goals. Once I had the data populated, percentages of the data were created. Once all the data was organized, I hid the columns without percentages and created the line graph with goal-amount ranges on the on the x-axis and percentage of the failed, canceled, and successful projects on the y-axis. 

<img width="342" alt="Outcomes based on Goal_Table" src="https://user-images.githubusercontent.com/107759305/175426173-483dff39-796b-4556-9e6d-e0401bbe5a58.png">

<img width="342" alt="Outcomes based on Goal_Table" src="https://user-images.githubusercontent.com/107759305/175426439-62898df1-9a9f-4161-9ad6-5f76dc95e75b.png">


When creating these graphs, mainly there were no major challenges to report. Some possible challenges could have been while creating a pivot table and the fields were entered incorrectly then the data wold not populate in the correct order. With the second deliverable, if there were errors with the countifs() function then the data for the graph may not have been valid. Additionally, if the user would forget to hide the columns that are not percentage columns, it would skew the data for the line graph, because it would be including all of the instead of just percentage related data fields. 

##Analysis of Outcomes Based on Launch Date

This graph represents data organized by Theatre Outcomes(plays) by Launch date. It provides line chart information which shows progression of canceled, failed, and successful campaigns for plays. 

Cancelled campaigns identified in yellow, are in flat line meaning that it was consistent throughout the year and does not represent high number of cancellations. The highest number was in January (7). The lowest number of cancellations was in the month of July (1), followed by April (2).

Red line shows failed campaigns. It is important to note that the highest number of failed campaigns was in May (52), and July/October (50), followed by June (49). The lowest number of failed campaigns was in the month of November (31) followed by January(33) and March(33). 

The blue line represents the number of successful campaigns. The most successful campaign was held in the month of May (166), followed by the month of June (153). The month of July(138) was 3rd most successful month. The least successful month for the number of play campaigns was in the month of December. 

###Analysis of Outcomes Based on Goals

A function, COUNTIFS() and SUM() were used to collect the outcome and goal data for the “plays” subcategory. The line graph demonstrates outcomes based on goals at various goal amount ranges. The grey line represents percentage of the canceled projects, which is flat thought out all ranges which indicates no change. 

Blue line represents percentage of successful projects. The highest percent was in the less than a 1000 range. The lowest was in the 45000 to 49999 range. 

The orange line represents the percentage of the failed projects. The highest percentage of the failed projects was in the 45000 to 49999 range, and the lowest was in the Less Than 1000 range. 


###Challenges and Difficulties Encountered

When creating these graphs, mainly there were no major challenges to report. Some possible challenges could have been while creating a pivot table and the fields were entered incorrectly then the data wold not populate in the correct order. With the second deliverable, if there were errors with the countifs() function then the data for the graph may not have been valid. Additionally, if the user would forget to hide the columns that are not percentage columns, it would skew the data for the line graph, because it would be including all of the instead of just percentage related data fields. 

##Results

-What are two Conclusions you can draw about the Outcomes Based on Launch date?

Conclusion one: The most successful campaign launch was held in the month of May (166). Since May was the most successful month, Louise should plan most of her play campaigns for the month of May and possibly use the months leading up to the month of May as a platform for advertising and market research to increase awareness. 

Conclusion two: The lowest number of failed campaigns was in the month of November (31) which indicates that this month is most suitable to start advertising upcoming launch date in May. 

-What can you conclude about the Outcomes based on Goals?

Percentage of successful vs. failed campaigns are in direct opposite correlation. When highest percentage of successful projects is less than a 1000 range, then lowest percentage of failed projects falls in the less than 1000 range. When highest percentage of failed projects falls in the 45000 to 49999 range, then lowest percentage of successful projects falls in the same range. This data shows the the best range for this campaign is in a Less than a 1000. 

-What are some limitations of this data set?

This data set was focused only on the plays subcategory. It would be great to have comparative analysis by month and country. 

-What are some other possible tables and/or graphs that we could create?

Bar graphs in 3D could add to the visual effects. Number of successful, failed and canceled campaigns could also be represented on a world map to identify comparable success of each region. 
