Task 15.3: Create responsive-text.HTML

Aim: Create an h1 and paragraph, set body font size to 1rem and h1 to 1.5rem, then set h1 to 2.5rem at 600px and up.

Software / Tools Required: HTML editor and web browser.

Theory: rem units are relative to the root font size. Media queries let styles change according to viewport characteristics such as width.

Algorithm / Procedure:
1. Create responsive-text.html.
2. Set body font size to 1rem and h1 to 1.5rem.
3. Add a min-width:600px media query.
4. Set h1 font size to 2.5rem in that query and test at different widths.

Program / Queries / Commands:

responsive-text.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Text</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Responsive Text Example</h1>

    <p>
      This is a responsive webpage created using HTML and external CSS. The
      heading size changes according to the screen width. On smaller screens,
      the heading is smaller, and on larger screens, the heading becomes bigger.
    </p>
  </body>
</html>

style.css
/* Base Styles */
body {
  font-size: 1rem;
  font-family: Arial, sans-serif;
  margin: 20px;
  line-height: 1.6;
}

h1 {
  font-size: 1.5rem;
  color: darkblue;
}

p {
  font-size: 1rem;
  color: #333;
}

/* Media Query for screens 600px and wider */
@media screen and (min-width: 600px) {
  h1 {
    font-size: 2.5rem;
  }
}

Input: Any heading and paragraph.

Output: The heading becomes larger when the viewport is at least 600px wide.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is rem?
•	2. What does a media query test?
•	3. Why is the viewport meta tag important?
