# Lesson 1

In this lesson we will look at:

-   the ternary operator
-   object destructuring
-   a brief overview of APIs
-   HTTP request methods
-   creating a custom API with Strapi
-   a refresher on retrieving parameters from the querystring
-   making GET requests to our local Strapi API

## The ternary operator

The ternary operator is a frequently used shorthand way to write an if/else statement.

<iframe src="https://player.vimeo.com/video/460600855" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/460600855/ee87b47060" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/ternary-operator-example" target="_blank">Code from the video</a>

---

## Object destructuring

Object destructuring is a way to retrieve properties from objects.

<iframe src="https://player.vimeo.com/video/460712855" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/460712855/91150dade5" target="_blank">View on Vimeo</a>

---

## What is an API?

An Application Programming Interface, in our case, is a layer of backend code written in a server-side language or framework like Node.js, .NET, Python, PHP, Java (not to be confused with JavaScript), etc that we call from our website or app.

The API provides the functionality for a site or app and is almost always backed by some kind of data store that maintains the data for the site or app. The data store could be a SQL database like MySQL or PostgreSQL, a NoSQL document-store like MongoDB or a simple file-system DB like SQLite.

The two primary types of APIs are REST (which is the kind we are working with) and GraphQL.

<img src="/images/api.png" style="max-width: 700px"/>

## HTTP request methods

REST APIs use HTTP request methods as a way of interacting with the API.

You will be familiar with `GET` request methods as these are the methods used to fetch data from APIs.

There are several other methods, sometimes called HTTP verbs. We will explore the following methods:

### POST

This is used to send data, or "entities", to the server.

It is a method commonly used to perform login actions or to create a new resource like, for example, a new product.

### PUT

This method is used to replace all data for a specific resource.

It could be used, for example, to update all the values for a product.

It is similar to the PATCH method which only updates some of the values in an entity.

### DELETE

This is used to delete an existing resource.

---

## Strapi

Strapi is an open-source `headless` CMS.

This means it provides an admin panel to create our own APIs that we can call from our frontends.

It is written in Node.js which means both our frontend and backend API will be written in JavaScript.

The video below provides a brief look at setting up a very simple REST API using Strapi.

We will run it locally but there are a variety of hosting options to make an API you create with Strapi available publiclly.

You can find the official docs on [their site](https://strapi.io/).

<iframe src="https://player.vimeo.com/video/461538074" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/461538074/2698aaa310" target="_blank">View on Vimeo</a>

---

## Retrieving querystring parameters

This video goes over getting values out of the querystring.

If you are comfortable doing this you can skip to the next section.

<iframe src="https://player.vimeo.com/video/453021027" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/453021027/cc9e8cce3f" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/retrieving-parameters-from-querystrings" target="_blank">Code from the video</a>

---

## Strapi GET requests

The video below covers making GET requests to our local Strapi API from a frontend project.

<iframe src="https://player.vimeo.com/video/461732700" width="640" height="270" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/461732700/54c6f85a6b" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/frontend-for-strapi-api" target="_blank">Code from the video</a>

---

## Activity

### Read

[An overview of HTTP](https://wiki.developer.mozilla.org/en-US/docs/Web/HTTP/Overview)

---

## Lesson Task

There are practice questions in the master branch of [this repo](https://github.com/NoroffFEU/lesson-task-js2-module3-lesson1).

---

[Go to lesson 2](2)

---
