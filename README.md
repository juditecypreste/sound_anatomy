# Lede Project 1: The sounds of anatomy

This repository include the data and notebooks used for the third project I've worked on as a part of the Lede program for Data Journalism from Columbia Graduate School of Journalism.

# The project
## The sounds of anatomy
Since ancient times, humans have had a curiosity to understand their own bodies. Despite scientific advancements providing more effective methods to satisfy this curiosity, humans continue to revere and seek knowledge about their bodies. 

To contribute to this quest, I sought to comprehend how humans speak about their own bodies in one of the most important and respected sources of insights into humanity today: Spotify songs.

Armpits, knees, and necks: how do the platform's most popular songs sing about our bodies? What do these songs celebrate (or not) about our bodies? What is the human relationship with oneself?

[Read this story.](https://juditecypreste.com/portfolio-lede/project-03/)

# The files:
1. [Body Parts](https://github.com/juditecypreste/sound_anatomy/blob/main/body_parts.csv)

I used songs that had body parts as keywords. For that, I created a dataframe with the body parts I wanted to be searched.

2. [Collecting the songs](https://github.com/juditecypreste/sound_anatomy/blob/main/spotify.ipynb)

To collect the songs, I used the Spotify API and the Spotipy library. Important note: I couldn't find methods that allowed searching only within the song lyrics. As a result, I sometimes got songs that had body parts in their titles. That's why I requested the API to return the 10 most popular songs among the 50 searched (API limit). After that, I conducted a manual and auditory analysis to find the most popular song that actually mentioned the desired body part.

3. [My list of found songs](https://github.com/juditecypreste/sound_anatomy/blob/main/body_tracks.csv)

This is the result of my scrapper.

# New tools and skills

It was my first time using the Spotify API, and I realized how limited and complex it can be. The most significant learning experience came from the visual aspect of the project, using JS in D3 and Scrollama. The complete code can be found [here.](https://github.com/juditecypreste/portfolio-lede/blob/main/project-03/index.html)

# I could not

My experience with the Spotify API left me a bit frustrated. I expected to find more effective search methods and detailed information about the songs. I couldn't collect the number of songs that mentioned body parts, for instance. I believe it would be an interesting analysis to determine if we celebrate certain body parts in music.
