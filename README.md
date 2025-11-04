# Netflix-Data-Analysis
# Netflix Content Strategy Analysis

## Project Overview

This project analyzes the Netflix dataset (up to mid-2021) to generate actionable insights. The primary goal is to understand the existing content library and identify trends that can help Netflix make data-driven decisions about:
* What types of content (movies or TV shows) to produce or acquire.
* Which genres are most popular and offer growth opportunities.
* Which countries are key markets for content production and subscriber growth.

## Dataset

* *File:* netflix_titles.csv
* *Description:* This dataset contains a list of all movies and TV shows available on Netflix as of mid-2021.
* *Key Columns:*
    * show_id: Unique ID for the title.
    * type: Identifier (Movie or TV show).
    * title: Title of the movie or TV show.
    * director: Director of the movie.
    * cast: Actors in the movie or show.
    * country: Country where the content was produced.
    * date_added: Date the title was added to Netflix.
    * release_year: The original release year of the content.
    * rating: TV rating (e.g., TV-MA, PG-13).
    * duration: Duration in minutes (for movies) or seasons (for TV shows).
    * listed_in: Genre(s) of the title.
    * description: A brief summary of the title.

## Requirements

This analysis is performed using Python 3 and the following libraries:
* pandas (for data manipulation and analysis)
* matplotlib (for data visualization)
* seaborn (for enhanced data visualization)

You can install these libraries using pip:
```bash
pip install pandas matplotlib seaborn