# NETFLIX-Data-analysis


This project analyzes Netflix's collection of movies and TV shows using SQL to identify key trends. It explores content distribution, leading production countries, popular genres, and yearly release patterns. Findings reveal that the U.S. contributes the most content, drama and comedy are the top genres, and mature-rated content is dominant. By answering business questions like the ratio of movies to TV shows and rating trends, the analysis provides useful insights. Overall, this study helps in understanding Netflix’s content strategy and evolving trends

SCHEMA 

CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
