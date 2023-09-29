# Flipkart Navbar

![Screenshot (182)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/3d7f9e42-957e-4fdd-a759-10a9f8a6f3b3)

![Screenshot (183)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/c80d1c65-6b23-405d-86c1-c10cfc49f1be)

![Screenshot (184)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/346fcf4d-4fe1-4876-8b77-38aa48199fba)

![Screenshot (185)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/415f2537-1fbd-4ccd-8886-989a502cd76a)

![Screenshot (186)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/4670494b-302d-42af-8388-ddaca8204d73)

![Screenshot (187)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/4203bb71-db5a-4932-8976-04fc3b8cbaa8)

![Screenshot (188)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/81f7c8ed-4c63-45b5-8e8f-4c162a981895)

![Screenshot (189)](https://github.com/VelpuriVineela/Geekster-Assignments/assets/134683293/3af481ea-94ac-4945-94e6-43f20ff548a1)

## HTML

| Tag                     | Property                    | Value                                                    | Description                                |
|-------------------------|-----------------------------|----------------------------------------------------------|--------------------------------------------|
| `<!DOCTYPE html>`       |                             |                                                          | HTML document type declaration.            |
| `<html>`                | `lang`                      | `"en"`                                                   | Specifies the document language.           |
| `<head>`                |                             |                                                          | Container for metadata.                    |
| `<meta>`                | `charset`                   | `"UTF-8"`                                                | Sets the character encoding.               |
|                         | `http-equiv`                | `"X-UA-Compatible"`                                     | Specifies the rendering mode for IE.        |
|                         | `name`                      | `"viewport"`                                             | Defines the viewport for responsiveness.    |
| `<link>`                | `rel`                       | `"stylesheet"`                                          | Indicates an external stylesheet.          |
|                         | `href`                      | `"style.css"`                                           | Links to the CSS stylesheet.               |
| `<title>`               |                             |                                                          | Defines the title of the page.             |
|                         | Text                        | `"Flipkart"`                                             | Specifies the page title.                  |
| `<body>`                |                             |                                                          | Container for the webpage content.         |
| `<main>`                |                             |                                                          | Main content section of the webpage.       |
| `<header>`              | `class`                     | `"menu"`                                                 | Defines the header section with a menu.    |
| `<nav>`                | `class`                     | `"navbar"`                                              | Navigation container within the header.     |
|                         |                             |                                                          |                                           |
| `.navbar-list`         | `list-style`, `display`,     | `none`, `flex`,                                          | Styles the navigation list.                 |
|                         | `align-items`, `gap`,       | `center`, `50px`,                                       |                                           |
|                         | `color`                     | `white`                                                  |                                           |
| `.plus`                 | `color`, `font-size`,       | `#FFE500`, `14px`,                                      | Styles the "plus" text.                     |
|                         | `font-family`, `margin`     | `"Roboto, Arial, sans-serif"`, `0px 2px 0px 2px`        |                                           |
| `.explore`              | `color`, `font-size`,       | `#F0F0F0`, `14px`,                                      | Styles the "Explore" text.                  |
|                         | `font-family`, `margin`     | `"Roboto, Arial, sans-serif"`, `0px 0px 0px 201px`      |                                           |
|                         |                             |                                                          |                                           |
| `.img`                  | `filter`, `width`,          | `white`, `110px`, `27px`,                              | Styles the Flipkart logo.                  |
|                         | `height`, `margin`          | `14px`, `200px`                                         |                                           |
|                         | `object-fit`                | `cover`                                                  |                                           |
| `.search-input`         | `width`, `height`,          | `600px`, `43px`,                                        | Styles the search input field.             |
|                         | `margin-left`, `margin-top`  | `310px`, `-20px`                                        |                                           |
|                         | `margin-bottom`, `padding`, | `15px`, `0px 16px`,                                   |                                           |
|                         | `color`, `font-size`,       | `grey`, `17px`                                          |                                           |
|                         | `font-family`,              | `"sans-serif"`                                          |                                           |
|                         | `background-image`,         | `"url(search.png)"`,                                    |                                           |
|                         | `background-repeat`,        | `no-repeat`                                             |                                           |
|                         | `background-position`,      | `right center`                                          |                                           |
|                         | `border`                    | `none`                                                   |                                           |
| `.button`               | `border`, `width`,          | `none`, `150px`, `38px`,                               | Styles the login button.                   |
|                         | `height`, `background`,     | `white`, `#2874f0`,                                     |                                           |
|                         | `color`, `font-size`,       | `#2874f0`, `16px`,                                      |                                           |
|                         | `font-weight`,              | `bold`,                                                  |                                           |
|                         | `margin-bottom`             | `22px`                                                   |                                           |
| `.data`                 | `font-size`,                | `19px`, `font-weight: bold`                           | Styles the "Become a Seller" text.         |
|                         | `margin-bottom`             | `18px`                                                   |                                           |
| `.text`                 | `font-size`,                | `19px`, `font-weight: bold`                           | Styles the "More" text.                   |
|                         | `margin-bottom`             | `18px`                                                   |                                           |
| `.cart`                 | `background`, `height`,     | `#2874f0`, `50px`, `50px`,                             | Styles the shopping cart icon.             |
|                         | `width`, `margin-left`,     | `-15px`, `13px`                                        |                                           |
|                         | `margin-bottom`,            | `13px`                                                   |                                           |
| `.content`              | `font-size`,                | `19px`, `font-weight: bold`                           | Styles the "Cart" text.                   |
|                         | `margin-bottom`,            | `18px`                                                   |                                           |
| `.body`                 | `width`, `height`,          | `100%`, `174px`,                                        | Styles the body section.                   |
|                         | `background-color

- Hosted Link: https://velpurivineela.github.io/Geekster-Assignments/CSS_Assignment_FilpKart_Navbar/index.html
