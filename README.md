# Netflix Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a Netflix titles dataset using Python. The goal is to understand the content available on Netflix and identify patterns related to content type, release year, ratings, countries, movie duration, TV show seasons, directors, and cast members.

## Objectives

- Understand the distribution of Movies and TV Shows.
- Analyze Netflix content across different release years.
- Explore ratings and content categories.
- Identify countries contributing the most content.
- Analyze movie durations.
- Analyze the number of seasons in TV Shows.
- Identify frequently appearing directors and cast members.
- Visualize important patterns and trends in the dataset.

## Dataset

The dataset contains information about Netflix titles, including:

- Title
- Category
- Director
- Cast
- Country
- Release Date
- Release Year
- Rating
- Duration

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning

The following data cleaning steps were performed:

- Checked the dataset structure and data types.
- Identified missing values.
- Handled missing values in important columns.
- Converted the Release Date column into a datetime format.
- Extracted the release year from the Release Date.
- Cleaned Country values by splitting multiple countries and using `explode()`.
- Cleaned Cast values by splitting multiple cast members and using `explode()`.
- Extracted movie duration in minutes.
- Extracted the number of seasons for TV Shows.

## Exploratory Data Analysis

The analysis includes:

- Movies vs TV Shows distribution.
- Release year trends.
- Ratings analysis.
- Country-wise content analysis.
- Movies vs TV Shows by country.
- Movie duration analysis.
- TV Show season analysis.
- Top directors by number of titles.
- Top cast members by number of titles.
- Data visualizations using Matplotlib and Seaborn.

## Key Insights

- The dataset contains 5,372 Movies and 2,408 TV Shows.
- The United States has the highest number of titles in the dataset.
- India has significantly more Movies (915) than TV Shows (75).
- Japan has more TV Shows (183) than Movies (103).
- South Korea has more TV Shows (157) than Movies (55).
- The average movie duration is approximately 99.33 minutes.
- The shortest Movie is 3 minutes, while the longest is 312 minutes.
- The maximum number of seasons among TV Shows is 16.

## Conclusion

This exploratory data analysis provides an overview of Netflix's content library and highlights important patterns in content type, release trends, ratings, countries, movie durations, TV show seasons, directors, and cast members.

The project demonstrates practical use of Python, Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, and visualization.
