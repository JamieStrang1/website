
+++
title = "Multi-VM Web Application"
date = 2026-10-01
draft = false
description = "A full-stack Movie & TV Watchlist application deployed across three virtual machines."
tags = ["Python", "Flask", "PostgreSQL", "Vagrant", "Linux"]
+++

## Overview

Developed a full-stack Movie & TV Watchlist web application deployed across three Ubuntu virtual machines. The project focused on building a multi-tier architecture, separating the frontend, application logic, and database into independent systems.

The application allows users to browse, search, filter, and sort movies and TV shows, with watchlist statistics displayed through a web interface.

## What I Did

- Built a three-tier architecture using separate web, API, and database servers.
- Developed a Flask REST API to handle requests and communicate with a PostgreSQL database.
- Used Apache to serve the frontend, built with HTML, CSS, and JavaScript.
- Configured networking and communication between the three virtual machines.
- Used Vagrant and VirtualBox to provision the Ubuntu environments.
- Automated environment configuration and deployment using setup scripts.
- Implemented testing and verification scripts to check application functionality.

## Key Takeaways

This project strengthened my understanding of full-stack web development, virtualisation, networking, and database integration.

It also provided practical experience deploying and managing a distributed application, including troubleshooting communication between services and automating infrastructure setup.

This project provided the foundation for my subsequent [AWS Infrastructure with Terraform](/projects/aws-infrastructure/), where I explored deploying and managing infrastructure in a cloud environment rather than on local virtual machines.

## GitHub Repository

[View the project on GitHub](https://github.com/JamieStrang1/multi-vm-web-app)
