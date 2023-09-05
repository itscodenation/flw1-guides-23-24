# JavaScript Guide

## Table of Contents
1. [Variables](#1-variables)
2. [Data Types](#2-data-types)
3. [Functions](#3-functions)
4. [DOM Manipulation](#4-dom-manipulation)
5. [Events](#5-events)
6. [Objects](#6-objects)
7. [Loops](#7-loops)
    - [forEach Loop](#foreach-loop)
    - [for of Loop](#for-of-loop)
8. [APIs](#8-apis)
    - [API Request URL](#api-request-url)
    - [fetch() Request](#fetch-request)
    - [API Methods](#api-methods)

---

## 1. Variables

In JavaScript, variables are used to store values. You can declare a variable using the `let`, `const`, or `var` keyword.

```javascript
let name = "Alice";
const PI = 3.14159;
```

- `let`: Declares a block-scoped, local variable, optionally initializing it to a value.
- `const`: Declares a block-scoped, read-only named constant.

---

## 2. Data Types

JavaScript has various data types, including:

- **Numbers:** `let age = 30;`
- **Strings:** `let text = "Hello, world!";`
- **Booleans:** `let isTrue = false;`
- **Null:** `let empty = null;`
- **Undefined:** `let notDefined;`

---

## 3. Functions

Functions are blocks of reusable code. 

**Example:**
```javascript
function greet(name) {
    return "Hello, " + name + "!";
}
```

To call a function:
```javascript
greet("Alice");  // Returns: "Hello, Alice!"
```

---

## 4. DOM Manipulation

The Document Object Model (DOM) represents the structure of an HTML document. With JavaScript, you can manipulate the DOM to change the content, structure, and style of a webpage.

**Example:**
```javascript
document.getElementById("myText").innerHTML = "New Text!";
```

This will change the content of the HTML element with the ID `myText` to "New Text!".

---

## 5. Events

JavaScript can detect various actions taken by a user, called "events". You can set up functions to run when a certain event occurs.

**Example:**
```javascript
button.addEventListener("click", function() {
    alert("Button was clicked!");
});
```

This will display an alert when a button is clicked.

---

## 6. Objects

### Object Syntax
An object in JavaScript represents a collection of related data in the form of key-value pairs.

```javascript
let classroom = {
    subject : "English", 
    teacher : "Ms. C", 
    durationInMinutes : 60
};
```

You can access the values within an object either using dot notation or bracket notation.

---

## 7. Loops

### forEach Loop

The `forEach` loop is a method specifically for arrays, allowing you to execute a function on each item in the array.

**Example:**
```javascript
let courses = ["history", "math", "science"];
courses.forEach(function(course) {
    $("#schedule").append("<p>" + course + "</p>");
});
```

### for of Loop

The `for of` loop is a newer loop in JavaScript, designed for iterating over iterable objects like arrays.

**Example:**
```javascript
let courses = ["history", "math", "science"];
for(let course of courses){
    $(".schedule").append("<p>" + course + "</p>");
}
```

---

## 8. APIs

APIs, or Application Programming Interfaces, allow communication between different software applications.

### API Request URL

For instance, an API URL like `api.giphy.com/v1/stickers/search/?q=dog&api_key=dc6zaT0xFJmzC` is composed of:

- **Base Url:** The consistent part of the URL.
- **End Point:** Refers to a specific object or set of objects.
- **Query String:** Begins after the `?` and has parameters separated by `&` signs.

### fetch() Request

The `fetch()` function provides a simple interface for fetching resources.

**Syntax:**
```javascript
fetch('API_URL')
    .then(function(response) {
        return response.json();
    })
    .then(function(data) {
        console.log(data);
    });
```

### API Methods

- **GET:** Retrieve data from a server.
- **POST:** Send new data to a server.
- **PUT:** Update existing data on a server.
- **DELETE:** Remove data from a server.

This guide provides an overview of basic JavaScript concepts and is by no means exhaustive. As you continue learning and practicing JavaScript, you'll uncover more advanced topics and nuances. 

Happy coding!
