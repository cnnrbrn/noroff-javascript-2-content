# Lesson 3

In this lesson we will look at:

-   creating a dynamic menu
-   creating a new resource in an API through a POST request
-   updating a resource through a PUT request

We'll be adding a JSON web token to our POST and PUT requests as both require authentication.

## Creating a dynamic menu

Our site doesn't have any navigation yet.

In this video we will add a menu that will add an active class to the current menu item using the location object, and change the HTML it displays depending on whether the user is logged in or not.

<iframe src="https://player.vimeo.com/video/461959625" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/461959625/878b8d9467" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/frontend-for-strapi-api/tree/step-4-dynamic-menu" target="_blank">Code from the video</a>

---

## Creating new resources

Here we'll create a form that will send a POST request to our API to create a new product.

As this request requires authentication, we will retrieve the JWT from localStorage and add it to the Authorization key in the header of our request.

First we'll look at how to make the POST request using Postman

<iframe src="https://player.vimeo.com/video/462113012" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/462113012/d9bbaf17f9" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/frontend-for-strapi-api/tree/step-5-post-request-form" target="_blank">Code from the video</a>

---

## Updating resources

In the following we'll use a form to update a product via PUT request from a form.

In our script we will first retrieve the product details via a GET request, and populate our form with those details.

We'll store the product ID in a hidden field in our form as we need the ID to make the PUT request.

We'll again add the JWT to the header of this request.

<iframe src="https://player.vimeo.com/video/462164343" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/462164343/1060593015" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/frontend-for-strapi-api/tree/step-6-put-request-form" target="_blank">Code from the video</a>

---

## Lesson Task

There are practice questions in the master branch of [this repo](https://github.com/NoroffFEU/lesson-task-js2-module3-lesson2).

---

-   [Go to lesson 4](4)

---
