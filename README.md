# Kickstarting with Excel
Dear Louis. This is Manuel, your data science expert. Right now I´m going to explain to you the attached report and chart.
First of all, thank you for choosing us for this job. We were told that you were close to your fund goal of the theater and musical projects through a Kickstarter campaign.  
## Overview of Project  
For this project we wanted to take advantage of all the data we were provided by Kickstarter in order to know how different campaigns fared in relation to their launch dates and their funding goals. We studied two aspects:  
- Outcomes Based on Launch Date  
- Outcomes Based on Goals  
### Purpose
The main goal for any data vizualition is to give an idea on how we can predict next data. So for your project Louise, in order to succeed we need to be able to tell you how you are most likely going to succeed or fully funded. As said before, we want you to know the best months of the year for fund raising and the best and realistic goals.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to succeed on getting a theater project funded we highly recommend you to follow the tendencies of successful campaigns within your interests. In the following chart we will show you the following conclusions:  

![Theater_Outcomes_vs_Launch](https://github.com/ManuelRuizF/kickstarter_analysis_challenge/blob/main/resources/Theater_Outcomes_vs_Launch.png)  


In this chart we can see that the best months to launch a campaign are May, June and July. May being the best month and June the second best.  
Also, the chart shows the worst months to launch. December, January, February and March. We think these are the worst since it´s a time of the year were people spend their money the most. For holidays for example. December is the worst since our successful percentage is the lowest on the chart.  
### Analysis of Outcomes Based on Goals
In order to succeed, we highly recommend you to follow the tendencies of successful campaigns within your interests. In the chart we will show you what we found on the outcomes of the different goals for each project of your interest: 

![Outcomes_vs_Goals](https://github.com/ManuelRuizF/kickstarter_analysis_challenge/blob/main/resources/Outcomes_vs_Goals.png)  

In this chart, we can observe that there are 2 peaks. The first one are backers that offer just a few money (less than 1000). And the other type of backers are big ones. The ones that spend great amount of money (35,000 - 44,999). After that range the percentage of success drops to the bottom.  
### Challenges and Difficulties Encountered  
The original data collected had some format issues in some columns. We changed the UNIX format of the date to the original long date format in order to arrange  the data so anyone can understand the dates.
Also, the categories and subcategories were in the same column. This was a really important step since we used the subcategories in all of the charts! With the "text in columns" option we were able to successfully separate the data in 2 columns, which we named "Parent Category" and "Subcategory".
## Results  
According to this chart. Kickstarter campaign projects tend to be successfully funded the most on the months of May, June and July . So our tip is the be ready to launch by the end of April. As a second conclusion, you might want to avoid winter holiday season.December is the worst since our successful percentage is the lowest on the chart. And January and February aren´t too far.  
For the outcomes based on goals we conclude that there are 2 types of backers or backed projects. The low goal ones (less than $1000), and big backers ($35,000 - $44,999). You might want to study if your projects can be funded within these two ranges.  
As a limitation I feel like we never lacked data. It was actually the other way. We had too much data and the magic of our skills and the program was to sort or filter it as we were needing it. That depended on what we were studying.  
Since we had a lot of data we were able to use a huge amount of the software tools. We could also create a Box & Wiskers chart to show the outliers and study why they were like that. 
