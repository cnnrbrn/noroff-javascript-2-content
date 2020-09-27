# Lesson 4

In this lesson we will look at:

-   A practical use for an IIFE - immediately invoked function expression
-   A practical use for classes

## IIFE

An immediately invoked function expression is a function that is declared and then immediately called.

It has the following syntax.

```js
(function () {
    // do something
})();
```

The video takes a look at a practical example.

<iframe src="https://player.vimeo.com/video/459377797" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/459377797/aad5ef3b9b" target="_blank">View on Vimeo</a>

---

## Classes

Classes are declared with the `class` keyword.

```js
class Block() {

}
```

Classes have a method - a function - called a `constructor` which is called each time an object is created with the `new` keyword.

We can pass variables into classes in the constructor method and set properties inside the class with these values. This is called initialising a class.

```js
class Block() {
    constructor(label) {
        this.label = label;
    }
}
```

We can add our own methods to classes:

```js
class Block() {
    constructor(label) {
        this.label = label;
    }

    printLabel() {
        console.log(this.label);
    }
}
```

We create a new object from a class using the `new` keyword and pass values in to the constructor.

```js
const myBlock = new Block("My label");
```

Once the object is created we can call the methods it contains:

```js
myBlock.printLabel();
// "My label"
```

The following video contains a practical introduction to classes.

<iframe src="https://player.vimeo.com/video/459504923" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/459504923/ca04e2d0e3" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/class-example" target="_blank">Code from the video</a>

---

## Activity

### Read

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes" target="_blank">The MDN reference on classes</a>

---

## Lesson Task

There are practice questions in the master branch of [this repo](https://github.com/NoroffFEU/lesson-task-js2-module2-lesson4).

Attempt the answers before checking the [answer branch](https://github.com/NoroffFEU/lesson-task-js2-module2-lesson4/tree/answer) of the repo.

---

-   [Go to the module assignment](ma)

---
