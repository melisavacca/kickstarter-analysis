# Kickstarting with Excel

## Overview of Project
Louise is hoping to be a successful playwright, and we are using collected data from previous scripts that were both successful and unsuccessful. 
We are able to compare and find trends between the budget goal for each, whether the goal was reached or was not, what country the script originated from, the timeline for each, and more. 

### Purpose
Louise wanted us to use all of this data to help guide her in creating a formnula for success with her play, Fever. We are able to find the trends that resulted in successful plays and compare them to 
the trends that resulted in unsuccessful plays. This will help us give her the best insight on budgeting, timeline, how to raise the most money, when to start fundraising, when to launch, and where to launch. We are able
to learn from others and use all of the data collected to make her as successful as possible. 

## Analysis and Challenges
The biggest challenge was making sure the filters were sorted correctly before performing any type of calculation or creating a graph. 
For the "Outcomes Based on Goals" analysis, I had to redo the COUNTIFS statements several times.  I was originally filtering the kickstarter data to only
show successful launches, and then setting the criteria to "play" in the COUNTIFS functions.  Once I noticed the outcomes were the same for successful and failed, 
I knew I had to be doing something wrong.  This is when I realized I had to include "successful" and "failed" in the COUNTIFS string. 

see screenshot:
![image](https://user-images.githubusercontent.com/64279232/123561835-c40a7880-d778-11eb-965d-afdc5dfc580d.png)

### Analysis of Outcomes Based on Launch Date
I prefer looking at this data through the line graph compared to the pivot table.  You can easily distinguish which months had the most successes (April-August) and which months
had the most failures (May-August).  
see below:
![image](https://user-images.githubusercontent.com/64279232/123561851-e3090a80-d778-11eb-98d3-c6cfca5b858b.png)

### Analysis of Outcomes Based on Goals
Fundraisers with goals less than $1000 were the most successful, and fundraisers with goals greater than $45,000 were the least successful. 

### Challenges and Difficulties Encountered
Since I am new to working with Excel in depth, some challenges were making sure I used the correct puncuation with double quotations, 
commas, and parentheses. It also took me some time to make sure I had the ranges formatted correctly. 
see below for an example: 
![image](https://user-images.githubusercontent.com/64279232/123561871-ff0cac00-d778-11eb-8395-1b669711eaa4.png)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Scripts were the most successful when launched during the spring/summer months and least successful when launched during the winter months. 
The best month to launch is May.  The worst month to launch is December.  
The most scripts canceled occured in January, and there were zero cancelations in October.
While the most successful launches occured in the spring/summer, the most failures did as well.  The spring/summer months seem to be much more active with launches
compared to the winter months.  

- What can you conclude about the Outcomes based on Goals?
The most successful launches had fundraiser goals lower than $5000.  The least successful launches had fundraiser goals greater than $45,000. 
The success/failure rate was equal for fundraiser goals in the range of $15,000-$19,999.  The rates were also equal around $35,000 and $45,000. 

- What are some limitations of this dataset?
Since the goals are sorted in intervals, you cannot determine the exact fundraiser goal by observing the data, just a range of it.  For example, you can easily 
see that the highest success rate were fundraiser goals that were less than $1000, but you cannot see the exact amount of these fundraiser goals.  You also cannot see how much money was actually pledged in 
comparison to the goals.  

- What are some other possible tables and/or graphs that we could create?
I think a bar graph would represent the "Theater Outcomes by Launch Date" well, and I think a histogram would represent the "Outcomes Based on Goals" data well, especially since it is already organized in intervals.
Here is an example of what the data could look like for "Theater Outcomes by Launch Date" in bar graph form. 
See below: 
![image](https://user-images.githubusercontent.com/64279232/123561887-151a6c80-d779-11eb-8202-69d7bf3bacb9.png)
