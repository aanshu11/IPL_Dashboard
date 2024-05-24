# IPL Live Score Dashboard

## Overview

Welcome to the IPL Live Score Dashboard project! This Power BI project aims to deliver in-depth analysis of Indian Premier League (IPL) data, providing real-time insights into batting, bowling statistics, and historical match performance. The dashboard is designed to give cricket enthusiasts and analysts a comprehensive view of live match statistics, player performances, and team standings.

## Problem Statement

The primary objectives of this project are:
- Identify the current score of ongoing matches.
- Track the number of sixes and fours scored by each player.
- Analyze the number of wickets taken by bowlers.
- Calculate the run rate of players.
- Create a points table displaying team standings, including the number of matches won, lost, and their net run rate.

## Features

- **Live Dashboard:** Real-time updates on batting and bowling performances during matches.
- **Team Standings and Points Table:** Comprehensive view of team standings and points table, including match results and net run rates.
- **Visualization:** Intuitive and visually appealing representation of data using Power BI's advanced visualization capabilities.

## Steps Followed

- **Data Acquisition via Rapid API:**
  - Established a connection to the Rapid API to seamlessly fetch real-time IPL data. This integration ensures continuous and up-to-date data flow into our Power BI model, capturing the latest match statistics and player performances.

- **Initial Data Ingestion and Processing in Power Query:**
  - Utilized Power Query to import the raw JSON data into Power BI. Performed preliminary data transformation tasks including expanding records, renaming columns for better readability, and structuring data into appropriate tabular formats for further analysis.

- **Comprehensive Data Cleaning and Transformation:**
  - Implemented rigorous data cleaning techniques to handle null values, outliers, and irrelevant records. Applied filters to extract pertinent information. Created additional calculated columns to facilitate deeper insights. Utilized Power Query’s M language for advanced data manipulation.

- **Handling Missing Visual Elements:**
  - Developed a robust mechanism to check for and handle missing images in the dataset. Replaced absent images with standard placeholder visuals to maintain the aesthetic integrity of the dashboard and ensure a consistent user experience.

- **Compilation and Integration of Player Metrics:**
  - Aggregated detailed datasets for batsmen and bowlers, incorporating various performance metrics such as runs scored, strike rates, wickets taken, and economy rates. This integration supports comprehensive player analysis within the dashboard.

- **Design and Implementation of Interactive Live Dashboard:**
  - Crafted a dynamic and interactive dashboard using Power BI’s visualization tools. Incorporated real-time data feeds to showcase ongoing match statistics, including live scores, batting and bowling performances, and key match events. Designed intuitive slicers and filters to enhance user interactivity.

- **Development of Points Table Visualization:**
  - Constructed a detailed points table visualization to display team standings. This included metrics such as matches played, won, and lost, along with net run rate calculations. Employed DAX (Data Analysis Expressions) to compute these metrics accurately.

- **Implementation of Contextual Tooltips:**
  - Enhanced the dashboard with tooltips to provide additional context-specific information on batsmen and bowlers. This feature allows users to hover over data points and access detailed statistics and insights without cluttering the main visual space.

- **Creation of Advanced DAX Measures:**
  - Developed a suite of complex DAX measures to facilitate advanced calculations. These measures include run rates, batting averages, economy rates, and performance indices, enabling granular analysis and insights derivation from the dataset.

## Live Dashboard

The IPL Live Dashboard is designed to provide a comprehensive and engaging view of ongoing matches. Here are some snapshots from the dashboard:

### Eliminator Match

![Eliminator Match](https://i.postimg.cc/7h8YjV2J/IPL-Dash-Snip-Scorecard-1.png)

### Tooltip

![Tooltip](https://i.postimg.cc/TYTDtVvH/Screenshot-45.png)

### Points Table

![Points Table](https://i.postimg.cc/Kv9RQCNR/Points-Table-snip.png)


## Data Source

The data for this project is sourced from an API providing real-time IPL match data. The API delivers structured data in JSON format, including match scores, player statistics, and team performance metrics. Utilizing this data ensures that the dashboard is always up-to-date and reflective of the latest match outcomes and player performances.

## Tech Stack

- **Power BI:** For data visualization and dashboard development
- **DAX (Data Analysis Expressions):** For data manipulation and calculations
- **Power Query:** For data transformation and cleaning
- **API Integration:** To fetch real-time IPL data

## Key Performance Indicators

-  **Batting Measures:** Runs, sixes, fours, and strike rate
- **Bowling Measures:** Economy rate, strike rate, wickets taken
- **Team Performance Measures:** Win-loss record, net run rate

## Insights and Recommendations

The IPL Live Score Dashboard provides invaluable insights for creating live scorecards and making fantasy cricket teams. These insights enable users to track player performances and make informed decisions when building their fantasy squads.

### Detailed Insights

- **Live Batting Analysis:**
  - Real-time analysis of batting performances, tracking runs scored, strike rates, and boundary counts to identify key contributors during live matches.

- **Team Overall Performance:**
  - Evaluate team performance across various metrics such as total runs, wickets taken, and overall efficiency to understand team strengths and weaknesses.

- **Qualified Teams:**
  - Analyze the performance metrics and standings of teams that have qualified for the playoffs, providing insights into their journey and key factors behind their success.

## Usage

- Open the Power BI file.
- Ensure you are connected to the internet to fetch real-time data.
- Interact with the dashboard using slicers, filters, and navigation buttons.

## Dashboard Components

- **Live Score Display:** Real-time match updates and highlights
- **Live Player Performance:** Detailed analysis of live player performance metrics
- **Team Analysis:** Comparative performance metrics and rankings
- **Match Insights:** Detailed match analysis and scorecard

## Video Demo

Check out a quick demo of the IPL Live Score Dashboard:

[![IPL Live Score Dashboard Demo](https://img.youtube.com/vi/your-video-id/maxresdefault.jpg)](https://www.youtube.com/watch?v=your-video-id)

Watch the demo to see how to navigate the dashboard, interact with different visualizations, and utilize its real-time features. Whether you're a cricket enthusiast or a data analyst, this video provides a brief yet comprehensive overview of the dashboard's capabilities.

Feel free to watch and explore the dashboard further! 


## Conclusion
The IPL Live Score Dashboard project showcases the power of data analytics and visualization in enhancing the viewing experience of cricket enthusiasts. By providing real-time updates and in-depth analysis, the dashboard serves as a valuable tool for fans, analysts, and team management. Explore the dynamic world of IPL cricket through our engaging and interactive dashboard.

