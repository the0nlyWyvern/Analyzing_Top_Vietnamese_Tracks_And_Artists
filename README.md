# Analyzing Top Vietnamese Tracks and Artists <img src="./screenshots/spotify-logo.png" alt="Spotify logo" width="30px">

# Description

Finding insight and making decisions based on the dataset.

# Table of Contents

1. Crawling data using Spotify APIs
2. Cleaning the data
3. Exploring the data
    1. Q1: Which genre has inappropriate lyrics for children?
    2. Q2: Which genre is the most popular one (in terms of quantity and quality)?
    3. Q3: What are the songs that have been released for a long time but are still heard by many people at present?
    4. Q4: For each song length, what is the average popularity score of the songs?

# Data source

| Column                 | Meaning                                           |
| ---------------------- | ------------------------------------------------- |
| **id**                 | ID                                                |
| **name**               | Song name                                         |
| **artist**             | Artist name                                       |
| **artist_followers**   | Number of follwers                                |
| **artist_genres**      | Main genres of artist                             |
| **album**              | The album contains the song                       |
| **release_date**       | Release date                                      |
| **album_total_tracks** | Number of songs of the album                      |
| **duration**           | Duration ( in millisecond)                        |
| **explicit**           | Explicit content (bad languages or mature themes) |
| **popularity**         | Popularity on a scale from 0 to 100               |

# Usage

Download is not needed. Everything has been prepared, go to these Colab files:

-   [Craw data](https://colab.research.google.com/drive/1bOv9_al3FdaYQh4Luteu9x3iWguxkBIz#scrollTo=nYjHO0p6oWfc "colab")
-   [Cleaning the data](https://colab.research.google.com/drive/1SiyWgEwAyTCxldTgkGWT2IMSblJ9am0-#scrollTo=8NpuAc1C_An3)
-   Understand the data:
    -   [Part 1](https://colab.research.google.com/drive/1ogZBqe-MQmneysn6jHlYwjaQe__cg2DF)
    -   [Part 2](https://colab.research.google.com/drive/1PmP-e8xaa2jFRLcCe_oMjub9Mz84tqFc#scrollTo=djCHS-KQheri)

All of the above Colab Files are contained inside this [root folder](https://drive.google.com/drive/folders/18vacvNjWV8bYakc7B6cFGd0yp9iK9fmE?usp=sharing)

# Contributors

-   Kiet Tuan Tran
-   Hung Quoc Pham
