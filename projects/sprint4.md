---
title: StackOverflow CLI
layout: page
---

## Inspiration

As developers, there are two things that we noticed when we do a Google search for a programming-related question:
- we naturally gravitate towards the 'stackoverflow' results
- subconsciously we may have our own criteria to determine which link(s) will be the most useful, ex. clicking on the most recent post or the post with the most answers

When we search for answers on google, we run the risk of getting lost in the abyss that is the internet. What if there is a way to get the answers you need without leaving your window?

## What it does

- Search any query inside your terminal
- Receive top 10 threads related to your question
- Order the results in ascending/descending order
- Sort the results via relevance/votes/activity/creation

## How we built it

We used Node.js to bring this CLI to life. We also used several open-source packages available on npmjs.com to implement certain functionalities. While building this CLI, we made sure the CLI has the following characteristics:

- Clean user interface
- Great user experience
- Easy to use

## Challenge we ran into

None of us had previous experience with writing tests. So it was one of the blockers for us. Also, it was quite difficult to implement navigation between threads and answers.