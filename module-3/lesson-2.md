# Lesson 2

In this lesson we will look at:

-   JSON Web Tokens
-   a refresher on event.preventDefault()
-   a refresher on simple form validation
-   building a form that we'll use to log in to our API
-   storing the data sent back after a successful login in localStorage

## JSON web tokens (JWT)

Some API requests need to be authorised, we can't let the general public create or delete resources in our API, for example. We need a way to ensure a user is authorised to make the request.

One way to do this is to use JSON Web Tokens (JWT).

When a user logs in with valid credentials (valid username and password), a token is sent back to the client.

We can store this token and add it to the header of future requests that require authentication.

<img src="/images/jwt.png" style="max-width: 600px"/>

In this video we will use a POST request in <a href="https://www.postman.com/downloads/" target="_blank">Postman</a> to log in to our API and receive a JWT in return.

<iframe src="https://player.vimeo.com/video/461747650" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/461747650/b68578534d" target="_blank">View on Vimeo</a>

---

## event.preventDefault()

The default behaviour of a form submission will reload the page and so deny the rest of our code from executing.

The event.preventDefault() method stops that behaviour.

<iframe src="https://player.vimeo.com/video/453361604" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/453361604/765aa36966" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/submit-event-preventDefault" target="_blank">Code from the video</a>

---

## Simple form validation

If you are comfortable with performing simple validation on forms, skip to the next section.

<iframe src="https://player.vimeo.com/video/453789618" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/453789618/501a1e3296" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/simple-form-validation" target="_blank">Code from the video</a>

---

## Building a login form

Now we'll add a login form to our site that make the same POST request we did with Postman, this time using JavaScript.

<iframe src="https://player.vimeo.com/video/461852859" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/461852859/f139d77049" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/frontend-for-strapi-api/tree/step-2-login" target="_blank">Code from the video</a>

---

## Saving logged in data

In this video we'll save the JSON web token in localStorage so that we can make use of it in future API calls that require authentication.

We'll also store the user object that is returned after logging in.

This can be used to display the username of the logged in user.

<iframe src="https://player.vimeo.com/video/461926363" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/461926363/85121e9911" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/frontend-for-strapi-api/tree/step-3-saving-login-data-in-localstorage" target="_blank">Code from the video</a>

---

## Lesson Task

There are practice questions in the master branch of [this repo](https://github.com/NoroffFEU/lesson-task-js2-module3-lesson2).

---

[Go to lesson 3](3)

---
