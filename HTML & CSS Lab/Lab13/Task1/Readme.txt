Task 1: Create nav-flex.html

Aim: Create a horizontal nav with Home, About, Events and Contact using display:flex, dark background and white link text.

Software / Tools Required: HTML editor and web browser.

Theory: Flexbox is a one-dimensional layout model for arranging items in rows or columns. display:flex makes a container a flex container.

Algorithm / Procedure:
1. Create nav-flex.html.
2. Add a nav with four anchor links.
3. Set display:flex and a dark background.
4. Style links white with spacing.

Program / Queries / Commands:

nav-flex.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flexbox Navigation Bar</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <nav class="navbar">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#events">Events</a>
      <a href="#contact">Contact</a>
    </nav>
  </body>
</html>

style.css
/* Base Styles */
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

/* Navigation Bar */
.navbar {
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #222;
  padding: 20px;
}

/* Navigation Links */
.navbar a {
  color: white;
  text-decoration: none;
  font-size: 18px;
  padding: 10px 15px;
}

/* Hover Effect */
.navbar a:hover {
  background-color: #444;
  border-radius: 5px;
}

Input: Home, About, Events, Contact.

Expected Output: A dark navigation bar displays four white links side by side.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does display:flex do?
•	2. What is a flex container?
•	3. Which property controls space between flex items?
