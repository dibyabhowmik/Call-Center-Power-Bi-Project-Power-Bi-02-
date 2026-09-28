Project Overview:
This project focuses on analyzing call center operations using Power BI. The objective was to understand call volume, customer satisfaction, call resolution, agent performance, response rates, and call patterns across different topics, months, and days.
The dataset contains 5,000 call records with information about agents, dates, call topics, answered status, resolution status, response time, talk duration, and customer satisfaction ratings.
The dashboard is divided into three main sections:
Executive Overview
Call and Customer Insights
Agent Performance
Interactive filters for Topic, Month, and Agent allow users to explore the dashboard based on different segments.

Objectives:
The main objectives of this project were:
Analyze the overall call center performance.
Measure answered, unanswered, and resolved calls.
Calculate the overall answer rate.
Understand customer satisfaction across different topics and agents.
Analyze call volume by month and day of the week.
Compare call volumes and resolution performance across topics.
Evaluate individual agent performance.
Identify patterns in customer satisfaction ratings.
Analyze average call duration and response-related metrics.
Build an interactive dashboard to support call center performance monitoring.
Tools & Technologies Used
Power BI – Dashboard creation and data visualization
Power Query – Data cleaning and transformation
DAX – Measures and KPI calculations
Microsoft Excel – Dataset and initial data handling
Data Analysis Process
1. Data Collection:
The Call Center dataset was imported into Power BI.
The dataset contains fields such as:
Call ID
Agent
Date
Time
Topic
Answered (Y/N)
Resolved
Speed of Answer
Average Talk Duration
Satisfaction Rating
Average Duration in Seconds
2. Data Cleaning:
The dataset was reviewed to ensure that the fields were correctly formatted and suitable for analysis.
The main preparation steps included:
Checking data types.
Converting date and time fields appropriately.
Preparing call duration for numerical analysis.
Creating month and day-name fields from the date.
Validating answered and resolved call statuses.
Checking satisfaction rating values.
Preparing categorical fields such as Topic and Agent for filtering.
3. Data Transformation

Additional measures and calculated fields were created to analyze:

Total calls
Answered calls
Unanswered calls
Resolved calls
Answer rate
Average call duration
Average satisfaction rating
Calls by topic
Calls by month
Calls by day
Calls by agent
Resolution performance
Satisfaction distribution
4. Dashboard Development

The analysis was organized into three dashboard pages.

The dashboard uses KPI cards, bar charts, line charts, donut charts, and interactive slicers to make the analysis easy to explore.

Dashboard 1: Executive Overview

The Executive Overview provides a high-level view of the call center's operational performance.

The key KPIs are:

Total Cases: 5,000
Unanswered Calls: 946
Average Duration: 3.7 minutes
Average Rating: 3.40
Resolved Calls: 3,646
Answer Rate: 81.1%

The calls-over-time visualization shows that call volume fluctuates throughout the January–March 2021 period rather than following a consistent upward or downward trend.

The answered versus unanswered analysis shows that approximately 81.1% of calls were answered, while 18.9% remained unanswered.

The satisfaction distribution shows that ratings of 3 and 4 account for a large proportion of customer responses, followed by ratings of 5. Ratings of 1 and 2 occur less frequently.

The topic analysis shows that call volumes are relatively evenly distributed across the five major topics:

Streaming – 1,022 calls
Technical Support – 1,019 calls
Payment Related – 1,007 calls
Admin Support – 976 calls
Contract Related – 976 calls

This indicates that no single topic overwhelmingly dominates the overall call volume.

Dashboard 2: Call and Customer Insights

This section focuses on call volume, customer satisfaction, and call patterns.

The Streaming topic has the highest number of calls with approximately 1,022 cases, closely followed by Technical Support with 1,019 cases.

The resolution analysis shows:

Streaming – 749 resolved calls
Technical Support – 736 resolved calls
Payment Related – 729 resolved calls
Admin Support – 723 resolved calls
Contract Related – 709 resolved calls

Customer satisfaction remains relatively consistent across the different topics, with average satisfaction values around 3.4.

The monthly analysis shows that:

January: 1,772 calls
February: 1,616 calls
March: 1,612 calls

January therefore has the highest call volume in the dataset.

The day-of-week analysis shows that Monday has the highest call volume with approximately 770 calls, followed closely by Saturday with 768 calls.

Tuesday has the lowest call volume with approximately 675 calls.

Dashboard 3: Agent Performance

The Agent Performance dashboard evaluates individual agents based on call volume, satisfaction, resolution activity, and performance status.

The dataset contains eight agents:

Becky
Dan
Diane
Greg
Jim
Joe
Martha
Stewart

Jim handled the highest number of calls, with approximately 666 calls, while Joe handled approximately 593 calls.

Average customer satisfaction by agent is relatively close across the team. Martha has an average satisfaction score of approximately 3.47, while Joe has approximately 3.33.

Other agents remain within a similar range, indicating that customer satisfaction is relatively consistent across the team.

The dashboard also includes a performance-status breakdown showing the distribution of calls across:

Needs Attention
High Performer
Average Performer

The resolution-rate visualization provides an agent-level comparison of these performance groups and helps identify differences in resolution activity across the team.

Key Insights:
Some of the major insights from the analysis are:
The call center handled 5,000 calls during the analyzed period.
4,054 calls were answered, resulting in an answer rate of approximately 81.1%.
946 calls were unanswered, representing approximately 18.9% of total calls.
3,646 calls were resolved.
The average call duration was approximately 3.7 minutes.
The overall average customer satisfaction rating was approximately 3.40 out of 5.
Call volumes are relatively evenly distributed across the five major topics.
Streaming generated the highest call volume, with 1,022 calls.
January recorded the highest monthly call volume with 1,772 calls.
Monday had the highest call volume among the days of the week.
Customer satisfaction is relatively similar across different topics and agents.
Jim handled the highest number of calls among the agents.
Martha recorded the highest average satisfaction score among the agents.
Satisfaction ratings of 3 and 4 were the most common responses.
The dashboard shows that call center performance can be evaluated from multiple dimensions rather than relying only on total call volume.
