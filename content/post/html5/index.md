---
title: LikeMovies
description: Academic project | Hybrid web application with Angular and Ionic for movie management
slug: likemovies
date: 2025-02-01 00:00:00+0000
image: likemovies.png
categories:
- Web Development
tags:
- Angular
- Ionic
- TypeScript
- Html, Css, Js
- Git, Github
- Firebase
- Ionic Storage
weight: 1 # You can add weight to some posts to override the default sorting (date descending)
---

This project was developed for the subject of Client-Side Technologies: HTML5 as part of the official university master's degree in Mobile Computing (MIMO).

The main goal of the project was to **create a hybrid web application for movie management and browsing**, leveraging modern technologies such as **Angular**, **Ionic**, and services such as **Firebase** for authentication and local storage with Ionic Storage.

## Key Features
The **LikeMovies** app allows users to:

1. **Browse Movies**: Consume the TMDB API to list popular movies, by genre, or upcoming movies in Spain.
2. **Custom Management**:
    - Add movies to lists such as "Favorites" or "My List".
    - Set reminders for upcoming releases.
3. **Secure Authentication**: Sign up and log in using Firebase Authentication.
4. **Responsive Interface**: Adapted for multiple devices, ensuring a smooth experience.

## Application structure
The application is organized into several sections accessible through a tabbed navigation system:

- **For you**: Main screen where the user can search for movies, filter them by genre and view them in an interactive grid.
- **New releases**: List of movies about to be released, with the option to add reminders. Includes an **infinite scroll** to dynamically load more results when scrolling.
- **My profile**: Allows the user to manage their personal data and view their personalized lists of favorites and reminders.
- **Movie details**: Displays complete information about a movie, including description, genres and rating, with options to manage favorites and lists.

## Technical highlights
1. **API consumption**: Use of the TMDB API to obtain movie data, managed through an Angular service that interacts with REST endpoints.
2. **Data Persistence**:
    - **Firebase Authentication**: User management and secure authentication.
    - **Ionic Storage**: Local storage for lists and reminders.
3. **Authentication Guards**: Implementation of a Guard to ensure that only authenticated users can access the application's functionalities. Automatically redirects to the login page if not logged in.
4. **Infinite Scroll**: Integrated into the "New Releases" section, it allows for an improved user experience by dynamically loading more data as the user scrolls down.
5. **Swiper.js**: Use of the Swiper.js library to create interactive and responsive carousels, used in sections such as "Favorites" and "Reminders" to highlight movies in an attractive way.
6. **Responsive Design**: Use of media queries, flexbox and grid to ensure adaptability on different devices.

## Conclusion
LikeMovies is a practical example of how to combine modern technologies like **Angular** and **Ionic** with external services like **TMDB** and **Firebase**, offering a complete and professional solution for movie management. The project stands out for its modular architecture, its focus on responsiveness and its fluid integration with APIs and storage.

[View pdf documentation](/documentacion_html5.pdf)

## LikeMovies Functionality Video
{{< youtube "GveLpWewbkg" >}}