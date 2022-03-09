# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
![pivot_chart](https://user-images.githubusercontent.com/99696816/154185446-6c08184d-6a4d-4eea-9e37-9ff81e34e894.png)
![outcomes_chart](https://user-images.githubusercontent.com/99696816/154185573-06e32e9c-ba62-45c8-a2e9-00161e287dad.png)
# KickStarting with Excel
Gathering the appropriate campaign statistics to sponsor a new theatrical play is one of the most difficult components of fundraising a new play. Louise is a fresh playwright who wants to learn from past successful theatrical crowdfunding projects in order to boost the success of her own. To find these successful elements, this project will use Excel to organize, sort, and analyze crowdfunding data.
# Overview of Project
Purpose
Louise's performance Fever met its fundraising goal in a short length of time, and Louise wants to know how previous campaigns went in order to improve the success of her theatrical fundraising goals. This analysis will entail the creation of two technical analyses as well as a written report outlining the findings.
# Analysis and Challenges
Analysis of Outcomes Based on Launch Date

I utilized a pivot table to visualize the campaign outcomes – successful, unsuccessful, and canceled – against the launch date to conduct this data analysis of Deliverable 1. The column labels of three "Successful," "Failed," and "Canceled" outcomes were displayed using a data filter. To choose "Theater" and Years, a filter was applied to Parent Category. The results column was created, and the Date Created Conversion rows were created. The pivot table values, which were the count of the outcomes, were the result. The data correlation between the Launch date on the x-axis and the Outcome count on the y-axis was visualized using a line chart. When looking at the graph, it is clear that there was a significant peak of 109 successful theater campaigns in July.

![Theater_Outcomes_vs_Launch-1](https://user-images.githubusercontent.com/99696816/157382363-d7862854-eeb0-4b17-b320-6557125549de.png)

 
Analysis of Outcomes Based on Goals

I used a pivot table to visualize the percentage outcomes – successful, unsuccessful, and canceled plays – based on the financing goal amount of a line chart for this Deliverable 2 data analysis. The chart heads of Goal, Number of Successful, Failed, and Canceled projects, and the percentage of Successful, Failed, and Canceled projects were used to construct a table. The percentage of these outcomes was calculated using the COUNTIFS() function. The Total Projects column was filled with the proportion using the SUM() function. The largest rate of successful plays occurred with a goal of less than $1000, according to the line chart. The failed plays with the highest percentage of failed plays raised the most money, ranging from $45,000 to $49,999.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99696816/157382557-90ceece1-51d7-44c4-8c6e-327bc2ee7500.png)

 
Challenges and Difficulties Encountered

One of the most difficult challenges I faced during my analysis of this First Challenge exercise was correctly calculating the COUNTIFS() function in the second deliverable. I discovered this function to be challenging and time-consuming in order to the get the correct range for the goal amount, the correct subcategory, and outcome. I encountered challenges in utilizing the pivot charts to visualize the line charts, so I had to review previous module exercises in order to properly utilize this pivot chart application. 
Results
What are the two conclusions you can draw about the Outcomes based on Launch Date?
•	Upon reviewing the line chart, I noted that there was a significant peak of 109 successful theater campaigns in July and it would be ideal to launch a campaign in July compared to other months of year.
•	The second conclusion is that failed plays do not vary much based on launch date, indicating that there is no other factor that would affect the campaign outcomes.
