# IMDb Top 1000 Movies Analysis

## Overview

This project focuses on analyzing IMDb’s Top 1000 Movies dataset to uncover trends in movie genres, ratings, directors, and more. The analysis is conducted using Python for data processing and Power BI for data visualization, with the aim of providing insights into the characteristics of top-rated movies.

## Project Objectives

- Analyze the characteristics of IMDb’s top 1000 movies.
- Identify trends in genres, ratings, directors, and release years.
- Provide actionable insights for movie enthusiasts and stakeholders in the film industry.

## Data Collection

The primary data source for this project is the [IMDb Top 1000 Movies Dataset](https://www.kaggle.com/datasets), which contains data such as:

- **Movie Title**: The title of the movie.
- **Year**: The release year of the movie.
- **IMDb Rating**: The average IMDb rating for the movie.
- **Director**: The director(s) of the movie.
- **Genre**: The genre(s) the movie belongs to.
- **Duration**: The length of the movie in minutes.
- **Votes**: The number of user votes for the movie.
- **Gross**: The box office revenue (if available).

## Data Operations

I performed **6 key data operations** during this analysis:

1. **Defining Objectives**:
   - Established the goal to understand what makes a movie rank in the top 1000 on IMDb and how certain factors (like genres or directors) influence ratings.

2. **Data Cleaning**:
   - Removed incomplete entries, handled missing values, and standardized formats for dates, genres, and numeric fields.

3. **Data Integration**:
   - Merged additional datasets to add contextual information such as country of production and awards won.

4. **Data Transformation**:
   - Converted categorical variables (e.g., genres, directors) into numerical formats for better analysis and created derived metrics like rating-to-votes ratios.

5. **Exploratory Data Analysis (EDA)**:
   - Conducted preliminary analysis using Python (pandas, matplotlib) to visualize relationships between different variables like ratings vs. years or gross earnings.

6. **Feature Engineering**:
   - Created new features such as average genre ratings and director success rates.

## Dashboard Showcase

The final dashboard, created using Power BI, features the following:

- **Key Metrics**: Total movies, average IMDb rating, and average gross revenue.
- **Genre Breakdown**: Pie charts and bar charts displaying the distribution of genres and average ratings by genre.
- **Director Insights**: Visualizations highlighting top directors and their average movie ratings.
- **Time Series Analysis**: Graphs showing how movie ratings and votes have trended over different decades.
- **Duration vs. Rating**: Scatterplots examining the relationship between movie runtime and ratings.

![Dashboard Screenshot](link-to-your-screenshot) *(Insert a screenshot of your Power BI dashboard here)*

## Technologies Used

- **Data Tools**: Python (pandas, matplotlib, seaborn), Power BI
- **Programming Languages**: Python (for data processing and EDA)
- **Data Source**: [IMDb Top 1000 Movies Dataset](https://www.kaggle.com/datasets)

##Thank You##
