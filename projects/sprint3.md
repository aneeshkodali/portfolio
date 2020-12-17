---
title: Shortify
layout: page
---

## Inspiration

There are a couple of reasons why we decided to build this web application. One of them is to save the readers time. Students who just want to go through a chapter can paste the entire chapter in this application and can get an overview. People who don't have time to read the entire article because of their busy schedules can use this application to get a gist of what they are reading.

## What it does

Shortify is a web application that is designed with a key point in mind i.e., to save user's time. It uses a Natural Language Processing (NLP) technique called BERT summarization extraction to provide the user a gist/summary of any article whatsoever. The client-side of the application uses React.js whereas the backend is designed in Flask, a python framework.

## How we built it

### React

As mentioned earlier, the clientside of the application is using React.js. It is a JavaScript frontend library developed by the folks at Facebook Inc. For writing the code, we made use of the following React.js practices:

- Controlled Components for state management
- Functional Components (Recommended by Facebook)
- React.js hooks for making API requests and dealing with the state

### Flask

We chose to work with Flask because the NLP model we used was written in python. The overall architecture is as simple as it gets. To make the clientside and backend talk, we wrote a route that was taking the content or the URL from the frontend and then sending the summary content as a response.

### BERT Model

In this project, we're using an NLP model (BERT). This model utilizes the HuggingFace Pytorch transformers library to run extractive summarizations. This works by first embedding the sentences, then running a clustering algorithm, finding the sentences that are closest to the cluster's centroids. This library also uses coreference techniques, utilizing the Neural Coref library to resolve words in summaries that need more context.

## Challenge we ran into

- Most of us were completely new to Machine Learning. Only one of the teammates had past experience with ML.
- All of us were mostly proficient with JavaScript. So working with python for the backend development was fairly new to us.
- Making the BERT extraction model run was one of the biggest challenges.