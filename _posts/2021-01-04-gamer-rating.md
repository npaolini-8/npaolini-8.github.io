---
title: Angular - Gamer Rating
layout: post
post-image: "https://cdn.discordapp.com/attachments/683692219345010761/928502327688716378/unknown.png"
description: Utilizes Angular and competitive game APIs to aggregate player statistics.
tags:
- Angular
- API
- AWS
- Typescript
- Web Development
---

Final project of Web Programming course taken in Summer 2021, assignment was to use any framework and use some API to complete a task. I picked Angular out of a hat to try this with and it ended up feeling like overkill, probably should have done it in React.

---

# Overview

The goal of this application is for a player to be able to search for their profiles across many different competitive games and determine an aggregate score which represents their "overall gaming rank". While each game has it's own ranking system, each rank is always related to the player population. Using these rank percentiles allows for comparable data to be used to calculate an overall ranking. The application is designed to work with multiple APIs.

### Functions

User selects the game they want to add a profile from using the dropdown to the left of the search bar. They then enter a player id, and click search. If a matching profile is found it is added to the pool of games. A tile is displayed with game and profile information, including game name, logo, and platform icon, and player name, rank, and ranking percentile. When a user wants to calculate their rating, they can click the "Calculate" button, which will use the attached profile data to calculate a rating.

### Hosting

Application information was stored in an AWS S3 bucket and then transferred to an EC2 instance running Apache.

### Technologies Used
* Angular
* Typescript
* HTML
* SCSS
* AWS (EC2/S3)
* Apache