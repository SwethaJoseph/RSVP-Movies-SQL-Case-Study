# RSVP-Movies-SQL-Case-Study
## Overview
This project is an SQL-driven analysis aimed at supporting RSVP Movies, an Indian film production company, as it prepares for a global movie release in 2024. By examining trends in movie genres, release timing, ratings, and industry success factors, the analysis provides data-backed insights that inform strategies for a successful international launch.

## Dataset Description
The project uses data from the IMDb database covering movie releases between 2017 and 2019. The dataset includes information on:

* Movie: Movie details such as title, release year, country, duration, and worldwide gross income.
* Genre: Genre classification for each movie.
* Ratings: Average rating, median rating, total votes, and other rating metrics.
* Names: Data on actors, directors, and other key personnel involved in each movie.
* Director & Role Mapping: Mapping tables to connect movies with their respective directors and actors.
  
The dataset has been processed using SQL to answer strategic questions regarding genre performance, ratings, and global audience preferences.

## ENTITY- RELATIONSHIP DIAGRAM (ERD)
The ERD below illustrates the relationships between the key tables used in this project:

![Entity-Relationship Diagram](ERD.png)

* Download the IMDB Dataset: Ensure all necessary tables (movies, genres, ratings, contributors) are accessible.
* Review Data Structure: Study the relationships and schema in the ERD to understand the data connections.
* Set Up the Database: Use your preferred SQL environment (e.g., MySQL Workbench) to create and populate the database using the provided SQL scripts or custom commands.

_Note: If you’d like to skip the manual setup, a SQL script is available that automates database creation and data loading._

## Objectives
* Identify Popular Genres: Determine the best-performing genres for RSVP’s new release.
* Timing Insights: Find optimal release months based on historical trends.
* Ratings & Performance: Assess ratings distribution and identify top-rated movies, actors, and directors.
* Global Trends: Compare performance metrics in major markets like the USA and India.
* Production Recommendations: Offer strategic guidance on selecting top production houses, actors, and directors for international appeal.

## Analysis Segments

1. **Movie Release Trends**
* Annual and Monthly Release Patterns: Analyzed the trend of movie releases by year and month, with March showing the highest release frequency.
* Country-Specific Insights: Identified that the USA and India are the top producers, collectively releasing 1,059 movies in 2019 alone.

2. **Genre Insights**
* Top Genres: Drama emerged as the most produced genre, followed by Thriller and Action.
* Genre Duration: Action movies have the longest average duration, while Horror is the shortest, with most genres averaging between 100-110 minutes.

3. **Rating Analysis**
* Rating Range: Most movies receive ratings from 1 to 10, with no significant outliers, suggesting a balanced rating distribution.
* Top-Rated Movies: The highest-rated movies, including "Kirket" and "Love in Kilnerry," achieved an average rating of 9.5.
* Production House Performance: Dream Warrior Pictures and National Theatre Live rank as top production houses, each producing three highly-rated movies.

4. **Performance by Contributors**
* Top Directors: Identified top directors like James Mangold, Joe Russo, and Anthony Russo, whose movies have an average rating above 8.
* Top Actors and Actresses: Mammootty and Mohanlal emerged as leading actors with high median-rated movies, while Taapsee Pannu was the top actress in Hindi films.

5. **Box Office Success**
* Top-Grossing Movies: Movies like "Avengers: Endgame" and "The Lion King" dominated the box office, especially in the Action and Adventure genres.
* Production House Influence: Marvel Studios and Warner Bros. are top producers, excelling in box office revenue and audience appeal.

## Findings & Recommendations
* Focus on High-Performing Genres: Drama, Action, and Thriller genres show high engagement and should be prioritized for international release.
* Optimal Release Timing: Aim for a March release, which historically has the highest number of movie releases.
* Top Talent Collaboration: Collaborate with top-rated directors and actors, such as Vijay Sethupathi and directors like James Mangold, to maximize global appeal.
* Box Office Insights: Leverage popular production houses like Marvel Studios for their market influence and experience with high-grossing movies.

## Tools & Technologies
* MySQL Workbench or any SQL Editor: For querying and analyzing the IMDb dataset.
* Microsoft Excel: For initial data processing and visualization.
* PowerPoint: To present findings and strategic insights.

## Contact
For further questions or suggestions, feel free to reach out to [LinkedIn | Swetha Kizhavana Joseph](https://www.linkedin.com/in/swetha-kizhavana-joseph-04b68721b/) or [email](swethakjoseph16@gmail.com) 
### If you found this project helpful or interesting, please give it a ⭐ to show your support!
