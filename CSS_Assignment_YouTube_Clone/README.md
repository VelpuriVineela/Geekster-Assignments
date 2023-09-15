# YouTube Clone
| HTML | CSS |
|------|-----|
| ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YouTube Clone</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <!-- Your HTML content goes here -->
</body>
</html>
``` | ```css
/* Your CSS styles go here */

/* Example: */
* {
   box-sizing: border-box;
   margin: 0;
   padding: 0;
}

/* Rest of your CSS styles */
``` |

| Header | Main | Main Left | Main Right |
|--------|------|-----------|------------|
| ```html
<header>
    <nav class="navbar">
        <!-- Header content goes here -->
    </nav>
</header>
``` | ```html
<main>
    <!-- Main content goes here -->
</main>
``` | ```html
<aside class="main-left">
    <!-- Main Left content goes here -->
</aside>
``` | ```html
<div class="main-right">
    <!-- Main Right content goes here -->
</div>
``` |

| CSS (continued) |      |      |
|-----------------|------|------|
| ```css
/* CSS for Header */
header {
   background-color: white;
   height: 70px;
   display: flex;
   align-items: center;
   position: fixed;
   width: 100%;
   top: 0;
}

/* CSS for Navbar, Search Container, Header Icons, etc. */
.navbar {
   /* Styles for the navigation bar */
}

/* Add more CSS styles for specific elements */
/* ... */
``` |      |      |

| Left Category | User Personal |      |      |
|---------------|---------------|------|------|
| ```html
<div class="left-category">
    <!-- Left Category content goes here -->
</div>
``` | ```html
<div class="user-personal">
    <!-- User Personal content goes here -->
</div>
``` |      |      |

| CSS (continued) |      |      |
|-----------------|------|------|
| ```css
/* CSS for Left Category */
.left-category {
   /* Styles for left category */
}

/* Add more CSS styles for specific elements */
/* ... */
``` |      |      |

| Main Right (continued) |      |      |
|------------------------|------|------|
| ```html
<div class="cards-box">
    <!-- Cards Box content goes here -->
</div>
``` |      |      |

| CSS (continued) |      |      |
|-----------------|------|------|
| ```css
/* CSS for Cards Box and Cards */
.cards-box {
   display: flex;
   justify-content: space-around;
   flex-wrap: wrap;
   gap: 30px;
}

.card {
   /* Styles for individual cards */
}

/* Add more CSS styles for specific elements */
/* ... */
``` |      |      |

This table format provides a clear and organized structure for your HTML and CSS code in my README file.
