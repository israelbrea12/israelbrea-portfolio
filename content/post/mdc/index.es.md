---
title: Análisis de Tweets y Recomendación de Películas
description: Proyecto académico | Sistema de recomendación de películas basado en la extracción y análisis de tweets para identificar preferencias cinematográficas.
slug: tweets-peliculas
date: 2024-05-25 00:00:00+0000
image: analisis-tweets-recomendacion-peliculas.png
categories:
    - Análisis De Datos
    - Aprendizaje Automático
    - Procesamiento de Lenguaje Natural (PLN)
tags:
    - Octoparse
    - Numpy
    - Pandas
    - Seaborn
    - Matplotlib
    - Plotly
    - Sklearn
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

## Descripción del proyecto:
Este proyecto consiste en el desarrollo de un sistema de recomendación de películas personalizado que utiliza tweets para identificar las preferencias cinematográficas de los usuarios. El sistema es capaz de analizar los tweets de usuarios específicos, comprender si la película mencionada es de su agrado y extraer información relevante para generar recomendaciones basadas en los gustos individuales.

## ¿Qué hace el sistema de recomendación de películas?
El sistema recoge tweets en español, analiza el sentimiento para determinar si el usuario disfrutó o no de la película y utiliza un modelo de aprendizaje automático para identificar las películas mencionadas. A través de algoritmos de Procesamiento de Lenguaje Natural (PLN) y análisis de hashtags, el sistema clasifica los tweets, extrae las películas mencionadas y ajusta las recomendaciones de acuerdo con los géneros y las preferencias detectadas.

## ¿Por qué se creó?
El proyecto nace con el propósito de automatizar la forma en que los usuarios reciben recomendaciones de películas, utilizando opiniones reales y dinámicas extraídas de las redes sociales. En lugar de basarse en reseñas convencionales, el sistema emplea la información que los usuarios comparten en sus tweets, proporcionando recomendaciones personalizadas basadas en gustos expresados de manera natural y espontánea en la red social.

## Proceso del sistema:
1. **Extracción de Tweets**: Se obtienen tweets en los que se mencione alguna película y se identifique si al usuario le ha gustado o no.
2. **Análisis de Sentimientos**: Se evalúan los tweets mediante técnicas de PLN para clasificar las opiniones como positivas o negativas.
3. **Identificación de Películas**: Mediante el análisis de hashtags y la normalización del texto, el sistema identifica las películas mencionadas en los tweets.
4. **Generación de Recomendaciones**: Basado en un algoritmo de recomendación, se asigna una puntuación a diferentes películas según las preferencias del usuario, proporcionando una lista final de las 20 películas más adecuadas.

## Visualizar presentación del proyecto en pdf
[Proyecto análisis de Tweets y recomendación de películas](/presentacion-resultados.pdf)