---
title: Web Service Deployment with EC2 AWS
description: Creating a load balancer that distributes requests between two EC2 instances, each with its own Apache server and web page.
slug: aws-ec2
date: 2023-11-15 00:00:00+0000
image: aws.png
categories:
    - Parallel programming
tags:
    - Bash
    - WSL
    - EC2
    - Apache
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

This project was developed for a Systems Architectures and Distributed Systems (ASSB) assignment during my fourth year of undergraduate studies. The main objective was to deploy a functional web service in a cloud environment using **AWS** services, keeping within the limits of the free plan.

**This web service consisted of a load balancer that distributed requests between two EC2 instances, each with its own Apache server and web page.**

The main tasks performed included:

- **Controlling and creating cost alerts**: Setting up alerts in AWS to ensure that all operations conformed to the free plan, avoiding unwanted additional charges.
- **Deployment of EC2 instances**: Raise two instances of **EC2** and connect to them via **SSH**. On each of the instances, install the **Apache** web server.
- **Configuring web servers**: Configuring the Apache services on both instances to serve a static web page I created myself.
- **Deployment of a load balancer**: Deployment of a load balancer on AWS, which distributes incoming requests evenly between the two Apache servers, optimising the load and ensuring higher availability.


[**View memory in pdf**](/aws-ec2.pdf)

