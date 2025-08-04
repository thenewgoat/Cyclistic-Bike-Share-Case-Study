# Cyclistic Bike-Share Case Study

## Overview
This notebook is my capstone project for the Google Data Analytics Professional Certificate.  
It focuses on understanding how casual riders and annual members use Cyclistic bikes differently,  
and how those insights can be used to increase annual memberships.

## What this notebook covers
1. **Introduction and business context**  
   Overview of Cyclistic’s bike-share program and the reason for focusing on converting casual riders to annual members.

2. **Data preparation**  
   - Combined multiple monthly trip files into one dataset.  
   - Removed records with missing or invalid information (e.g., missing station data, ride times less than a minute or more than a day).  
   - Added new columns to help with analysis, such as ride duration, day of week, and month.

3. **Exploration and cleaning**  
   - Looked for missing values, duplicates, and inconsistent entries.  
   - Checked data types and fixed issues.  
   - Verified that all ride times and coordinates made sense.

4. **Analysis**  
   - Compared members vs. casual riders by ride count, ride length, and when they ride (hour, day, and month).  
   - Explored bike type preferences (classic vs. electric).  
   - Mapped the most popular routes using latitude and longitude.  
   - Reviewed patterns by season and location.

5. **Visualizations**  
   - Used charts to show ridership trends by day, hour, and month.  
   - Created bar and line plots for ride counts and ride durations.  
   - Built route maps showing top start and end station connections. To view them, download the html files attached in this repository.

6. **Findings and insights**  
   - Casual riders ride longer but mostly on weekends and leisure areas.  
   - Members ride more often, mainly during weekdays for commuting.  
   - Electric bikes are popular around universities, while casual riders often focus on scenic lakefront routes.

7. **Recommendations**  
   - Target casual riders with flexible membership plans.  
   - Promote memberships near tourist and leisure zones.  
   - Engage universities with student and staff membership discounts.  
   - Use digital media to share success stories and highlight benefits.

## Tools Used
- Python with Pandas for data processing and cleaning  
- Folium for route mapping  
- Matplotlib for charts and trend analysis

## Purpose
This notebook demonstrates how data cleaning, exploration, and visualization can generate actionable business recommendations.  
It showcases the full data analysis process, from raw data to insights and strategies.
