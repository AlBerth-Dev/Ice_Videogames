# Ice_Videogames

---
The online store "Ice" sells video games all over the world and has compiled data with user and expert reviews, genres, platforms (for example, Xbox or PlayStation) and historical data on game sales over the years. 2016. 
The objective of this project is to identify patterns that determine whether a game is successful or not for sale. This will allow us to detect promising projects and plan advertising campaigns for the following year (2017).

To achieve the objective, the data received will be prepared, then analyzed in order to create a user profile for each of the relevant regions (North America, the European Union and Japan). Additionally, we will seek to answer the following hypotheses:
1. Average user ratings for Xbox One and PC platforms are the same.
2. Average user ratings for Action and Sports genres are different.
___

## General conclusion of the analysis
***The objective of this project was to identify some gaming consumption patterns among users of the "Ice videogames" company from different regions of the world. Below are some of the discovered patterns:***

Analyzing the historical total revenue of the company, it is concluded that the video game market experienced accelerated growth from the year 1995 onwards. Therefore, data from this year onwards were used for analysis, as they provide the most relevant information. Also, with this historical, it was discovered that the most profitable platforms have an almost constant lifecycle of 5 years, except for a few cases like PS3 and X360, where their lifecycle is approximately 10 years.

When comparing the scores given by both users and experts to games on a particular platform (in this case, X360) it was found that the distribution of scores is very similar between users and critics. However, the correlation ***sales-Critic_score*** is slightly more favorable than the correlation ***sales-user_score***. This finding could be relevant to determine the videogames acceptance on the market, based on the critic score.

The distribution of total sales by genre was also analyzed. It was found that the most successful genres, i.e., the best-selling ones, are "Action," "Sports," and "Shooter." However, it was also discovered that there is a strong positive correlation between this distribution and the number of games in the database for each genre. This implies that perhaps the aforementioned genres are seen as "successful" because the store has a greater number of games available in these genres.

Finally, when creating consumption profiles for users from different regions, it is observed that:

- Almost all regions share the same main platforms, including X360, PS2, Wii, and PS3. However, users in JP have a different video game consumption pattern, as most users in this region consume games on the DS platform.
- The most played games in almost all regions are action and sports games, although again, the JP region deviates from the conventional pattern, with the "Role-playing" category being the most popular.
- Regarding these last two categories, "Action" and "Sports," when conducting a hypothesis test on the average rating users give to games in these categories, it was found that these ratings can be considered the same, which means that games from both genres are equally accepted by users.
- Another hypothesis test was conducted to determine whether the average rating users give to XOne and PC games (two of the most recent platforms) is similar or not. As a result of the test, both average ratings are actually different, so we can say with 95% certainty that, in average, the PC platform is better rated by users.
___

## Dataset
The dataset contains a "rating" column that stores the ESRB rating of each game. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.
___
## Data Description
- ***Name***: Name of the game

- ***Platform***: Platform on which the game was launched

- ***Year_of_Release***: Year of release

- ***Genre***: Game genre 

- ***NA_sales***: Sales in North America in millions of U.S. dollars

- ***EU_sales***: Sales in Europe in millions of US dollars

- ***JP_sales***: Sales in Japan in millions of U.S. dollars 

- ***Other_sales***: Sales in other countries in millions of U.S. dollars

- ***Critic_Score***: Critical Score (maximum of 100)

- ***User_Score***: User Score (maximum of 10)

- ***Rating***: ESRB rating

___
### Github Repository:
https://github.com/AlBerth-Dev/Ice_Videogames
