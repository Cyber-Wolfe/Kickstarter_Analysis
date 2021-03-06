# Kickstarting with Excel

## Overview and Purpose of Analysis
The purpose of this file is to illustrate to Louise how her kickstarter compared to many other play's kickstarters over the years. I had created charts and tables used to calculate the competition's successes and failures as their plays had been crowdfunding. Charts had been created to help visualize the data so that it can be easily digestible for Louise and an explaination disconnect won't occur.

## Analysis and Challenges
What was done for this file is that the different analysees were sorted onto seperate sheets with various parameters in mind. One sheet the outcomes had been split into tiers based on the goal in mind for the project and broken down again based on a success, failure or cancelated on the play.
Following this was a smaller analysis on Parent Category and their outcomes of successes, failures, or cancelations as well as another break down of the Parent Catgory but shown with a Bar chart for easier understanding. Another sheet called Subcategory Statistics breakdowns subcategories by country, giving a simple bar graph to show the size of the failures, successes, and current live shows. These graphs depict each sheet respectively.
![Parent_Category_Outcomes](https://github.com/Cyber-Wolfe/Kickstart_Analysis/blob/main/Resources/Parent_Category_Outcomes.png) 

![Subcategory_Statistic_Bargraph](https://github.com/Cyber-Wolfe/Kickstart_Analysis/blob/main/Resources/Subcategory_Statistic_Bargraph.png)

There was another requested analysis to find plays in Edinburgh and have a breakdown of the play name, description, the goal amount, pledged amount, average donation and number of backers.  Giving Louise an idea of her competition and their own success or failures for their project. Lastly an analysis of the outcomes from the Theatre categroy based on their launch date, giving Louise an idea of a better time to launch her play, whether cold months or warm months affect the success of a play or not.
![Theatre_Outcomes_vs_Launch](https://github.com/Cyber-Wolfe/Kickstart_Analysis/blob/main/Resources/Theatre_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Launch Date
The first conclusion I had come to with the data is that during May there are the most sucessful plays out of any month in the year and it tapers down towards August with a number comparable to February. May is probably a good month for these plays because that somewhat begins the summer mindset for people and being out of the house is much more pleasant than compared to the cold months like November to February and even March.
The second conclusion I had come to is that December is the month with the least amount of plays and an almost even split of successful and failed plays. One can assume that month people are more busy with the last quarter work push, their own finances for the coming tax months, the various holidays and so on that plays and their funding campaigns are not a priority for people to be supporting.

### Analysis of Outcomes Based on Goals
Based on the data we have the ranges for goals have very different outcomes, some have absolute great performance metrics others do not. Thise data seems to show that from $19,999 back to $100 has a lower percentage of success than $20,000 to $50,000.  Problem is even with that idea in mind the amount of campaigns that happen in that first grouping far excedes that second grouping. From $19,999 to 0 there are 985 compared to the only 56 from $20,000 and higher so the data shows there are more successes by percentile in the higher areas than the lower but that really isn't a strong argument for those funding goals.

### Dataset Limitations
The dataset limits itself to only campaigns, goals, and their success or failure. I think having more data on whether the play had done well or not along with their kickstarter goal could be useful to see analyzed for Louise. Having an idea of whether the amount of money kickstarted for each play was enough to cover the costs of working on the production and if the goal pledged amount correlated to the successfulness of the play itself would be very useful data. That data could gauge how high her goal could be compared to what others had reached and their success with that money.
Another limitation would be that as I said in my previous analysis of the outcomes based on goals, I think the analysis is good but the chart shouldn't be a line chart but maybe a clustered column chart instead like so:
![Outcomes_vs_Goals_Cluster](https://github.com/Cyber-Wolfe/Kickstart_Analysis/blob/main/Resources/Outcomes_vs_Goals_Cluster.png)
This provides a much clearer comparison than the line chart because it gives a side by side comparison of the goal tiers and their outcomes(canceled was omitted because there were no canceled campaigns).  Percentiles I think are great but only if the data acquired is close to each other in amount of entries otherwise it skews the chart. It disregards the fact that the first half of the set has 70 to 190 times more entries than the second half.

