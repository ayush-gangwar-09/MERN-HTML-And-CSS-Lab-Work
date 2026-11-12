Task 11.2: Create variables.html

Aim: Define --main-color, --accent-color and --page-padding in :root, then use them for body colour, padding and h1 colour.

Software / Tools Required: HTML editor and web browser.

Theory: CSS custom properties are reusable values declared with --property-name and accessed through var(). The :root selector makes variables globally available in the document.

Algorithm / Procedure:
1. Create variables.html.
2. Define the three requested variables in :root.
3. Use var() for body colour and padding.
4. Use the accent colour for h1.

Program / Queries / Commands:

variables.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Variables Example</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Variables Example</h1>

    <p>
      CSS variables help us store and reuse colours and spacing values
      throughout a webpage. They make styling easier to maintain and update.
    </p>
  </body>
</html>

style.css
/* CSS Variables */
:root {
  --main-color: #1d3557;
  --accent-color: #e63946;
  --page-padding: 20px;
}

/* Body Styles */
body {
  background-color: var(--main-color);
  padding: var(--page-padding);
  font-family: Arial, sans-serif;
  color: white;
}

/* Heading Styles */
h1 {
  color: var(--accent-color);
  font-size: 2rem;
}

/* Paragraph Styles */
p {
  font-size: 1rem;
  line-height: 1.6;
}

Input: Main colour #1d3557, accent #e63946 and padding 20px.

Output: The heading uses the accent colour; body text uses the main colour and page padding is applied.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. How do you declare a CSS variable?
•	2. How do you read a CSS variable?
•	3. What is :root?
