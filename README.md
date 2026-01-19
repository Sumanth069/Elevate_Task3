# Elevate_Task3

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset. The goal is to understand the structure of the data, analyze content distribution, identify outliers, and extract meaningful insights that can support future machine learning or recommendation system tasks.


# Dataset Information

Dataset Name: Netflix Movies and TV Shows

Source: Kaggle

File Used: netflix_titles.csv

Records: Movies and TV shows available on Netflix

# Tools & Libraries Used

Python

Pandas – Data loading and manipulation

Matplotlib – Basic visualizations

Seaborn – Statistical plots

# Exploratory Data Analysis Steps

1. Data Loading & Overview

Loaded dataset using Pandas

Checked shape, data types, and missing values

Identified numerical and categorical features

2. Numerical Feature Analysis

Histogram of release_year to observe content trends over time

Box plots used to detect outliers in numerical columns

3. Categorical Feature Analysis

Count plots for:

Movies vs TV Shows

Content ratings

Identified dominant categories and class imbalance

4. Duration Analysis

Extracted numerical values from the duration column

Analyzed movie durations (minutes) and TV show seasons separately

Used box plots to identify outliers

5. Correlation Analysis

Generated correlation heatmap for numerical features

Observed weak correlation between duration and release year

# Key Insights

Netflix catalog is dominated by movies compared to TV shows.

Majority of content was released after 2010, showing a focus on recent productions.

Most movies have a duration between 80–120 minutes.

TV shows generally have 1–3 seasons, with few long-running outliers.

Mature ratings like TV-MA and TV-14 are most common.

#  Important Features Identified

type

release_year

rating

duration

listed_in

country

These features are useful for future predictive modeling or recommendation systems.

# Conclusion

This EDA helped in understanding Netflix’s content distribution, detecting outliers, and identifying important features. The insights gained from this analysis can be used for building machine learning models such as content recommendation or classification systems.
