# JavaScript 2 Course Assignment

## Brief

Create an API with Strapi or find an existing external API.

It doesn’t matter what kind of data this API serves, but if you create a content type in Strapi, for example, it should have at least 3 custom properties.

For instance, if you create a `Team` content type, each team might have a `name`, `nickname` and `yearEstablished` property.

Submit your Strapi folder with your other code when delivering the project.

You can also build your own API in any other technology as long as it is publicly hosted. (The API only needs to be publicly hosted if you use a different framework or platform than Strapi).

Level 1 is required.

Level 2 and Level 3 are optional. If you attempt these levels please add a `README.md` file to your project that includes an admin username/email address and password that the markers can use to log in to your API.

---

Choosing appropriate variable and function names will form part of your assessment, as will proper and consistent formatting of your code.

## Level 1 Process

Build a frontend for your API and add the following:

### Home page

-   Make a GET request to fetch a list of resources from your API
-   Create HTML for each item and display at least 3 properties for each
-   Each item should also display a button or icon. Clicking on this button should toggle the item in and out of an array stored in localStorage
-   There should be a text input on this page that filters the array of results on one of the properties

### Favourites page

-   This page should fetch the array of items stored in localStorage and display them or display a message that there are no items.
-   There should be a "Clear all" button that clears localStorage (or just a specific key in localStorage) and reloads the display. Don’t reload the page, just redraw the HTML.

## Level 2 Process

Add a login form to your frontend that will allow a logged in admin user to perform the following tasks

-   Adding new resources to the API
-   Updating resources through an edit form
-   Deleting resources

## Level 3 Process

Add a registration form to your site and allow new users to register. These new users should not have the same permissions as the admin user from Level 2.

When a logged in user adds or removes an item from the favourites array, save the state of the array on the server via an API call.

When a logged in user navigates to the favourites page, the favourites array should be retrieved from the API rather than localStorage.

## Rules

-   Copying and sharing of any code will result in your assignment being given a mark of zero.
-   You may only use plain JavaScript for this assignment, no JavaScript libraries or frameworks. You may use CSS libraries like Bootstrap.

## Submission

-   Create a folder called your-name-js2-ca, e.g. mary-smith-js2-ca.
-   Add all your frontend code to this folder and add your Strapi folder if you used Strapi. If you attempted Level 2 or 3, remember to add a `README.md` file that includes an admin username/email address and password for the API project.
-   Remember to exclude the node_modules folder from your Strapi project before delivering.
-   Zip the folder and submit the zip file.

## Time

40 hours
