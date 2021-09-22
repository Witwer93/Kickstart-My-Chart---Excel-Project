Kickstart My Chart - An Excel Project

Background:
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. For this week's homework, you will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

Instructions:
1. Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.

Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Here's a picture of the excel before and after the conditional formatting:

2. Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.
3. Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.
4. Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.
5. Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.
6. Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category.**
7. Create a stacked column pivot chart that can be filtered by country based on the table you have created.
8. Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category.**
9. Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.
10. The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.
11. Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.\
12. Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.
13. Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.
14. Now create a pivot chart line graph that visualizes this new table.

Create a report in Microsoft Word and answer the following questions.

Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?

Here is my report:

1.	Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
One conclusion we can draw about Kickstarter campaigns that stands out is that they have a higher success rate at the beginning of the year relative to the end of the year. This data shows that the number of successful Kickstarter campaigns always peaks in the first six months of the year and consistently hits its lowest point in the last six months of the year. 

The average rate of success for any given Kickstarter campaign is approximately 53% according to this data set. However, this data set reveals that success rate has high variance depending on the category and subcategory of the Kickstarter campaign. For example, this data shows Kickstarters in the music category have the highest rate of success at around 77%, whereas Kickstarters in the food category have a success rate of only 17%. These two categories are outliers, but in all, six of the nine categories have a variance of at least 10-20%.

This data set also indicates that trying to get funding for certain sub-categories of Kickstarters is a fruitless endeavor. Food trucks, animation, and video games all had at least 100 Kickstarter campaigns and all 3 sub-categories have 0% success rates. Wearable technologies also only had a 5% success rate out of 200 total Kickstarter campaigns. On the other hand, this data set shows that Kickstarter is a good place to get funding for theater projects, or more specifically for plays. Not only do theater projects have a respectable 65% success rate overall, they also account for almost 34% of all Kickstarter campaigns. 

2.	What are some limitations of this dataset?

The total number of Kickstarter projects was significantly smaller between 2009 and 2013, and there is almost a 400% jump in total projects from 2013 to 2014. Additionally, there is nothing indicating how much visibility each project had to the public outside of the Spotlight and Staff’s Choice columns. Visibility might have a big impact on a project’s chances of success particularly if it has a small goal. Finally, The sample size of all projects between 2009 and 2017 is only 4114, which makes it harder to identify trends with 100% certainty. A larger total number of projects would improve the reliability of predictions based on the data set.
 
3.	What are some other possible tables and/or graphs that we could create?

  1.	A bar graph showing average goal size for categories and subcategories
  2.	A bar graph showing the average size of donations per category/sub-category
  3.	A line graphs that show number of donations per month 
  4.	A pivot table that examines success rate, goal size for each category
  5.	A line graph that tracks success rates for categories/sub-categories over months/years
  6.	A bar graph comparing success rate to Spotlight/Staff’s Choice.
