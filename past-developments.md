# Developments

I have worked as a web developer for all of my professional life. Here are some interesting things.

## Darts

I played a lot of darts during the pandemic with my neighbors. I wanted to make a game tracker that was fun to use with friends.
I also wanted to test out some libraries too.
It's open source :)

[Darts repo](https://pausebreak.github.com/darts)

[Darts app](https://pausebreak.github.io/darts)

## Opengov

2016-2022

Node, Typescript, D3, React, immutable.js, immer, css_modules, reselect, knex, redshift, docker, kubernetes, micro services. I reverse engineered the direct DOM manipulation output of D3 into a functional React library more conducive to a dynamic data application.

A pretty intense UI -> SQL generator for arbitrary time series data.

![graph](/opengov-graph.png)

## Albuquerque Band Tree

(defunct) 1996?

A Geocities hosted web app tracking band members movements between bands in Albuquerque New Mexico. It had a static js data structure that I would manually update.
A user could traverse the tree seeing 3 slices (frames) at a time. The center frame would show the selected band and player. The left pane would show the last band the player was in.
The right showing the next band the player moved on to.
The interesting part was the frames were generated at runtime in javascript.

## The story that wrote itself

(defunct) 2002?

A concept site where the user enters the next sentence in the story and the backend would replace nouns with synonyms.
The synonyms came from scrapping a dictionary site. Implemented a durable cache of synonyms per word to get around rate limiting.
People abused the site :)
