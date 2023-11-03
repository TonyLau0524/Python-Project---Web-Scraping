# Web Scraping of Top 1000 movies on IMDb

This simple Jupyter Notebook project analyzes historical yearly weather averages for Toronto, Ontario, Canada. The data represents the average maximum and minimum temperatures as well as the annual average rainfall, taken from over 12 years of historical data. The data is obtained from the World Weather Online website.

## Data Source

The data used in this analysis is derived from the following URL:
- [IMDb "Top 1000" (Sorted by Popularity Ascending)](https://www.imdb.com/search/title/?groups=top_1000)

## Project Overview

The project involves web scraping, data cleaning, analysis, and visualization using Python libraries such as BeautifulSoup, pandas, seaborn, and matplotlib.

## Data Content

This repository contains a dataset with information about movies. The dataset includes the following information:

- **Title**: The title of the movie.
- **Year**: The year the movie was released.
- **Category**: The genre or category of the movie.
- **Time**: The duration or runtime of the movie.
- **Ratings**: The Motion Picture Association (MPA) film ratings assigned to the movie.
- **Director**: The director(s) of the movie.
- **Stars**: The main actors or actresses in the movie.
- **Vote**: The number of votes or ratings the movie has received on IMDb.
- **Gross**: The gross earnings or revenue generated by the movie.


## Analysis Steps

1. **Web Scraping:**
   - Data is scraped from the website using BeautifulSoup.
   - Information is extracted from HTML tables on the web page.

2. **Data Cleaning:**
   - Data is organized into a pandas DataFrame.
   - Column names are cleaned, and data types are converted for analysis.

3. **Data Analysis:**
   - Descriptive statistics and a correlation matrix are calculated.
   - Visualizations are used to provide insights into the data.

4. **Data Visualization:**
   - Bar chart to visualize the top 1000 movies on IMDb distribution by year.
   - Bar chart to visualize the top 10 popular categories.
   - Scatterplot with a correlation line to show correlations between votes and gross earnings for movies.
   - Horizontal Bar chart to show the top 10 most frequent directors/stars.
   - Scatterplot with varying hues to show correlations between votes and gross earnings for movies directed by the top 5 most frequent       directors.


## Conclusion

The data tells us that between 2000 and 2020, there were a lot of highly-rated movies. People really like drama films. A good chunk of movies are for grown-ups (R-rated), and some don't have any ratings. If a movie gets a high rating on IMDb, it often makes a lot of money at the box office. Steven Spielberg is really good at making movies that people love and pay to see. Also, directors like Alfred Hitchcock and Akira Kurosawa have made many great films. And the actor Robert De Niro has been in a lot of really good movies too. All in all, the data shows us what kinds of movies people enjoy and which filmmakers and actors are really successful in the movie business.

## Contributors

- **Hoi Tung Lau**
- Data Analyst | Proficient in SQL, Python, Tableau, MATLAB, Excel(VBA)
