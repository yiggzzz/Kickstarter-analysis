# Kickstarting with Excel

## Overview of Project

The project analysis was to gain an understanding of how to use excel to view and dissect data that will give you results that are easy to dissect. 

### Purpose

The purpose of this project was to perform an analysis on kickstarter data to uncover trends. The intention is to practice using Pivot Tables and Pivot Charts, use functions to deepen understanding of analysis by applying descriptive statistics, and creating visualizations of the data.

## Analysis and Challenges

The analysis was performed by using Pivot Tables to create Pivot Charts, which could filter the data to give us specific results we were looking for. The functions used were COUNTIFS, SUM, and diving cells by one another to find percentages. The biggest challenge was making sure the syntax of the code was good, so we didn't get any 'Inconsistent Formula' error on a cell while using COUNTIFS.

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/yiggzzz/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
The first deliverable asked us to create a Pivot Table and filter out the parent category to only show theatre outcomes based on launch date. We needed to also filter out the column labels to not include live; therefore, it would only display successful, failed, and cancelled outcomes.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/yiggzzz/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
The second deliverable asked us to find the outcomes based on goals where we used the COUNTIFS function to use data from the Kickstarter sheet to analyze the dollar-amount ranges so projects were grouped based on their goal amount. 

### Challenges and Difficulties Encountered

The biggest challenge I encountered is that I expected my chart to match the second example since the first chart matched exactly. I thought I had wrote my code incorrectly but upon looking back at the lecture, I realized the data is different from the example, since the professor had the same numbers I had on my table. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May was the month with the highest percentage of successful launches whereas December was the month with the lowest percentage of failed launches. The cancelled percentages were around the same amount for every month except October, where there were no cancelled launches. Across all the months, except December, there was a higher percentage of successful launches than failed ones.

- What can you conclude about the Outcomes based on Goals?

The highest percentage of successful launches had "Less than 1000" as a goal, whereas the lowest percentage of successful launches had "50000 to More" for their goal. 

- What are some limitations of this dataset?

The 'Outcomes Based on Goals' dataset does not include the values that were actually pledged vs goals, so we could compare how much of the goal the successful launches completed. The 'Theatre Outcomes Based on Launch Date' dataset does not include percentages, only values, so that could skew the data if there is a very large value, and cause some of the data to become meaningless.

- What are some other possible tables and/or graphs that we could create?

We could create a graph that had the average donation versus the goal amount and filtered out by categories.
