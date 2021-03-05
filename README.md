# Kickstarting with Excel

## Overview of Project

This project provides introduction to the world of excel by discovering trends in the Kickstarter data set more specifically analyzing and finding trends related to theater launch campaigns.

### Purpose

The purpose of this project is to offer Louise insight on how different campaigns fared in relation to their launch date and their funding goals.

## Analysis and Challenges

The main analysis happens in 2 different parts. The first part of the analysis happens at a holistic level showing which time periods have had successful launch outcomes while the second part of the analysis reveals which campaigns have reached, exceeded, or failed their fund-raising goals 

### Analysis of Outcomes Based on Launch Date

A pivot table and line graph were created to compare the total number of outcomes of a theatre production versus the month the theatre production came out. To achieve the resultant graph and pivot table filters was placed in the year and category fields. To the get the years, the YEAR() function was used to extract the year from the "Date Created Conversion" column found in the Kickstarted raw data set. Once the filters were added the outcomes column was added to the columns and values field while the "Date created Conversion" column was filtered to show just the months and than added to the rows field to obtain the pivot table which was than charted to obtain the resultant graph below. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/57723459/110135957-1f18f980-7d9d-11eb-989a-1b536d75f067.png)

### Analysis of Outcomes Based on Goals

The analysis of Outcomes based on goals focused on the subcategory "Plays" and looked at percentage of plays that were deemed successful, fail, or cancelled. To do this the COUNTIFS() function was used to aggregated numbers of plays of a specific outcome based on the expected goal. Once the data was aggregated and tabulated a line graph was created from the table showing the general trend of successful, failed, and cancelled plays. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/57723459/110135978-25a77100-7d9d-11eb-8bee-b6da526cf32c.png)

### Challenges and Difficulties Encountered

The biggest challenge that was encountered was the use of the COUNTIFS() functions due to the unfamiliarity of the functions and trying to understand the logic and syntax of the function. Other than the difficulties using the COUNTIFS() function the analysis was very straightforward and easy to implement

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    The main conclusion that can drawn about the Outcomes based on Launch Date is that the best time to launch a theatre production is during May followed by June as these months had the highest percentage of successful launches while December had the least number of successful launches. Looking at the number of failed launches the months of May, June and October had the highest percentage of failed theatre launches. Considering May and June both had the highest successful and failed launches indicates that there is an all-or-nothing risk for launching theatre productions during that time. The month of December shows there is a 50/50 chance of success and failure as the 2 lines almost intersect at that month. 

- What can you conclude about the Outcomes based on Goals?

    The main conclusion is that campaigns sub $5000 have the highest chance of success (74.5%) while campaigns between $45,000 and $49,999 have no chance of successful. Campaigns between $25,000 and $34,999 are the riskiest as they have the highest percentage of failure (76.5%).

- What are some limitations of this dataset?

    The limitations of the dataset include the time frame of the data. A lot of the data was from the year 2014-2016 which limits the ability to extrapolate the insights to the current year of 2021. I believe by providing the data from 2010 to the current year would provide a better data set by removing biases and would allow use to extrapolate and make future predictions on more robust data set. 

- What are some other possible tables and/or graphs that we could create?

    Some other graphs that can be created with the given data are boxplots which will visual the distribution of the data and help identify outliers.


