---
title: Creation and deployment of web portfolio with Hugo.
description: Personal project | Creation and deployment of web portfolio to present and write about the projects done during my academic and professional career.
slug: hugo-web
date: 2024-09-01 00:00:00+0000
image: hugo-portfolio.png
categories:
    - DevOps
    - Web Development
tags:
    - Markdown
    - Bash
    - Hugo
    - Docker
    - Caddy
    - Git, Github
    - Html, Css, Js
    - Vs Code
    - RPI5
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

## Project Description
This personal project aims not only to create a website that brings together all the projects I have developed during my academic and personal career, but also to deploy it on my own server, making it securely accessible from the Internet.

## Web development
For the construction of my portfolio I chose **Hugo**, a static website generation platform that allows you to create modern frontend pages using **Markdown** files. The decision to use Hugo was based on the fact that I had already written part of my portfolio in Obsidian, a tool (which is also written in Markdown) that I use regularly to take notes and organise my notes. Hugo's ability to take advantage of Markdown format files allowed me to migrate this content easily and focus more on the quality of the content than on the technical development.

The theme I selected for my portfolio is [hugo-theme-stack](https://github.com/CaiJimmy/hugo-theme-stack), because of its clean and modern format, which fits perfectly with the structure and design I was looking for. This template, with its focus on performance and simplicity, allowed me to optimise the development of my portfolio without having to invest too much time in the design of the interface.


## DevOps and Deployment
For deployment and operational management, my portfolio is hosted on a **Raspberry Pi 5 server with 8GB of RAM**, which provides an efficient and energy efficient solution. To ensure a secure and isolated environment, I use Docker, where the portfolio runs inside a container. This allows me to package the application independently from the rest of the system, making it easier to manage and avoiding conflicts with other services running on the same server.

The web server that handles the requests is **Caddy**, a lightweight solution that allows me to secure the connection with HTTPS automatically and redirect the traffic to the different services I have deployed. In addition to my own portfolio, I also host the portfolio of a fellow student, taking advantage of the server's capacity to handle multiple websites.

For development, I usually work locally using **Visual Studio Code**, although I occasionally use **GitHub Codespaces** when I prefer to work in a remote environment. The deployment process is simple: I connect to the server via SSH, pull the latest changes from GitHub and restart the Docker container running Hugo. This workflow is automated via a Docker Compose file, which simplifies the process of pulling up the web application with each update.