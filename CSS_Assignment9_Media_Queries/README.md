# Media Queries
![Screenshot (150)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/638d5f99-2e51-44c3-b198-1e597bdc1eeb)
![Screenshot (151)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/9dc45ab0-d890-4be7-877b-368de58e73b5)
![Screenshot (152)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/41e01528-fee4-472c-80b8-5f48e303bab2)

## HTML

| Tag                | Property              | Value                                      | Description                            |
|--------------------|-----------------------|--------------------------------------------|----------------------------------------|
| `<html>`           | `lang`                | `"en"`                                     | Specifies the document language.       |
| `<head>`           |                       |                                            | Container for metadata.                |
| `<meta>`           | `charset`             | `"UTF-8"`                                  | Sets the character encoding.           |
|                    | `name`                | `"viewport"`                               | Defines the viewport for responsiveness.|
|                    | `content`             | `"width=device-width, initial-scale=1.0"` | Sets initial scale for mobile devices. |
| `<title>`          |                       |                                            | Defines the title of the page.         |
|                    | Text                  | `"My Awesome Website"`                     | Specifies the page title.              |
| `<link>`           | `rel`                 | `"stylesheet"`                             | Indicates an external stylesheet.      |
|                    | `href`                | `"style.css"`                              | Links to the CSS stylesheet.           |
| `<body>`           |                       |                                            | Container for the webpage content.     |
|                    | Content               | Your HTML content goes here                | Placeholder for your content.          |
| `<header>`         |                       |                                            | Header section of the webpage.         |
| `<nav>`            | `class`               | `"navbar"`                                 | Defines a navigation menu.             |
|                    |                       |                                            |                                        |
| `<ul>`             | `id`                  | `"menu"`                                   | Unordered list for the menu.           |
|                    |                       |                                            |                                        |
| `<li>`             |                       |                                            | List items for the menu.              |
|                    | `class`               | `"menu-item"`                              | Defines a menu item.                  |
|                    |                       |                                            |                                        |
|                    | Text                  | `"Home"`                                   | Text content for the menu item.        |
|                    |                       |                                            |                                        |
| `<a>`              | `href`                | `"#"`                                      | Hyperlink for the menu item.          |
|                    |                       |                                            |                                        |
|                    | Text                  | `"About"`                                  | Text content for the menu item.        |
|                    |                       |                                            |                                        |
| `<li>`             |                       |                                            | List items for the menu.              |
|                    | `class`               | `"menu-item"`                              | Defines a menu item.                  |
|                    |                       |                                            |                                        |
|                    | Text                  | `"Services"`                               | Text content for the menu item.        |
|                    |                       |                                            |                                        |
| `<a>`              | `href`                | `"#"`                                      | Hyperlink for the menu item.          |
|                    |                       |                                            |                                        |
|                    | Text                  | `"Contact"`                                | Text content for the menu item.        |
| `<section>`        | `class`               | `"main-content"`                          | Main content section of the webpage.  |
|                    |                       |                                            |                                        |
| `<h1>`             |                       |                                            | Main heading of the content section.  |
|                    | Text                  | `"Welcome to My Website"`                 | Text content for the heading.         |
| `<p>`              |                       |                                            | Paragraph of introductory text.       |
|                    | Text                  | `"This is some introductory text."`       | Text content for the paragraph.       |

## CSS

| Selector           | Property              | Value                                      | Description                            |
|--------------------|-----------------------|--------------------------------------------|----------------------------------------|
| *                  | `margin`              | `0`                                        | Resets margin for all elements.        |
|                    | `padding`             | `0`                                        | Resets padding for all elements.       |
|                    | `box-sizing`          | `border-box`                               | Sets box-sizing to border-box.        |
|                    | `font-family`         | Font stack for text elements.              | Defines the default font family.      |
| `body`             | `background-color`    | `#f0c50b`                                  | Sets background color for the body.   |
| .header            | `height`              | `20vh`                                     | Defines the height of the header.     |
|                    | `background-color`    | `white`                                    | Sets the background color of the header.|
| .main              | `height`              | `120%`                                     | Defines the height of the main section. |
|                    | `display`             | `flex`                                     | Displays content in a flex container.  |
|                    | `justify-content`     | `center`                                   | Centers content horizontally.         |
|                    | `max-width`           | `1280px`                                   | Sets the maximum width of the main content. |
| .item1             | `position`            | `relative`                                 | Positions the item relatively.        |
|                    | `top`                 | `-50px`                                    | Shifts the item vertically.           |
|                    | `max-width`           | `305px`                                    | Sets the maximum width for item1.     |
| .item1 img         | `max-width`           | `305px`                                    | Sets the maximum width for item1 image.|
|                    | `height`              | `450px`                                    | Sets the height for item1 image.      |
| .item2             | `margin-left`         | `40px`                                     | Sets left margin for item2.           |
|                    | `max-width`           | `300px`                                    | Sets the maximum width for item2.     |
|                    | `height`              | `400px`                                    | Sets the height for item2.            |
|                    | `text-align`          | `center`                                   | Centers text content.                  |
|                    | `display`             | `flex`                                     | Displays content in a flex container.  |
|                    | `flex-direction`      | `column`                                   | Arranges content in a column.         |
|                    | `justify-content`     | `center`                                   | Centers content vertically.            |
| .item2 h1          | `font-size`           | `2.2rem`                                   | Sets font size for heading.           |
|                    | `font-weight`         | `800`                                      | Sets font weight for heading.         |
| .para              | `font-weight`         | `bold`                                     | Sets font weight for paragraphs.      |
|                    | `margin-top`          | `10px`                                     | Sets top margin for paragraphs.       |
|                    | `font-size`           | `1rem`                                     | Sets font size for paragraphs.        |
|                    | `width`               | `80%`                                      | Sets width for paragraphs.            |
|                    | `margin`              | `auto`                                     | Centers
- Hosted Link: https://velpurivineela.github.io/Geekster-Assignments/CSS_Assignment9_Media_Queries/index.html
