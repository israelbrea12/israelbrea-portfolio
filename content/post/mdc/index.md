---
title: Tweets Analysis and Film Recommendations
description: Academic project | Film recommendation system based on the extraction and analysis of tweets to identify film preferences.
slug: tweet-film
date: 2024-05-25 00:00:00+0000
image: tweet-analysis-film-recommendations.png
categories:
    - Data Analysis
    - Machine Learning
    - Natural Language Processing (NLP)
tags:
    - Octoparse
    - Numpy
    - Pandas
    - Seaborn
    - Matplotlib
    - Plotly
    - Sklearn
weight: 1
---
## Project description:
This project involves the development of a personalised movie recommendation system that uses tweets to identify users' movie preferences. The system is able to analyse the tweets of specific users, understand if the mentioned movie is to their liking and extract relevant information to generate recommendations based on individual tastes.

## What does the movie recommendation system do?
The system collects tweets in Spanish, analyses the sentiment to determine whether or not the user enjoyed the film and uses a machine learning model to identify the films mentioned. Through Natural Language Processing (NLP) algorithms and hashtag analysis, the system classifies the tweets, extracts the films mentioned and adjusts the recommendations according to the genres and preferences detected.

## Why was it created?
The project was born with the purpose of automating the way users receive film recommendations, using real and dynamic opinions extracted from social networks. Instead of relying on conventional reviews, the system uses the information users share in their tweets, providing personalised recommendations based on tastes expressed naturally and spontaneously on the social network.

## System process:
1. **Extraction of Tweets**: Tweets are obtained in which a film is mentioned and it is identified whether the user has liked or disliked it.
2. **Sentiment Analysis**: Tweets are evaluated using PLN techniques to classify opinions as positive or negative.
3. **Film Identification**: Using hashtag analysis and text normalisation, the system identifies the films mentioned in the tweets.
4. **Generation of Recommendations**: Based on a recommendation algorithm, a score is assigned to different films according to the user's preferences, providing a final list of the 20 most suitable films.

## View presentation of the project in pdf
[Tweet analysis and film recommendation project](/presentacion-resultados.pdf)