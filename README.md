# [Cyclistic Bike Share Data Analysis](https://github.com/Dhanushwr/Cyclistic-Bike-Share-data-analysis/blob/main/Cyclistic%20analysis%20report.pdf)

---

## **_Table of contents_**

1. [Overview](#Overviw)
2. [Project Details](#ProjecT-Details)
3. [Conclusion](#Conclusion)
4. [License](#License)

---

## _**Overview**_

This repository contains the analysis of Cyclistic's historical bike trip data. The objective is to identify key differences between casual riders and annual members, with the ultimate goal of informing a marketing strategy aimed at converting casual riders into annual members.

## _**Project Details**_ 
(A part of Google data analysis certificate)

### Background of the Company:-

Cyclistic is a bike-sharing service operating in Chicago with over 5,800 bicycles and 600 docking stations. Launched in 2016, Cyclistic offers various bike types, including traditional bicycles, reclining bikes, hand tricycles, and cargo bikes. The service accommodates different usage patterns with flexible pricing options, including single-ride passes, full-day passes, and annual memberships. Annual members contribute significantly more to the company's revenue than casual riders.

### Project Overview:-

Cyclistic aims to increase the number of annual members by understanding how casual riders and annual members use the service differently. The insights from this analysis will help develop effective marketing campaigns to convert casual riders into loyal subscribers.

### Key Questions:-

- How do annual members and casual riders use Cyclistic bikes differently?

- Why would casual riders buy Cyclistic annual memberships?

- How can Cyclistic use digital media to influence casual riders to become members?

### Data Preparation:-

The analysis utilizes Cyclistic’s historical bike trip data from June 2023 to June 2024 [(Data link)](https://divvy-tripdata.s3.amazonaws.com/index.html), available publicly from Motivate International Inc. The dataset includes ride identifiers, bike type, start and end times, station details, geographic coordinates, and customer type (member or casual rider).

### Data Processing:-

Data Quality Issues: Missing values for station identifiers, names, and geographic coordinates; inconsistencies in ride start and end times.

Data Transformation: Creation of new columns for ride duration, start and end hours, and day of the week. Handling of missing values and consolidation of data into a unified dataset using Google BigQuery.

### Analysis:-

- Membership Analysis: Count of casual and annual members.

- Ride Length Analysis: Total ride duration by minutes for both membership types.

- Bike Utilization: Number of times different bike types were used, categorized by membership type.

- Annual Bike Ridership: Analysis of monthly ridership patterns.

- Weekly Bike Ridership: Analysis of weekly ridership patterns.

- Hourly Bike Ridership: Analysis of hourly ridership patterns.

- Roundtrip analysis: Count of casual and annual members taking round trips throughout the period.

- Departure hotspots: Identifying points with more than 5000 casual riders who start their trips.

### Tools Used:-

- Data Manipulation: Excel, SQL, Google BigQuery

- Data Visualization: [Tableau](https://public.tableau.com/views/CyclisticBikeshareanalysisJune2023toJune2024/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

- Data communication: [Powerpoint](https://github.com/Dhanushwr/Cyclistic-Bike-Share-data-analysis/blob/main/Cyclistic%20data%20report%20presentation.pptx)

### Findings:-

1. Customer Segmentation: The customer base is distinctly divided into casual riders and members with differing ride behaviors and preferences.

2. Ride Behavior: Casual riders exhibit higher ride frequency and a preference for round trips, while members demonstrate longer ride durations and weekday usage.

3. Bike Preference: Both segments favour electric and classic bikes, but casual riders lean towards docked bikes.

4. Market Opportunity: High-departure locations offer significant potential for targeted marketing campaigns, especially for casual riders.

## _**Conclusion**_

The analysis aims to provide data-driven recommendations to Cyclistic's executive team to secure approval for proposed marketing initiatives. By understanding the differences in usage patterns between casual riders and annual members, Cyclistic can develop targeted marketing strategies to increase annual memberships.

---

## _**License**_

The dataset is publicly available under the license provided by Motivate International Inc. [Cyclistic Data License Agreement.](https://divvybikes.com/data-license-agreement)
