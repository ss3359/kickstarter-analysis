# Kickstarting with Excel

## Overview of Project
Kickstarter is a website focused on crowfunding that is targeted towards creativity. Their mission statement is to help bring "creative projects to life". 
In this project, we comapre different Kickstarter campaigns in the context of plays. 

### Purpose
The purpose of this project is to examine how different Kickstarter campaigns, that had to do with plays, fared in regards to their launch dates and funding goals. 

## Analysis and Challenges
Using the Data on the Excel document, we have generated line graphs which display outcomes of Kickstarter campaigns with respect to their launch dates and thieir funding goals. 
We are reviewing the outcomes for the plays in regards to their launch dates by month, and their funding goal. We have constructed line graphs to see the observations for these types of scenarios. The major challenges was to look up some of the functions presented in Excel. In particular, I researched the function COUNTIFS() in detail. Excel is case sensitive, so it was very important to get the formating and the syntax properly in order to generate the tables and graphs. The thing we made sure was that the data was calculuated how I wanted to be calculated. According to Fever, the funding goal just came a bit short 

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/104328106/175077890-3df1cacc-73cf-4a0e-8edd-e7ee9660dec4.png)
The first piece of analysis to observe is the line chart displaying the number of outcomes based on the launch date. This is indicated with a line graph shown labeled "Theatre Outcomes vs Launch". In order to accomplish this, we have created a pivot table on a new spreadsheet. Then, we have labed out the rows by using the date when the Kickstarter projects were created. Next, we have filtered the pivot table by category and the years so we can get the data we want from Kickstarter campaigns in plays. Next, we labeled the row of the chart as the month of Kickstarter launch date. 
Based on the data, we have a spike of kickstarter campaigns being sucessful on the month of May. The month with the lowest percentage of success is Decemeber. As opposed to the data with failed funded kickstarter campaigns, the spike occurs on the month of October. Louise's play lauch date was at June 13th, 2016. Based on this data, it seems the best time to lauch a Kickstarter campaign covering a play is on May. However, lauching a kickstarter campaign in October would not be the best time. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/104328106/175077940-a84d9542-e1c8-4a74-affe-73c7bff2cbf1.png)
The second piece of anaysis to look at is how the outcomes fared in regards to their respective funding goals. This graph is indicated as a line graph labeled "Outcomes Based On Goals". To generate this graph, we first had to generate a collumn which separates the funding goals by intervals. Then, we have used the COUNTIFS() function to filter the number of sucessful, failed, and cacnceled plays whose funding goal met the indicated range highlighted in the collumns. These will generate the number of plays that were sucessful, failed, and canceled that are indicated in the corresponding collumns. Next, we have computed the percentages of campaigns that were successful, failed and the projects canceled. Finally, we have generated a line graph that represents the percentages for the indicaed funding goals.  
Based on the data, the highest percentage of the campaigns funded are the campaigns that have a funding goal in between $0 and $5000. The biggest percent of failures occur at funding goals between $25,000 and $29,999. In Louise's play, Fever, the funding goal was set at $2,885. What is interesting is the funding goal belongs to the group that produced the lowest failure percentage. Finally, I would love to plot in the number of backers for the kickstarter campaigns.  

### Challenges and Difficulties Encountered
One of the major challenges encountered was setting up Pivot Tables and fitting the proper Pivot Chart corresponding to the Pivot Tables. We had to select the appropriate filter, collumn and row in order to best visualize the data generated for plays with respect to their funding goals and launch dates.  
There were some challenges encountered while working on this assesment. Another obstacle that I needed to master was practing to make pivot tables and pivot charts. We has to make sure we are computing the data exactly as we needed. 

The interesting thing about this project was working on a dataset that was not up to date. In other words, we were using data for plays whose launch dates were between in the years 2009-2017. Therefore, the pivot tables and the charts are not that accurate. For a much deeper analysis of this data, we could have gathered data that is generated for plays after 2017 up until the present year. 


## Results

The major thing is that the maximum percentage of sucesses in Kickstarter campaigns is when the launch date was in May. In Louise's play, Fever, the launch date was in June, which started the decline in sucesses percentages. Also, the decrease of the number of sucessful Kickstarter campaigns was not sharp, as opposed to the number of sucessful projects in January, or in February. The question people have to ask themselves is what is the best and times to lauch a Kickstarter project? The best time to launch a kickstarter project is on May. Conversely, launching a project on October would not be the best time. Also, a major limitation is that since the amount of data was gathered for a limited amount of years, it might not be enough data to draw some conclusions about the Kickstarter campaigns. Out of the 4115 Kickstarter campaigns, only 3594 campaigns were plays occuring in a theater. The more data points acquired, the better of our results that fit our claims. 

The projects whose funding goal was set in between 0 to 4999 had the highest percentage of campaigns funded. According to Louise's play, she had set a funding goal at 2,885. Some of limitiations of this dataset was figuring out the average amount of donations for each backer for the Kickstarter campaign. We would like to know if there was a minimumum amount of money that has to be donated. Also, if there were funding tiers attached to the kickstarter campaign. For example, if someone donated $10, they could get a free play merchandise. Another factor that can come into play is if their creator of the kickstarter campaign listed out any descriptive risks and challenges during the creation and construction of the play. We would like to find out what day of the week the Kickstarter campaign was supposed to launch.

In this project, we are looking at how various Kickstarter campaigns differ from each other by Categories and Subcategories. Some of the graphs we could introduce is line graphs that showed a comparision between each category or subcategory in each Kickstarter campaign. 
Since we are dealing with a number of outcomes, this would be a quantitative dataset. In this context, other possible graphs we could have made is a scatter plot. 
