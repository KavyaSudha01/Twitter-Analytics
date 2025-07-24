# 📊 Twitter Analytics using PowerBI
An interactive, real-time dashboard built in Power BI to monitor, analyze, and visualize engagement insights from Twitter data. This project uses complex business logic and time-based filters to dynamically control the visibility of charts and deliver meaningful, action-oriented analytics.

## Project Objective
To build a feature-rich Twitter analytics dashboard that helps analyze tweet performance across different metrics (likes, retweets, impressions, media engagement, etc.) and generate advanced, time-sensitive insights for decision-making.

## Internship Tasks
-**Task 1**: Develop a chart that displays tweets with the highest engagement rates (top 10%). Include only those tweets that have received more than 50 likes and were posted on weekdays and this graph should work only between 3PM IST to 5 PM IST apart from that time we should not show this graph in dashboard itself as well as tweet character count should be below 30.

-**Task 2**: Plot a scatter chart to analyse the relationship between media engagements and media views for tweets that received more than 10 replies. Highlight tweets with an engagement rate above 5% and this graph should work only between 6PM IST to 11 PM IST apart from that time we should not show this graph in dashboard itself and the tweet date should be odd number as well as tweet word count be above 50.

-**Task 3**: Analyse tweets to show a comparison of the engagement rate for tweets with app opens versus tweets without app opens. Include only tweets posted between 9 AM and 5 PM on weekdays andthis graph should work only between 12PM IST to 6PM IST and 7 AM to 11AM apart from that time we should not show this graph in dashboard itself and the tweet impression should be even number and tweet date should be odd number as well as tweet character count should be above 30 and need to remove tweet word which has letter 'D'.

## Dataset
- <a href="https://github.com/KavyaSudha01/Twitter-Analytics/blob/main/Tweet.xlsx">Dataset </a>

## Techonologies Used
Power BI Desktop – For creating the dashboard and visuals

Power Query (M language) – For data transformation and filtering

DAX (Data Analysis Expressions) – For calculated columns and dynamic measures

Custom Time Logic – For conditional chart visibility based on IST

## Process Overview
Data Cleaning – Removed irrelevant characters, nulls, and duplicate rows.

Feature Engineering – Calculated engagement rate, extracted tweet time/date info, applied conditions like odd/even and word/character count.

Time Logic Setup – Built DAX measures to detect system time and control visual visibility.

Chart Development – Created dynamic bar, pie, scatter, and line charts.

Dynamic Filtering – Applied business logic to filter visual content based on real-time criteria.

## Dashboard Highlights

Weekday trends of tweets and impressions

Media views vs engagements breakdown

Top-performing tweets by URL clicks

Dynamic visibility of charts based on time window

Pie chart for hashtag/user clicks

KPI cards for retweets, likes, views, and engagement 
<a href="https://github.com/KavyaSudha01/Twitter-Analytics/blob/main/Twitter%20Dashboard.png"> View DashBoard </a>

## Internship Task Summaries
| **Task**   | **Visualization**       | **Description**                                                                                                                                                                                                                                                                                                                      |
| ---------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <a href="https://github.com/KavyaSudha01/Twitter-Analytics/blob/main/Task%20One.png"> View Task 1 </a>| 📊 Bar Chart            | Displays the **top 10% tweets with highest engagement rates.**
| <a href="https://github.com/KavyaSudha01/Twitter-Analytics/blob/main/Task%20Two.png"> View Task 2 </a> | 🟢 Scatter Chart        | Analyzes the **relationship between media engagements and media views.**         |
| <a href="https://github.com/KavyaSudha01/Twitter-Analytics/blob/main/Task%20Three.png"> View Task 3 </a> | 📉 Horizontal Bar Chart | Compares **engagement rate for tweets with app opens vs. without app opens.**


## Conclusion
This Twitter Analytics Dashboard showcases advanced Power BI features such as DAX time logic, dynamic filtering, and effective data storytelling. It successfully meets the requirements of all three internship tasks, simulating real-world data challenges and business logic.

Special thanks to NullClass for providing this hands-on opportunity to build practical data analytics skills and work on an industry-relevant project.

## Author
Golla Kavya Sudha

NullClass Twitter Analytics using PowerBi

<a href="https://www.linkedin.com/in/golla-kavya-sudha-64477a290/" >LinkedIn </a>

Mail: "gollakavyasudha01@gmail.com"

<a href="https://github.com/KavyaSudha01"> GitHub </a>
