# Magazine UI 

![Screenshot (193)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/de364bcc-bd0d-4e61-8440-2a2c0adfa24d)

![Screenshot (194)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/dc135fa8-a2e3-45fd-8e84-4c63617619ac)

![Screenshot (195)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/1cde8889-8323-48f7-ac7b-85c81df1d84d)

![Screenshot (196)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/77338d75-7ca1-4e43-998e-a64fc1485989)

![Screenshot (197)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/f475c97d-e452-42ad-8d27-bbae6815cfed)


## Table of Contents

- [Introduction](#introduction)
- [HTML Structure](#html-structure)
- [CSS Styles](#css-styles)
- [Media Queries](#media-queries)

## Introduction

This README provides an in-depth overview of the HTML and CSS code used to create the Magazine UI. It explains the elements, tags, properties, and values used in various sections of the UI.

## HTML Structure

The HTML structure defines the content hierarchy and layout of the magazine. Here's a breakdown of the key elements:

| Element                  | Description                                                                                   |
| ------------------------ | --------------------------------------------------------------------------------------------- |
| `<html>`                 | The root element of the HTML document. Contains metadata and the document's content.        |
| `<head>`                 | Contains metadata elements such as character set, viewport settings, and linked stylesheets. |
| `<link>`                 | Links external stylesheets for fonts and icons.                                              |
| `<body>`                 | Contains the main content of the page.                                                        |
| `<main>`                 | Represents the main content of the page, divided into sections for better organization.      |
| `<section class="heading">` | Represents the header section of the magazine.                                             |
| `<header class="hero">` | Contains a hero image, title, and subtitle.                                                  |
| `<h1 class="hero-title">` | Displays the main title of the hero section.                                               |
| `<p class="hero-subtitle">` | Displays a subtitle in the hero section.                                                   |
| `<div class="author">` | Contains information about the author and publication date.                                   |
| `<div class="social-icons">` | Displays social media icons for sharing.                                                    |
| `<section class="text">` | Represents the main text content of the magazine.                                           |
| ... (continue for other elements) |

## CSS Styles

The CSS styles define the visual presentation and layout of the magazine. Here are the key CSS styles and their purposes:

| CSS Selector                     | Description                                                                                   |
| --------------------------------- | --------------------------------------------------------------------------------------------- |
| Universal Selector                | Resets padding, margin, and box-sizing for all elements.                                     |
| `html`                            | Sets the base font size to 62.5% for easier rem unit calculations.                            |
| `body`                            | Defines the font family, text color, and background color for the entire page.                |
| `h1`, `h2`, `h3`, `h4`, `h5`, `h6` | Sets different font families for various header levels.                                       |
| `a`                               | Defines styles for links, including text decoration and color.                                  |
| `.heading`                        | Styles the heading section, including a grid layout and row gap.                               |
| `.text`                           | Styles the main text content, including font size, letter spacing, and column width.          |
| ... (continue for other styles) |

## Media Queries

Media queries provide responsive design by adjusting styles for different screen widths. Here are the key media queries and their effects:

- Media Query 1 (max-width: 720px): Adjusts image-wrapper layout.
- Media Query 2 (max-width: 600px): Adjusts text-with-images layout.
- Media Query 3 (max-width: 550px): Modifies font sizes for various elements.
- Media Query 4 (max-width: 420px): Further adjusts the hero title font size.

These media queries ensure that the magazine UI looks good and functions well on various devices and screen sizes.

This README provides a comprehensive guide to the structure and styling of the Magazine UI's HTML and CSS code. It serves as a valuable reference for developers working on or maintaining the codebase.

Hosted Link: https://velpurivineela.github.io/Geekster-Assignments/Major_Project_Grid_Magzine/index.html
