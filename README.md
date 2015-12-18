# An Integrated crowd sourcing, Remote Sensing Change Monitoring platform

## What is this repository about?

This is the main repository of the last week assignment as part of the Geo-Scripting course, taught at Wageningen University, The Netherlands. This project is designed to be the assignment of three students team, who will collaborate and complement each others work toward setting up an integrated change monitoring platform.

## What is an intgrated Change monitoring platform?

We define in this context an integrated change monitoring platform as a webpage from which various users can visualize and interact with near-real time land change information. We call it integrated since the change information originates from multiple sources; crowd soursing using smartphone technologies and automated change detection from remote sensing images.

## Challenges of setting up such a platform

Because it is integrated, every component of the platform need to work well with each others. As you will be multiple teams working on the platform, it is 

## How to contribute to this project

The present repository will be the main repository of the project. Every team is assigned a well defined topic to work on, as well as clear instructions about which part of the project to contribute. Your contributions to this repository will be merged via pull requests, which means that you will need to first fork the repository to your own github account and contribute to that repository. Once you have achived your goals, and you have added a well structured and working contribution to the project, please submit a pull request to the present repository.
Given that the input of each team will depend on the outputs of the other teams, we will provide test datasets for every crital input.

## Components of the system

A team will be assigned to each components of the system

|              Name              |   Language  |                                                                              Tasks                                                                               |
| ------------------------------ | ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Data ingestion                 | Python      | Automated data download of MODIS VI?, data cleaning, database ingestion                                                                                          |
| Crowdsourced                   | Python/JS ? | Collect twitter? feed, update database, place them on a web-map, derive output (confusion matrix between crowd sourced information and change detection results) |
| Automated detection of changes | Python      | Read data from database, run simple change detection algorithm, update change information layers of database                                                     |
| Visualization/interactivity    | JS/CSS/HTML | Do we need some geo-server stuff? Sounds complicated, should we give that to the students, do it ourselves, find an easy way around?                                                    |
|                                |             |                                                                                                                                                                  |

TODO: Add diagram of tasks, inputs/outputs

## Project supervisors

Loïc
Johannes ?
Fritz ?
