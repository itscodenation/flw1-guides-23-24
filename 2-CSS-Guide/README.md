# CSS Guide

Dive into the world of Cascading Style Sheets (CSS) with this guide. Explore CSS syntax, properties, values, layouts, and the box model. For hands-on learners, don't hesitate to use the provided code snippets and see them in action!

## Table of Contents

- [CSS Syntax](#css-syntax)
- [CSS Properties and Values](#css-properties-and-values)
- [CSS Layout and Box Model](#css-layout-and-box-model)
- [CSS Flexbox](#css-flexbox)

---

## CSS Syntax

In CSS, each rule-set consists of a **selector** and a declaration block:

```css
img {
 height: 30px;
 border: 1px solid red;
}
```

- **Selector**: Points to the element(s) you wish to style. Selectors can be based on element name, class, or id.
- **Property**: Specifies what attribute you wish to change.
- **Value**: Dictates the value to which you're setting the property.

---

## CSS Properties and Values

Here are some fundamental CSS properties, their possible values, and their impact:

| Property | Code Examples | Description |
|----------|---------------|-------------|
| Text | `font-family: "Comic Sans"; font-size: 12px; text-align: center; color: blue;` | Modifies font, size, alignment, and color |
| Color | `background-color: #000000; color: yellow;` | Adjusts background and font colors |
| Background | `background-color: pink; background: url("ex.png");` | Sets background color or image |
| Size | `width: 50px; width: 50%; font-size: 20px;` | Configures width and font size |
| Display | `display: "none"; display: "block";` | Shows or hides content |
| Border-Radius | `border-radius: 500px;` | Rounds corners |
| Opacity | `opacity: 0.5;` | Controls transparency (0 for fully transparent, 1 for opaque) |

---

## CSS Layout and Box Model

All HTML elements are rendered as boxes. Understand the structure with padding, border, and margin.

| Box Area | Code Examples | Description |
|----------|---------------|-------------|
| Content | `<p>hey</p> <img src="cat.jpg">` | Not a CSS property; represents any HTML element |
| Padding | `padding: 20px; padding-left: 100px;` | Space between content and border |
| Border  | `border: 2px solid red; border-right: 10px solid black;` | Encloses the padding and content |
| Margin  | `margin: 150px; margin-top: 25px;` | Space outside the border |

Use different values for each side of an element (top, right, bottom, left) for detailed control.

---

## CSS Flexbox

Enable flexible layouts using Flexbox:

### Setting up Flexbox

Activate Flexbox for a container:
```css
.container {
  display: flex;
}
```

### Child Element Alignment

| Value | Code Example | Description |
|-------|--------------|-------------|
| flex-start | `.container { display: flex; justify-content: flex-start; }` | Aligns children to start |
| center | `.container { display: flex; justify-content: center; }` | Aligns children to center |
| flex-end | `.container { display: flex; justify-content: flex-end; }` | Aligns children to end |
| space-between | `.container { display: flex; justify-content: space-between; }` | Spaces children evenly |
| space-around | `.container { display: flex; justify-content: space-around; }` | Even spacing around children |

### Columns

For column-based layouts:

```css
.section { display: flex; }
.left { width: 25%; }
.right { width: 75%; }
```

---

**Keep practicing and dive deeper into CSS! The more you explore, the more techniques you'll discover to design the perfect web page.**

---