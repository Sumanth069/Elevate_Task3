**Netflix Movies and TV Shows Dataset**





**1. Introduction**



Exploratory Data Analysis (EDA) is a crucial step in understanding the structure, patterns, and characteristics of a dataset before applying machine learning models.

This report presents an EDA performed on the Netflix Movies and TV Shows dataset, with the objective of analyzing content distribution, identifying outliers, and extracting insights useful for prediction and recommendation systems.



**2. Dataset Description**



Dataset Name: Netflix Movies and TV Shows



Source: Kaggle



File Used: netflix\_titles.csv



Data Type: Structured, mixed (categorical + numerical)



Key Columns



type – Movie or TV Show



release\_year – Year of release



rating – Age rating



duration – Duration in minutes or number of seasons



listed\_in – Genre



country – Country of production



The dataset contains information about content available on Netflix, including both movies and TV shows.



**3. Tools \& Technologies Used**



Python



Pandas for data manipulation



Matplotlib for basic visualizations



Seaborn for statistical plots



**4. Data Overview**



Initial inspection of the dataset revealed:



Presence of both numerical and categorical features



Missing values in columns such as director, cast, and country



Clean and well-structured data suitable for exploratory analysis



Descriptive statistics were used to understand data ranges, central tendencies, and distributions.



**5. Exploratory Data Analysis**



**5.1** Distribution of Numerical Features



A histogram of the release\_year column showed that:



Most Netflix content was released after 2010



There is a sharp increase in content production in recent years



Insight:

Netflix focuses heavily on modern and recent productions.



**5.2** Categorical Feature Analysis

Movies vs TV Shows



A count plot comparing content types revealed:



Movies significantly outnumber TV shows on Netflix



Insight:

The platform’s catalog is movie-dominated.



Content Rating Distribution



Ratings such as TV-MA and TV-14 are most frequent



Insight:

Netflix targets mature and teenage audiences more than children.



**5.3** Outlier Detection

Release Year



Box plot analysis showed:



Most content lies between 2010–2021



Older titles (before 1990) appear as outliers



Insight:

Older movies are rare and treated as exceptions.



**5.4** Duration Analysis



The duration column was processed by extracting numerical values:



Movies → duration in minutes



TV Shows → number of seasons



When analyzed together, the box plot showed wide variation due to mixed units.



After separating content types:



Movies: Mostly between 80–120 minutes



TV Shows: Mostly 1–3 seasons



Insight:

Movie duration is fairly consistent, while TV shows vary by season count.



**5.5** Correlation Analysis



A correlation heatmap of numerical features showed:



Weak correlation between release\_year and duration



Features are largely independent



Insight:

Most features contribute unique information and are suitable for modeling.



**6. Important Features Identified**



Based on EDA, the following features are important for prediction or recommendation tasks:



type



release\_year



rating



duration



listed\_in



country



**7. Summary of Findings**



Netflix content is dominated by movies.



Majority of titles were released after 2010.



TV-MA and TV-14 are the most common ratings.



Movie durations typically range between 80–120 minutes.



TV shows usually have 1–3 seasons.



Older content appears as outliers in release year analysis.



**8. Conclusion**



This exploratory data analysis provided valuable insights into Netflix’s content library. The dataset shows strong trends toward modern, mature-rated content with consistent movie durations. The identified features and patterns can be effectively used in future machine learning applications such as content recommendation systems, classification models, or trend analysis.

