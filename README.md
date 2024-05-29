**Entertainment**

**Objective**

Our main objective is to use Power BI to transform these datasets into a cohesive narrative. This involves meticulous data cleaning, sophisticated data modeling, and adept use of DAX for advanced analytical insights. The culmination of your task is to build an interactive dashboard that vividly presents your findings, offering actionable insights into trends, financial viability, and audience preferences within the movie industry.

***Data Source***

**1. Movie Revenue and Ratings Dataset:**

Key columns in this dataset include:

- Movie ID: A unique identifier for each movie.(Primary Key)
- Title: The name of the movie.
- Worldwide Gross (Millions): Total revenue generated by the movie worldwide, in millions.
- Domestic Gross (Millions): Total revenue generated by the movie within its country of origin, in millions.
- Opening Weekend Gross (Millions): Revenue generated by the movie on its opening weekend, in millions.
- IMDb Rating: The rating of the movie on IMDb.
- Rotten Tomatoes Rating (%): The percentage rating of the movie on Rotten Tomatoes.
- Number of Theaters: The total number of theaters in which the movie was shown.
- MPAA Rating: The Motion Picture Association of America rating for the movie.
- Release Month: The month in which the movie was released.
- Synopsis: A detailed textual description of each movie's plot, setting, and characters. These synopses are varied, covering a range of genres and themes, and provide a comprehensive narrative overview of each film.
  
**2. Movie Production Details Dataset:**

It contains detailed information such as:

- Movie ID: A unique identifier for each movie (Foreign Key).
- Title: The name of the movie (corresponding to the Title in the Movie Revenue and Ratings dataset).
- Production Company: The company responsible for producing the movie.
- Director: The director of the movie.
- Release Year: The year in which the movie was released.
- Budget (Millions): The budget allocated for the movie, in millions.
- Genre: The genre of the movie.
- Filming Location: The geographical location where the movie was filmed.
- Runtime (Minutes): The total runtime of the movie, in minutes.
- Language: The primary language spoken in the movie.

  **Dashboard Outcomes:**
  ![Pb1](https://github.com/Saniyashakur22/PowerBI-Project/assets/112815736/7fdf90fa-d2b3-419a-8ac9-3ca069ca5e8f)
  ![Pb2](https://github.com/Saniyashakur22/PowerBI-Project/assets/112815736/3ec2f482-e675-4568-aea6-eeb90f9b384a)
  ![Pb2](https://github.com/Saniyashakur22/PowerBI-Project/assets/112815736/93ee2180-17cc-42b4-b5c1-58a848b34e6a)
  ![Pb2](https://github.com/Saniyashakur22/PowerBI-Project/assets/112815736/853ebba4-95c6-49ec-96e5-7a9901792afa)

  
**Task Performed**

*1. Genre Popularity Over Time*

 Analyze how the popularity of movie genres has changed over time based on the number of releases.
 
*2. Release Month Impact on Revenue*

Calculate the average worldwide gross revenue by release month. Does the release month impact a movie's financial success?

*3. Production Company Analysis*

Analyze which production companies have the most successful movies in terms of revenue and ratings.

*4. Runtime and Rating Relation*

Investigate if there's a relationship between the runtime of movies and their ratings.

*5. Comparative Analysis of MPAA Ratings*

Compare the box office performance and ratings of movies across different MPAA ratings.

*6. Trends in Movie Releases*

Explore trends in the number of movies released each year. Are there more movies being released now than in the past?


***Key Insights***
- Most no. of movies were released in the year 2013, Sci-fi genre toped it with count of 11 followed by Action Genre.
- From the dataset comedy movies are the highest released movies.
- Shadow of tommorow is the highest budget movie with the budget of $18,482 million and made a world-wide gross revenue of $71,880 millions.
- Taylor Jonson is making the world-wide gross revenue which is around $25k million followed by Jessie Jordan and Riely Brown with a - world-wide gross revenue or $24k millions.
- Highest Profit is made by the Spanish movies of $25.2K millions.
- Over the years thriller movies have highest average IMDB rating of 6.6.
- From the overall dataset we could conclue that the coming trend is of Sci-fi movies as they are making good world-wide gross revenue in less amount of budget and getting good Ratings.



