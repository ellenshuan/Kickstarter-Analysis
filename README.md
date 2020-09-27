# kickstarter-analysis
Performing analysis on Kickstarter data to unlock trends 

## Overview of Project

### Purpose
The purpose of this project was to be able to take a lot of raw data that contained information about film project names, blurbs, goal amount to raise, amount pledged, etc and be able to clean, filter, and graph the data to see trends such as outcomes based on goals and outcomes based on launch date,

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The way I performed this analysis Outcomes based on Launch Date is by going into the Kickstarter page and created a pivot chart in a new worksheet from the information given from the Kickstarter page. I categorised the pivot chart by placing Date Created Conversion on the Rows section as well as Outcomes in the column section. The values shown on the graph are the count of outcomes. I then filtered the category into only showing outcomes for theatre and changed the rows to be showing months. Last but not least, I showed this on a line graph. 

### Analysis of Outcomes Based on Goals
The way I performed the Analysis of Outcomes Based on Goals is by first creating a new worksheet and created a chart that showed the total number of successful, failed, and canceled projects based on the goal amount in the subcategory of plays. From there, I was able to calculate successful percentage, percentage failed, and percent canceled based on goal amount. I then highlighted selected and highlighted the columns "Goal", "Percentage Successful", "Percentage Failed", and "Percentage Canceled" and created a line graph from that information. 

### Challenges and Difficulties Encountered
Some of the challenges I encountered was learning how to do VLOOKUP and understuding the purpose of it. I also faced challenges as to making pivot tables and filtering them by dragging the correct factors into the x and y axis. This task really tested my knowledge on graphical analysis! In addition, while creating the line graph for Analysis of Outcomes Based on Goals, I encountered the issue where I forgot to include the filter of plays into my COUNTIFS function, which led to incorrect results for my graph. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
I found that in terms of theatre, outcomes of the kickstarter campaign tend to be successful in June than any other month. I also noticed that overall, the success rate for shows tends to be the lowest when the kickstarter month is at December.

- What can you conclude about the Outcomes based on Goals?
I can conclude about the Outcomes based on Goals that in terms of plays, outcomes are most successful when people set their kickstarter goal to less than $1000. I also concluded that the highest percent of failed outcome based on goals is greater than $5000. Therefore, this data suggests that for plays, it is better to set the goal at a lower price to maximise outcome. 

- What are some limitations of this dataset?
Some limitations of this dataset is knowing that there are many reasons why a film would have an outcome of success or fail, other than the amount of money kickstarter fundraiser pledged and its goals. I think it would be helpful to see more information about the number of actors and actresses, the size of the film crew, editing time, and other factors that go into creating a show or a play. 

- What are some other possible tables and/or graphs that we could create?
I think some other tables and graphs we could create could be how average donation for each film impacts outcome. We can do this by creating a graph that shows on the x axis the average donation by increments of $50, and then on the y azis show which films succeeded, failed, or got canceled based on the average amount of donation through percentage. 
