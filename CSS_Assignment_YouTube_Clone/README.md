# YouTube Clone

## Table of Contents

- [Overview](#overview)
- [HTML Tags and Properties](#html-tags-and-properties)
- [CSS Properties and Values](#css-properties-and-values)
- [Additional Information](#additional-information)

## Overview

This readme provides an overview of the HTML and CSS code for a YouTube clone webpage. It covers key tags, properties, values, their purposes, and additional details about the project.

## HTML Tags and Properties

| Tag          | Property            | Value             | Purpose                                       |
|--------------|---------------------|-------------------|-----------------------------------------------|
| `<html>`     | `lang`              | `"en"`            | Specifies the language of the document.       |
| `<meta>`     | `charset`           | `"UTF-8"`         | Sets the character encoding for the document. |
| `<meta>`     | `name`              | `"viewport"`      | Defines the viewport settings for responsiveness. |
| `<title>`    |                     |                   | Sets the title of the webpage.                |
| `<link>`     | `rel`               | `"stylesheet"`   | Links an external CSS file to the HTML file.  |
| `<nav>`      | `class`             | `"navbar"`        | Defines a navigation bar.                     |
| `<div>`      | `class`             | `"header-left"`   | Creates a container for the left part of the header. |
| `<svg>`      | `xmlns`             | `"http://www.w3.org/2000/svg"` | Specifies the XML namespace for SVG images. |
| `<img>`      | `src`               |                   | Embeds an image in the webpage.               |
| `<input>`    | `type`              | `"search"`        | Defines an input field for search.            |

## CSS Properties and Values

| Property           | Value                  | Purpose                                       |
|--------------------|------------------------|-----------------------------------------------|
| `box-sizing`       | `border-box`           | Includes padding and border in element's total width and height. |
| `margin`           | `0`                    | Sets margin to zero for all elements.         |
| `padding`          | `0`                    | Sets padding to zero for all elements.        |
| `background-color` | `white`                | Sets the background color of the header.      |
| `height`           | `70px`                 | Defines the height of the header.            |
| `display`          | `flex`                 | Displays elements in a flexible box layout.   |
| `align-items`      | `center`               | Centers items vertically in a flex container. |
| `position`         | `fixed`                | Positions the header as a fixed element.      |
| `justify-content`  | `space-between`        | Distributes space evenly between items.       |
| `border`           | `1px solid rgb(192, 192, 192)` | Adds a border to the search container.  |
| `border-radius`    | `5px`                  | Rounds the corners of the search container.  |
| `outline`          | `none`                 | Removes the outline on input focus.           |
| `width`            | `100%`                 | Sets the width to 100% for various elements.  |
| `min-width`        | `160px`                | Sets a minimum width for the left sidebar.    |
| `overflow-y`       | `scroll`               | Adds a vertical scrollbar for overflowing content. |
| `scrollbar-width`  | `none`                 | Hides the scrollbar in Firefox.               |

## Additional Information

### What new properties did I learn about?

- `box-sizing`, `outline`, `scrollbar-width`: These CSS properties were used to control box sizing, remove outlines on input focus, and hide scrollbars in Firefox, respectively.

### What challenges did I face?

- Achieving responsive design and layout alignment required careful use of flexbox and CSS properties.
- Implementing the search input and styling proved to be challenging due to cross-browser compatibility.

### A walkthrough of  code:

- The HTML structure includes header navigation, left sidebar, and main content.
- CSS styles were applied to achieve the desired layout and appearance.
- Media queries can be added for responsiveness on smaller screens.

- Hosted Link: https://velpurivineela.github.io/Geekster-Assignments/CSS_Assignment_YouTube_Clone/index.html
