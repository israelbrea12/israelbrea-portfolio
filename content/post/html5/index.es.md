---
title: LikeMovies
description: Proyecto académico | Aplicación web híbrida con Angular e Ionic para la gestión de películas
slug: likemovies
date: 2025-02-01 00:00:00+0000
image: likemovies.png
categories:
    - Desarrollo Web
tags:
    - Angular
    - Ionic
    - TypeScript
    - Html, Css, Js
    - Git, Github
    - Firebase
    - Ionic Storage
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

Este proyecto fue desarrollado para la asignatura de Tecnologías del lado del cliente: HTML5 como parte del máster universitario oficial en Informática Móvil (MIMO).

El objetivo principal del proyecto fue **crear una aplicación web híbrida para la gestión y exploración de películas**, aprovechando tecnologías modernas como **Angular**, **Ionic** y servicios como **Firebase** para autenticación y almacenamiento local con Ionic Storage.

## Funcionalidades principales
La aplicación **LikeMovies** permite a los usuarios:

1. **Explorar películas**: Consumir la API de TMDB para listar películas populares, por género o próximas a estrenarse en España.
2. **Gestión personalizada**:
   - Añadir películas a listas como "Favoritos" o "Mi Lista".
   - Configurar recordatorios para estrenos próximos.
3. **Autenticación segura**: Registro e inicio de sesión mediante Firebase Authentication.
4. **Interfaz responsiva**: Adaptada para múltiples dispositivos, garantizando una experiencia fluida.

## Estructura de la aplicación
La aplicación está organizada en varias secciones accesibles mediante un sistema de navegación con tabs:

- **Para ti**: Pantalla principal donde el usuario puede buscar películas, filtrarlas por género y visualizarlas en una cuadrícula interactiva.
- **Estrenos**: Listado de películas próximas a estrenarse, con opción para añadir recordatorios. Incluye un **scroll infinito** para cargar más resultados dinámicamente al desplazarse.
- **Mi perfil**: Permite al usuario gestionar sus datos personales y visualizar sus listas personalizadas de favoritos y recordatorios.
- **Detalle de película**: Muestra información completa de una película, incluyendo descripción, géneros y puntuación, con opciones para gestionar favoritos y listas.

## Características técnicas destacadas
1. **Consumo de API**: Uso de la API de TMDB para obtener datos de películas, gestionado mediante un servicio Angular que interactúa con los endpoints REST.
2. **Persistencia de datos**:
   - **Firebase Authentication**: Manejo de usuarios y autenticación segura.
   - **Ionic Storage**: Almacenamiento local para listas y recordatorios.
3. **Guards de autenticación**: Implementación de un Guard para garantizar que solo los usuarios autenticados puedan acceder a las funcionalidades de la aplicación. Redirige automáticamente a la página de inicio de sesión si no se ha iniciado sesión.
4. **Scroll infinito**: Integrado en la sección de "Estrenos", permite una experiencia de usuario mejorada al cargar dinámicamente más datos conforme el usuario se desplaza hacia abajo.
5. **Swiper.js**: Uso de la librería Swiper.js para crear carruseles interactivos y responsivos, utilizados en secciones como "Favoritos" y "Recordatorios" para destacar películas de forma atractiva.
6. **Diseño responsivo**: Uso de media queries, flexbox y grid para garantizar adaptabilidad en distintos dispositivos.


## Conclusión
LikeMovies es un ejemplo práctico de cómo combinar tecnologías modernas como **Angular** e **Ionic** con servicios externos como **TMDB** y **Firebase**, ofreciendo una solución completa y profesional para la gestión de películas. El proyecto destaca por su arquitectura modular, su enfoque en la responsividad y su integración fluida con APIs y almacenamiento.

[Ver documentación en pdf](/documentacion_html5.pdf)

## Video Funcionalidad LikeMovies
{{< youtube "GveLpWewbkg" >}}