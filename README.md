British Airways Customer Reviews | Tableau Dashboard
An interactive customer review analysis project built with Tableau Public to explore passenger satisfaction with British Airways across service categories, travel periods, countries, aircraft types, and passenger segments.
Project Overview
This project explores a dataset of British Airways customer reviews and presents the findings through an interactive Tableau dashboard. The dashboard allows users to investigate overall customer ratings and compare service performance across different dimensions, including cabin staff service, entertainment, food and beverages, ground service, seat comfort, and value for money.

It also provides time-based, geographic, and aircraft-level views to help users explore how passenger feedback varies across the selected filters.
Business Objectives
- Evaluate overall passenger satisfaction with British Airways.
- Compare customer ratings across key airline service categories.
- Track changes in service ratings over time.
- Explore differences in customer feedback across countries.
- Compare cabin staff service ratings by aircraft type.
- Examine review volumes across aircraft categories.
- Explore feedback by traveller type, seat type, aircraft group, and continent.
- Support evidence-based discussions about customer experience and service improvement.
Tools & Technologies
Tool	Purpose
Tableau Public	Data visualization and interactive dashboard development
Tableau Calculated Fields	Creating analytical measures and supporting comparisons
Tableau Filters & Parameters	Enabling dynamic exploration of customer reviews
Geographic Visualization	Exploring review metrics across countries


Key Performance Indicators
The dashboard displays the following average ratings:
KPI	Average Rating
Overall Rating	4.2
Cabin Staff Service	3.3
Entertainment	1.4
Food & Beverages	2.4
Ground Service	3.0
Seat Comfort	2.9
Value for Money	2.8


These values are taken from the dashboard screenshot. They represent the displayed averages and may change when filters are applied.
Dashboard Features
1. Customer Rating Overview
A KPI section summarizes the average passenger ratings across the main service categories. It provides a quick view of overall satisfaction and highlights differences between service dimensions.
2. Metric Selector
The Pick a metric control allows users to choose which service measure to investigate. Available measures shown in the dashboard include:
- Overall Rating
- Cabin Staff Service
- Entertainment
- Food
- Additional service measures represented in the KPI section
The selected metric drives the related time-series and country-level analysis.
3. Service Ratings by Month
A time-series chart tracks the selected average service rating over time. The dashboard includes a date-range control covering March 2016 to October 2023 in the displayed view.

This analysis helps users explore trends, fluctuations, and periods that may deserve further investigation.
4. Service Ratings by Country
A geographic map visualizes the selected service metric across countries. It supports geographic comparisons and helps identify differences in passenger feedback between markets.
5. Service Ratings by Aircraft
A horizontal bar chart compares average cabin staff service ratings across aircraft types, including:
- Boeing 777-200
- A380
- Boeing 787
- A321
- A319
- Boeing 747-400
- Boeing 747
- A320
- Boeing 777
- Various
The accompanying review-count bars provide additional context about the volume of feedback associated with aircraft categories.
Interactive Filters
The dashboard includes several controls that allow users to refine the analysis:
- Metric selector: choose the service rating to analyze.
- Month of Date: select a date range.
- Traveller Type: filter by passenger/traveller category, such as Business and Couple Leisure.
- Seat Type: filter by cabin class, including Business Class, Economy Class, and First Class.
- Aircraft (group): focus on a selected aircraft group.
- Continent: filter the geographic analysis by continent.
The charts update according to the selected metric and filter context, allowing users to explore specific passenger segments.
Questions This Dashboard Helps Answer
- What is the average overall rating for British Airways?
- Which service categories receive higher or lower average ratings?
- How do service ratings change over time?
- How does passenger feedback vary across countries?
- Which aircraft types have higher average cabin staff service ratings?
- How does the number of reviews vary by aircraft type?
- Do ratings differ by traveller type or seat class?
- How do customer ratings vary across geographic regions?
The dashboard is designed to help investigate these questions. Any conclusions should be checked against the underlying data, review counts, and active filter selections.
Suggested Repository Structure
British-Airways-Reviews-Tableau/
│
├── README.md
│
├── Dashboard/
│   └── British_Airways_Reviews.twbx
│
└── Images/
    └── british-airways-dashboard.png
Update the workbook and image filenames to match the files uploaded to your repository. If the dashboard is published on Tableau Public, add its public URL below:

Tableau Public Dashboard: Add your published dashboard link here.
How to Explore the Project
1. Clone or download this repository.
2. Open the Tableau workbook (.twb or .twbx) in Tableau Desktop, or visit the published Tableau Public dashboard.
3. Choose a service metric from the Pick a metric control.
4. Adjust the date range to focus on a particular period.
5. Use the Traveller Type, Seat Type, Aircraft Group, and Continent filters to explore specific segments.
6. Compare the time-series, country map, and aircraft charts to investigate customer feedback from different perspectives.
Skills Demonstrated
- Customer review and satisfaction analysis
- Exploratory data analysis
- KPI analysis and interpretation
- Data visualization with Tableau
- Interactive dashboard development
- Calculated fields and dynamic metric selection
- Time-series analysis
- Geographic analysis and mapping
- Comparative analysis across customer segments
- Business-focused data storytelling
Author
Abdelrahman Hamdi
Aspiring Data Analyst
This project demonstrates how Tableau can transform airline customer review data into an interactive dashboard to support customer experience analysis and service performance evaluation.
