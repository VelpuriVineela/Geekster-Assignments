# Grid Template

## HTML

| Tag                 | Property             | Value                                      | Description                            |
|---------------------|----------------------|--------------------------------------------|----------------------------------------|
| `<!DOCTYPE html>`   |                      |                                            | HTML document type declaration.        |
| `<html>`            | `lang`               | `"en"`                                     | Specifies the document language.       |
| `<head>`            |                      |                                            | Container for metadata.                |
| `<meta>`            | `charset`            | `"UTF-8"`                                  | Sets the character encoding.           |
|                     | `name`               | `"viewport"`                               | Defines the viewport for responsiveness.|
|                     | `content`            | `"width=device-width initial-scale=1.0"`  | Sets initial scale for mobile devices. |
| `<title>`           |                      |                                            | Defines the title of the page.         |
|                     | Text                 | `"FEM Grid"`                               | Specifies the page title.              |
| `<link>`            | `rel`                | `"stylesheet"`                             | Indicates an external stylesheet.      |
|                     | `href`               | `"style.css"`                              | Links to the CSS stylesheet.           |
| `<body>`            |                      |                                            | Container for the webpage content.     |
| `<main>`            |                      |                                            | Main content section of the webpage.   |
|                     | Content              | Your HTML content goes here                | Placeholder for your content.          |
| `.a1`, `.a2`, `.a3`, `.a4`, `.a5` | `grid-area` | `A`, `B`, `C`, `D`, `E`                 | Defines grid areas for cards.          |

## CSS

| Selector            | Property             | Value                                      | Description                            |
|---------------------|----------------------|--------------------------------------------|----------------------------------------|
| `*`                 | `margin`, `box-sizing` | `0`, `border-box`                        | Resets margin and box-sizing for all elements. |
| `body`              | `padding`, `background-color`, `font-family`, `line-height` | `32px 0`, `#ecf2f8`, `"Barlow Semi Condensed", sans-serif`, `1.2` | Sets body styles.              |
| `.main`             | `display`, `gap`, `width`, `margin` | `grid`, `1.5rem`, `95%`, `auto` | Styles the main grid container.   |
| `.a1`, `.a2`, `.a3`, `.a4`, `.a5` | `background-color`, `color`, `background-image`, `background-repeat`, `background-position`, `padding`, `line-height` | Sets styles for individual cards. |
| `.profile-heading`  | `display`, `align-items` | `flex`, `center`                   | Styles the profile headings.        |
| `.cards`            | `padding`, `border-radius` | `32px`, `8px`                     | Styles the cards.                   |
| `.cards img`        | `border-radius`, `width`, `height` | `50%`, `28px`, `28px`          | Styles the profile images.          |
| `.profile-part1`    | `margin-inline`      | `1rem`                                     | Sets margin for profile images.       |
| `.profile-part2 h2` | `font-size`          | `13px`                                     | Sets font size for profile names.     |
| `.profile-part2 p`  | `font-size`, `opacity` | `11px`, `0.5`                            | Sets font size and opacity for graduate status. |
| `.para-heading`     | `font-size`, `margin-top` | `1.25rem`, `1em`                        | Styles paragraph headings.            |
| `.para-content`     | `font-size`, `opacity`, `margin-top` | `0.8rem`, `0.7`, `1em`            | Styles paragraph content.             |

## Media Queries

The project includes media queries to ensure responsiveness at different screen sizes.

- `min-width: 300px`: Single-column layout for smaller screens.
- `min-width: 38em`: Two-column layout for medium screens.
- `min-width: 54em`: Three-column layout for larger screens.
- `min-width: 75em`: Four-column layout for extra-large screens.

## Hosted Link: https://velpurivineela.github.io/Geekster-Assignments/CSS_Assignment8_Grid_Template/index.html

