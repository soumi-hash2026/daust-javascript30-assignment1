# LocalStorage & Event Delegation

## About the Project

This project is part of my JavaScript 30 assignment, following the course by Wes Bos.

The project is a small interactive food list called **Local Tapas**. Users can add food items, mark them as completed, and save their list in the browser using LocalStorage.

## Technologies Used

* HTML
* CSS
* JavaScript
* Browser LocalStorage
* VS Code
* Live Server

## What I Am Learning

* DOM manipulation
* JavaScript events and event listeners
* Form handling
* Arrays and objects
* Array methods
* Template literals
* Event delegation
* JSON and LocalStorage
* Saving and retrieving data in the browser

## Progress

* [x] Downloaded the starter files from the JavaScript30 repository.
* [x] Opened the project in VS Code.
* [x] Ran the project using Live Server.
* [x] Explored the HTML and CSS starter files.
* [x] Selected HTML elements using `document.querySelector()`.
* [x] Handled form submissions using `addEventListener()`.
* [x] Used `e.preventDefault()` to prevent the page from reloading on form submission.
* [x] Retrieved food names from the input field.
* [x] Created food objects with `text` and `done` properties.
* [x] Added objects to an array using `items.push(item)`.
* [x] Used `this.reset()` to clear the form.
* [x] Created `populateList()` to display food items.
* [x] Used `map()` and template literals to generate HTML.
* [x] Added checkboxes and labels to the food list.
* [x] Used `console.log()` and `console.table()` to inspect data.
* [x] Explored the browser's Developer Tools and Application tab.
* [x] Saved the food array using `localStorage.setItem()`.
* [x] Converted the array to JSON using `JSON.stringify()`.
* [x] Retrieved saved data using `localStorage.getItem()`.
* [x] Converted JSON text back into JavaScript data using `JSON.parse()`.
* [x] Loaded saved items when initializing the application.
* [x] Practiced event delegation using `itemsList.addEventListener()`.
* [x] Used `data-index` to identify the selected food item.
* [x] Updated an item's `done` status when its checkbox was clicked.
* [x] Saved checkbox changes to LocalStorage.
* [x] Completed a final test of all features after refreshing the page.

## What I Learned

* How `document.querySelector()` selects an HTML element.
* How `document.querySelectorAll()` selects multiple HTML elements.
* How `addEventListener()` listens for events.
* How `e.preventDefault()` prevents the default form submission.
* How `e.target` identifies the element that triggered an event.
* How `e.target.matches('input')` checks whether the clicked element is an input.
* How `this.querySelector('[name=item]').value` retrieves the entered food name.
* How `this.reset()` clears a form.
* How to create an array using `const items = []`.
* How `items.push(item)` adds an object to an array.
* How to create objects with properties such as `text` and `done`.
* How to pass arguments to a function.
* How `map()` processes array elements to generate HTML.
* How template literals use backticks and `${...}` to insert values.
* How `innerHTML` inserts generated HTML into a page.
* How `join('')` combines strings into a single string.
* How checkboxes represent an item's completion status.
* How `data-index` identifies an item's position in the array.
* How `dataset.index` retrieves a custom data attribute.
* How `!items[index].done` toggles a Boolean value between `true` and `false`.
* How `localStorage.setItem()` saves data in the browser.
* How `localStorage.getItem()` retrieves saved data.
* How `JSON.stringify()` converts JavaScript data into JSON text.
* How `JSON.parse()` converts JSON text back into JavaScript data.
* How `|| []` provides an empty array as a fallback when no saved items exist.
* How event delegation allows a parent element to handle events from its children.
* How to use browser Developer Tools to inspect JavaScript data and LocalStorage.

## How to Run

1. Open `index-START.html` in VS Code.
2. Run it using Live Server.
3. Add food items using the form.
4. Use the checkboxes to mark items as completed.
5. Refresh the page to test whether the items and their completion states are preserved.

## Credits

* Course: [JavaScript 30](https://javascript30.com/)
* Instructor: Wes Bos
* Original repository: [Wes Bos JavaScript30](https://github.com/wesbos/JavaScript30)
