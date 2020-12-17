---
title: Localy
layout: page
---

## Inspiration

COVID-19 is still a global pandemic and local businesses have taken a hit as a result. However, pandemic or not, the need to support local endeavors exists in any scenario. It is our hope that this project inspired people to think, engage, and act locally.

## What it does

Localy is a web application designed for one purpose: think and act locally. Check out local organizations in need of financial or skill-based assistance or news regarding what's going on in your community.

At the moment, Localy provides following features to its users

- See businesses, schools, hospitals, orphanages, and other organizations in need of help
- Stay up-to-date on business, tech, and science news

## How we built it

The clientside of the application was built using React.js, a JavaScript frontend library developed by Facebook. Some other frontend considerations included:

Redux for state management Bootstrap for styling Material UI for icons

The serverside was built with Flask, a lightweight Python web development library. The following libraries were used in addition to Flask:

Flask-RESTful to create and organize endpoints Flask-MongoEngine to create database tables/columns and interact with database

For a database, we used MongoDB Atlas, a cloud NoSQL database. In order to carry out CRUD functionalities to maintain database content we used Flask-MongoEngine, an ODM (Object Document Mapper; see Flask section above).

We deployed our site using Heroku