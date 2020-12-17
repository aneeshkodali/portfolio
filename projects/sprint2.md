---
title: PicFlix
layout: page
---

## Inspiration

We knew we would not be able to build a game via game engine (Unity) due to time constraints and the steep learning curve. We still wanted to create something interested, so we decided to try and implement a multiplayer game that involved establishing and maintaining connections among multiple users. Having established this core capability, we decided to make some sort of guessing game in which a user displays something that relates to the word(s) that the participants must guess. For the specifics regarding the goal of the guessing, we decided to make the goal as guessing a tv show or movie based on a limited number of allowed images (ex. image of a "game" + image of a "throne" = "Game of Thrones")

## What it does

- create/join a room to play a game
- chat with participants in the lobby
- display images/messages asynchronously to all participants in a room
- conditionally render the searchbar + results components if the user is the host (because the participants seeing what is being searched for defeats the purpose of the game)

## How we built it

- Frontend: React + Bootstrap Styling
- Image API: Unsplash
- Backend: Node + Express
- SocketIO/SocketIO Client for establishing and managing socket connections

## Challenge we ran into

- understanding socket
- due to unforseen circumstances, one of our teammates was unable to be a part of this most recent sprint, so that affected how much of the project goal we were able to accomplish.