# Docker - multi-container app

## Description

A simple project to demonstrate the setup of a multi-container docker application.

## System requirements

1. [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Start and stop in development

1. First time and after dependency changes, run `docker-compose up --build`
2. To stop the application, stop the running process from the terminal (`ctrl` + `c`)
3. For restarts, run `docker-compose up`
4. To remove the containers from the system, run `docker-compose down`. Note: this will remove any persisted data (in the database).
