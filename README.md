# Cyclistic Bike-Share Analysis

## Google Data Analytics Capstone Project

This case study analyzes 12 months of Cyclistic bike-share trip data (April 2020–March 2021) to understand how casual riders and annual members use the service differently. The goal is to identify data-driven insights that can support strategies for converting casual riders into annual members.

### Tools Used
- Microsoft Excel
- Power Query
- PivotTables
- Tableau

## Business Task

Analyze how casual riders and annual members use Cyclistic bikes differently and identify insights that can help support strategies to convert casual riders into annual members.

## Data Source

The analysis uses 12 months of historical Divvy bike-share trip data from April 2020 through March 2021. The dataset contains individual ride records including ride ID, bike type, start and end times, station information, and rider type (casual or member).

The 12 monthly CSV files were combined into a single dataset for cleaning and analysis.

## Data Preparation and Cleaning

The 12 monthly CSV files were imported and combined using Excel Power Query. The data was then prepared for analysis by:

- Checking column data types and consistency across the monthly files.
- Creating ride-length and date/time fields for analysis.
- Identifying and removing rides with invalid ride durations (ride length ≤ 0).
- Retaining valid ride records for analysis.
- Producing a cleaned dataset containing 3,478,810 rides.

## Analysis

The cleaned dataset was analyzed using Excel PivotTables and Tableau to compare casual riders and annual members across several dimensions:

- Total number of rides by rider type.
- Average ride length by rider type.
- Riding patterns by day of the week.
- Monthly ridership trends.
- Riding patterns by hour of the day.
- Bike type preferences.

Tableau was used to visualize these patterns and build an interactive dashboard comparing casual riders with annual members.

## Key Findings

- **Members ride more frequently overall:** Annual members completed 2,051,851 rides compared with 1,426,959 casual rides — approximately 44% more rides.
- **Casual riders take much longer trips:** Casual riders averaged 45.0 minutes per ride compared with 16.1 minutes for members, nearly three times longer.
- **Riding patterns differ by day of the week:** Member ridership is substantially higher Monday through Friday, while Saturday is the only day casual riders recorded more rides than members.
- **Casual riding is strongly weekend-oriented:** Casual ridership rises sharply on weekends, with Saturday recording the highest casual ridership at 335,034 rides.
- **Both groups show strong seasonality:** Ridership increased through spring and summer, peaked in August 2020, and declined substantially during the winter months.
- **Members show stronger commuting-hour patterns:** Member ridership shows a noticeable morning peak around 7–8 AM and a pronounced late-afternoon peak around 5 PM.

## Recommendations

Based on the analysis, Cyclistic could consider the following strategies:

- **Target casual riders during weekends and warmer months.** Run membership campaigns when casual ridership is highest, particularly on Saturdays and during spring and summer.
- **Promote membership around the value of frequent riding.** Use targeted offers to show casual riders how an annual membership could benefit them if they begin using Cyclistic more regularly.
- **Encourage casual riders to use Cyclistic beyond recreation.** Promote membership for weekday and commuting use, positioning Cyclistic as an option for routine transportation rather than only leisure trips.

## Project Files

This repository includes the main materials used to complete the analysis:

- **Excel Analysis:** Cleaned data preparation, Power Query workflow, PivotTables, and analytical summaries.
- **Tableau Workbook:** Visualizations and dashboard used to explore rider behavior.
- **Presentation:** Final PowerPoint and PDF presentation summarizing the analysis, key findings, and recommendations.
