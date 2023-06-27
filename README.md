# Netflix-Data-Analysis
## About NETFLIX

Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.
## Business Problem

Analyze the data and generate insights that could help Netflix ijn deciding which type of shows/movies to produce and how they can grow the business in different countries.

Dataset_link (https://github.com/lordchan/Netflix-Data-Analysis/blob/main/Netflix%20-%20Python.csv)

The dataset provided consists of a list of all the TV shows/movies available on Netflix:

Show_id: Unique ID for every Movie / Tv Show

Type: Identifier - A Movie or TV Show

Title: Title of the Movie / Tv Show
Director: Director of the Movie
Cast: Actors involved in the movie/show
Country: Country where the movie/show was produced
Date_added: Date it was added on Netflix
Release_year: Actual Release year of the movie/show
Rating: TV Rating of the movie/show
Duration: Total Duration - in minutes or number of seasons
Listed_in: Genre
Description: The summary description

## Process: 
1. Cleaning the data which includes - filling null values with estimates, dropping bad quality data, Unnesting and stacking multiple comma separated data points.
2. Exploratory Data analysis - Understanding the basic metrics of the data, range of values, key features, segregating numerical and categorical columns.
3. Non-Graphical Analysis: Value counts and unique attributes.
4. Visual Analysis - Univariate, Bivariate after pre-processing of the data
4.1 For continuous variable(s): Distplot, countplot, histogram for univariate analysis
4.2 For categorical variable(s): Boxplot
4.3 For correlation: Heatmaps, Pairplots
5. Missing Value & Outlier check (Treatment optional)
6. Insights based on Non-Graphical and Visual Analysis
 6.1 Comments on the range of Attributes.
 6.2 Comments on the distribution of the variables and the relationship between them
 6.3 Comments for each univariate and bivariate plot
7. Business Insights - Patterns observed in the data along with what you can infer from it.
8. Recommendations - Actionable items for business.
