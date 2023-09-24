# Animations
![Screenshot (153)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/26870e83-819e-49bd-8438-1111da0fda8e)

## HTML

| Tag                | Property              | Value                                      | Description                            |
|--------------------|-----------------------|--------------------------------------------|----------------------------------------|
| `<!DOCTYPE html>`  |                       |                                            | HTML document type declaration.        |
| `<html>`           | `lang`                | `"en"`                                     | Specifies the document language.       |
| `<head>`           |                       |                                            | Container for metadata.                |
| `<meta>`           | `charset`             | `"UTF-8"`                                  | Sets the character encoding.           |
|                    | `name`                | `"viewport"`                               | Defines the viewport for responsiveness.|
|                    | `content`             | `"width=device-width initial-scale=1.0"`  | Sets initial scale for mobile devices. |
| `<title>`          |                       |                                            | Defines the title of the page.         |
|                    | Text                  | `"Animations"`                             | Specifies the page title.              |
| `<link>`           | `rel`                 | `"stylesheet"`                             | Indicates an external stylesheet.      |
|                    | `href`                | `"./style.css"`                            | Links to the CSS stylesheet.           |
| `<body>`           |                       |                                            | Container for the webpage content.     |
| `<main>`           |                       |                                            | Main content section of the webpage.   |
|                    | Content               | Your HTML content goes here                | Placeholder for your content.          |

## CSS

| Selector           | Property              | Value                                      | Description                            |
|--------------------|-----------------------|--------------------------------------------|----------------------------------------|
| `*`                | `margin`              | `0`                                        | Resets margin for all elements.        |
|                    | `padding`             | `0`                                        | Resets padding for all elements.       |
|                    | `box-sizing`          | `border-box`                               | Sets box-sizing to border-box.        |
| `body`             | `background-color`    | `black`                                    | Sets background color for the body.   |
| `main`             | `display`             | `flex`                                     | Displays content in a flex container.  |
|                    | `justify-content`     | `flex-end`                                 | Aligns content to the right.           |
|                    | `align-items`         | `center`                                   | Centers content vertically.            |
|                    | `height`              | `100vh`                                    | Sets the height of the main section.  |
| `.main .image`     | `-webkit-box-reflect` | Below 0 linear-gradient                   | Creates a reflection effect.           |
|                    | `transform`           | `perspective(800px) rotateY(20deg)`        | Applies a 3D transformation effect.    |
|                    | `margin`              | `0 5px`                                    | Adds margin between images.            |
|                    | `transition`          | `0.5s`                                     | Defines a smooth transition effect.    |
| `.main .image:hover`| `transform`          | `perspective(800px) rotateY(0)`           | Removes the 3D transformation on hover.|
|                    | `opacity`             | `1`                                        | Sets full opacity on hover.            |
| `.main:hover img`  | `opacity`             | `0.4`                                      | Reduces opacity of all images on hover.|
| `.main img`        | `width`               | `350px`                                    | Sets the width of images.             |
|                    | `height`              | `350px`                                    | Sets the height of images.            |
|                    | `border-radius`       | `4px`                                      | Rounds image corners.                  |
|                    | `box-shadow`          | `0px 0px 8px grey`                        | Adds a box shadow effect.              |

- Hosted Link: https://velpurivineela.github.io/Geekster-Assignments/CSS_Assignment10_Animations/index.html
