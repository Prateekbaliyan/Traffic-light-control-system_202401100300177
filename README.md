# Traffic-light-control-system_202401100300177
Understanding website traffic is essential for improving user experience and optimizing online presence. This project visualizes and analyzes trends in page views, unique visitors, and hourly traffic patterns.

Dataset

The dataset contains website traffic logs with the following key columns:

timestamp – The date and time of each recorded visit

Date – The date of the visit

PageViews – The number of pages viewed

UniqueVisitors – The number of distinct users

Other relevant columns


Methodology

1. Data Loading & Exploration

Read the CSV file using Pandas.

Display dataset information, check for missing values, and generate statistical summaries.

2. Data Cleaning & Processing

Convert timestamp and Date columns to datetime format.

Extract hourly traffic patterns by grouping data based on hours.

3. Visualization & Analysis

Hourly Traffic Trends:

Group traffic data by hour and visualize using a line plot.
Daily Traffic Trends:

Plot Page Views and Unique Visitors over time.
