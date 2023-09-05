# HTML Guide

This guide is a quick reference for various HTML elements, their structures, and common attributes. Make sure to practice using these code snippets to better understand HTML.

## Table of Contents

- [Basic Structure of an HTML Document](#basic-structure-of-an-html-document)
- [HTML Elements](#html-elements)
- [Nesting and Indentation](#nesting-and-indentation)
- [HTML Elements with Attributes](#html-elements-with-attributes)
- [Id vs. Class Attributes](#id-vs-class-attributes)

---

## Basic Structure of an HTML Document

An example of a basic HTML page structure is given below:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Page</title>
  </head>
  <body>
    <p>My first paragraph</p>
  </body>
</html>
```

---

## HTML Elements

Here are some basic HTML elements and their respective output when rendered:

| Element | Code Example | Output |
|---------|--------------|--------|
| Paragraph | ```<p></p>``` | ```<p>This is a paragraph.</p>``` |
| Heading | ```<h1></h1> to <h6></h6>``` | From ```<h1>Heading level 1</h1>``` to ```<h6>Heading level 6</h6>``` |
| Ordered List | ```<ol><li></li></ol>``` | ```<ol><li>George Washington</li><li>John Adams</li></ol>``` |
| Unordered List | ```<ul><li></li></ul>``` | ```<ul><li>George Washington</li><li>John Adams</li></ul>``` |
| Line Break (Self-closing) | ```<br>``` | ```<br>``` |
| Button | ```<button></button>``` | ```<button>Click Me</button>``` |
| Div | ```<div></div>``` | ```<div>This is a div</div>``` |
| Input (Self-closing) | ```<input>``` | ```<input>``` |

---

## Nesting and Indentation

HTML allows nesting, meaning you can place one tag inside the content of another. Proper indentation makes your code more readable.

Example:

```html
<div>
  <h1>Weekday</h1>
  <p>Monday</p>
</div>
```

---

## HTML Elements with Attributes

Attributes provide additional information about an element. Here are some examples:

| Element | Code Example | Output |
|---------|--------------|--------|
| Image (Self-closing) | ```<img src=" ">``` | ```<img src="https://imgur/cats.png">``` |
| Link (Anchor Tag) | ```<a href=" "></a>``` | ```<a href="https://www.google.com">This is a link to Google</a>``` and ```<a href="https://www.youtube.com" target="_blank">YouTube popout</a>``` |
| Input with Placeholder (Self-closing) | ```<input placeholder=" ">``` | ```<input placeholder="type here">``` |

---

## Id vs. Class Attributes

**IDs** and **Classes** are attributes used to identify and style HTML elements.

### Classes:

- Assign: ```<div class="my-class">```
- CSS Selector: ```.my-class { text-align: right; }```
- Multiple Classes: ```<li class="important busy">```

**Notes:** Classes are case-sensitive, can't start with a number, and multi-word classes should be hyphenated (e.g., `class="go-button"`).

### IDs:

- Assign: ```<div id="my-id">```
- CSS Selector: ```#my-id { color: blue; }```

**Notes:** IDs are unique per element and per page and are case-sensitive.

---

**Keep practicing, and soon HTML will become second nature!**

---