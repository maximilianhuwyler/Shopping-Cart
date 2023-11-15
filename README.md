# Submissioncode: 03SM22MI0022 - Computer Network Security Principles (CNSP) - Challenge Task 2023

This repository contains the code for our challenge task submission for the course [Computer Network Security Principles](https://studentservices.uzh.ch/uzh/anonym/vvz/?sap-language=EN&sap-ui-language=EN#/details/2023/003/SM/51110725) course at [University of Zurich](https://www.uzh.ch/en.html).

## Table of Contents
* [Introduction](#introduction)
* [File Organization](#file-organization)
* [Getting Started: Installation and Execution](#getting-started-installation-and-execution)

## Introduction
In this repository, you will find the codebase for our submission, which extensively covers the core functionality and security enhancements implemented on the forked web-shop application.

The project serves as a practical learning experience, aligning with the learning objectives of a collaborative classroom setting. The accompanying Capture The Flag (CT) exercise encourages students to discuss and decide on theoretical concepts, fostering creativity and honing skills in offensive and defensive network security. Students, working in small groups, choose web services as their environment. This hands-on approach equips students with practical knowledge, allowing them to implement defense and offensive techniques effectively.

### Why did we fork the shopping-cart repository
We chose this rudimentary web-shop application for our challenge task due to its simplicity and accessibility. The codebase, discovered on the public GitHub repository, serves as an ideal foundation for us to understand and implement security measures. The application's uncomplicated front-end, built with HTML, CSS, and JavaScript, coupled with a Flask back-end and SQLite3 database, offers a practical platform for introducing and enhancing security concepts. Notably, the absence of security measures, except for password encoding, presents a valuable opportunity for us to fortify the system through proactive defensive and offensive strategies.

## File Organization
This is the file setup required to execute the project using Docker. There are two Dockerfiles, each dedicated to a specific container, and a Docker Compose file to connect them:
````
├── docker-compose.yml
├── nginx
│   └── nginx.Dockerfile
├── README.md
└── server
    └── Dockerfile
````

## Getting Started: Installation and Execution
- Make sure that Docker is up and running and [Docker Compose](https://docs.docker.com/compose/) is available.   
- Downloading, building the images, and initiating the containers can be accomplished in one step by using the following command in the root directory:
  ```bash
  docker compose up
  ```
