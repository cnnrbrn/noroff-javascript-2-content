# Lesson 2 - Imports and exports using modules

We can split our code up into files using modules.

In order to import code from another file we need to export it first.

There are two kinds of exports.

## Named exports

Named exports are exported with the `export` keyword and imported using their name between braces.

<img src="/images/imports-exports-1.png" style="max-width: 800px"/>

One file can contain many named exports.

You can alias a named export usign the `as` keyword.

<img src="/images/imports-exports-2.png" style="max-width: 800px"/>

## Default exports

Default exports are exported with the `export default` keywords and imported without braces.

<img src="/images/imports-exports-3.png" style="max-width: 800px"/>

When you import a default export, you can import it using any name, the name you use in the import is really just an alias.

---

## Navigating directories

### Go up a folder

`../` - go back (or up) one directory (folder) from the current directory.

You can use several of these, the below will go back three folders:

`../../../`

### Look in the current folder

`./` - look in the current folder for the path

---

## Imports and exports

The following video takes a look at using imports and exports.

<iframe src="https://player.vimeo.com/video/457199012" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/457199012/f3e2f37cfe" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/import-export" target="_blank">Code from the video</a>

---

## Import/export example

The following video converts a small existing project to use modules, splitting the code up using imports and exports.

<iframe src="https://player.vimeo.com/video/456346771" width="640" height="400" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

<a href="https://vimeo.com/456346771/61a3fcad19" target="_blank">View on Vimeo</a>

<a href="https://github.com/NoroffFEU/import-export-example" target="_blank">Code from the video</a>

---

<!--
## Lesson Task

There is a practice question in the master branch of [this repo](https://github.com/NoroffFEU/lesson-task-js2-module1-lesson2).

Attempt the answer before checking against the example answer in the [answer branch](https://github.com/NoroffFEU/lesson-task-js2-module1-lesson2/tree/answer) of the repo. -->

---

[Go to lesson 3](3)

---
