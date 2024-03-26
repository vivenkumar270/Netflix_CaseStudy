# Netflix_CaseStudy
Data:

 This case study analyzes a dataset containing information about movies and shows available on Netflix up to 2021. The data includes columns such as:

    Movie/Show Name: Title of the movie or show.
    Release Date: Date the movie or show was originally released (may be missing for some entries).
    Published Date: Date the movie or show was added to Netflix (may be missing for some entries).
    Rating: User rating associated with the movie or show (may be missing for some entries).
    Director(s): (Exploded) List of directors associated with the movie or show (one director per row).
    Actor(s): (Exploded) List of actors associated with the movie or show (one actor per row).

Exploding Technique: The data utilizes an exploding technique for the Director(s) and Actor(s) columns. This means that if a movie or show has multiple directors or actors, the data will be replicated for each director/actor in separate rows. This allows for a more granular analysis of director and actor involvement.

Focus: This case study primarily focuses on univariate analysis. This means we will be analyzing the distribution of data within each column (e.g., number of movies released per year, distribution of ratings).

Benefits: This case study offers insights into:

    Trends in movie/show releases and additions to Netflix over time (up to 2021).
    Distribution of user ratings.
    Potential relationships between release date, published date, and ratings.
    Exploration of director and actor involvement through counts and breakdowns.

