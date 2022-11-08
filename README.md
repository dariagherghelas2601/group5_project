# AM10 Data Visualisation and Story Telling - Group 5 Project
## What makes a song a hit?


## What is your topic?
Thousands of new songs are released every year but very few make it to the top records. We decided to embark on a journey to discvoer what are the different characteristics of hit songs to help artists maximize their chances of launching a successful song. 

## What questions are you addressing?
There are many different variables to consider when thinking about music:
- How does the lyrics and topic influence the success of a song?
- What are the characteristcs of artists that made it?
- What genres are most likely to become breakout songs?
- What's the best time to release a new song?

## What data will you be using?

We will start with the complete historical dataset of every Billboard Hot 100 chart since 1958 (https://github.com/HipsterVizNinja/random-data/tree/main/Music/hot-100). This dataset contains detailed information about how a song performed on the charts (how long it has been on the chart, how many times a song returned to the chart, peak and worst position on charts etc.). TO have a comprehensive view over a particular song adn add more context, we will augment this with data from Spotify.

## What statistical methods will you use?
We will be using cluster analysis to group features and identify the correlation between variables such as genre and time on the chart. The  goal is to create a prediction model that is able to identify the likelyhood that a song will become a hit by looking at variables such as artist name, title, genre, length etc.
