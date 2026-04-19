# IMBD_Top_1000_Movies-EDA-Project-
# Exploratory Data Analysis (EDA) and Deep Dive Analysis Top 1000 IMDb Movies

![IMDB TOP 1000](https://github.com/Rizal-A/EDA-Top-1000-IMDb-Movies/assets/117552819/47f3af59-3ed6-4c47-a4f1-f02f25086be8)

**This Repository is about Exploratory Data Analysis on Kaggle's Top 1000 IMDb Movies dataset**.


This dataset contains information about top 1000 IMDB movies, including their titles, certificates, durations, genres, IMDb ratings, Metascores, directors, cast members, the number of votes they received, grossed earnings, and plot summaries. The data is a curated list of highly acclaimed and popular movies.

**The dataset consists of several features, such as:**

- Movie Name: The title of the movie.
- Certificate: The certificate or rating assigned to the movie.
- Duration: The duration of the movie in minutes.
- Genre: The genre(s) to which the movie belongs.
- IMDb Rating: The IMDb rating of the movie.
- Metascore: The Metascore rating of the movie.
- Director: The director of the movie.
- Stars: The main cast members of the movie.
- Votes: The number of user votes/ratings the movie has received.
- Grossed in $: The gross earnings in dollars (if available).
- Plot: A brief summary or plot description of the movie.

# The things done on this dataset are
- Preparation Data
- Data Cleaning (Missing Values, Duplicated Check)
- Data Understanding
- Exploratory Data Analysis
  - Univariate Analysis
  - Bivariate Analysis
  - Multivariate Analysis
- EDA Conclusion

# Here the results: 
1. There are missing values in the dataset, in the columns Metascore and Certificate by a total of 158 or 15.8% and no Duplicate Data
2. In the Genre column there are several values and in 1 movie there are multiple genres
3. There are special character strings and multiple value in Stars column, so here we separate them into a list so that we can see in which Stars the movie appears the most
4. It can be seen that there are most movies with the genre of **Drama** and **'R' (Rated)** certificate also majority of movies that have a mixture of various genres in the movie.
5. Duration, IMDb Rating, Metascore have a normal distribution while Votes, and Grossed have a distribution skewed to the right (Mean > median)
6. There are outliers in the numerical data, which is in the Duration column where there is a movie that is more than 300 minutes in duration but after observing these data is normal.
7. There is a strong correlation between IMDB Rating with Votes and Grossed in dollars, it can be concluded that the higher the rating, the more votes are given and the higher the grossed revenue obtained. A strong correlation is also found in Votes and Grossed in dollars, it could be that the information contained is redundant information.
8. After analysis the highest Metascore does not affect the high Grossed Revenue and it can be seen that even the most maximal Metascore still gets a small Grossed Revenue. It can be concluded that Grossed Revenue is not affected by Metascore
9. Majority of movie durations are between 100 - 140 minutes.
10. The movie is dominated by multiple genres, which means that in 1 movie there are 3 types of genres 
11. The movie have longest duration is **Gangs of Wasseypur** then **Hamlet, Zack Snyder's Justice League, Gone With The Wind, Once Upon a Time in America**
12. The Top Movie by IMDb Rating in IMBD's 1000 Movies is **The Shawshank Redemption** then **The Godfather, The Dark Knight, Schindler List** and **The Lord of the Rings: The Return of the King** but it turns out that even the best rating does not always result in high Grossed Revenue because it can be seen that the second highest rated **The Godfather** has a Grossed Revenue that is not higher than **The Matrix, Interstellar** and **Inception** which were previously not included in the Top 10 highest rated movies. It can also be seen that **Schindler's List** and **12 Angry Men** are not included at all in the Top 10 Movies with the highest Grossed Revenue.
13. Top Movies according to Metascore are equally strong with a rating of 100 including the movie **Three Colors: Red to The Leopard**
14. The Top Stars in IMBD's 1000 Movies is **Robert De Niro** then **Tom Hanks, Al Pacino, Matt Damon, Brad Pitt**
15. The Top Directors in IMBD's 1000 Movies are **Alfred Hitchcock and Akira Kurowasa** but the director who earned Highest Grossed Revenue from their movie is **Christopher Nolan**
16. After analyzing the movies that contributed the most to Director Christopher Nolan's Grossed Revenue, it turns out the movies that have the highest Grossed Revenue are **The Dark Knight** then **Inception, Interstellar, The Dark Knight Rises** and **Batman Begins**. It can also be seen that the **Batman sequel or The Dark Knight** is the highest or main contribution to Christopher Nolan's Grossed Revenue.
17. Every movie mostly contains the words **"Life, Find, Man, Two, Family and Young"**. Maybe these words are found in the Drama genre, therefore it must be further analyzed the words on the plot in the drama genre where the Drama Genre is the most popular movie in the Top 1000 IMDb Rating.
