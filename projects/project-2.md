---
layout: project
type: project
image: images/norm.jpg
title: Smart Campus Energy Lab
permalink: projects/scel
# All dates must be YYYY-MM-DD format!
date: 2017-01-08
labels:
  - Javascript
  - Vagrant
  - XCTU
  - GitHub
  - Nginx
  - Eagle
  - PostgreSQL
summary: Environmental data collection via weatherboxes for energy conservation.
---

<img src="../images/weatherbox.png" width="1000">

The Smart Campus Energy Lab researches weather/environmental data for weather analysis and prediction which will be used to help conserve campus-wide energy use.

SCEL is currently deploying weatherboxes on the roof of Holmes Hall. Current weatherbox designs are based upon Arduino circuits with additional sensors and radios for data collection and transmission. Environmental data gathered by the weatherboxes are transmitted wirelessly to a central hub which parses the data and stores it in a postgres database. Intial data collection is ongoing and analysis will be tested once sufficient data is collected.

The project is comprised of multiple subteams which work on hardware, firmware and software. I am a member of the software team whose primary responsibilities include the development of the firmware for the weatherboxes as well as the backend for the data management. I have contributed to the development of the firmware as well as developing a modular testing platform which allowed the software team to develop firmware independently from the hardware team workflows. I have also implemented a reverse proxy for the backend server which facilitates the implementation of an API for future modularity.

More information about this project can be found on the [SCEL Project Website](http://scel-hawaii.org/) as well as the [SCEL Project Wiki](https://wiki.scel-hawaii.org/doku.php).
