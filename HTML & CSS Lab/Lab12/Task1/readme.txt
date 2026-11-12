Task 12.1: Create box-model.html

Aim: Create two boxes with width 200px, padding 20px and border 5px; use content-box for one and border-box for the other.

Software / Tools Required: HTML editor and web browser.

Theory: The CSS box model consists of content, padding, border and margin. With content-box, padding and border add to declared width; with border-box, they are included in declared width.

Algorithm / Procedure:
1. Create box-model.html.
2. Add two divs.
3. Apply equal width, padding and border.
4. Set box-sizing differently and compare widths.

Program / Queries / Commands:

box-model.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Box Model</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Box Model</h1>

    <div class="box content-box">
      <h2>Content Box</h2>
      <p>Width: 200px</p>
      <p>Padding: 20px</p>
      <p>Border: 5px</p>
    </div>

    <div class="box border-box">
      <h2>Border Box</h2>
      <p>Width: 200px</p>
      <p>Padding: 20px</p>
      <p>Border: 5px</p>
    </div>
  </body>
</html>


style.CSS
/* Base Styles */
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  background-color: #f4f4f4;
}

h1 {
  text-align: center;
  color: darkblue;
}

/* Common Box Styles */
.box {
  width: 200px;
  padding: 20px;
  border: 5px solid black;
  margin: 20px 0;
}

/* Content Box */
.content-box {
  box-sizing: content-box;
  background-color: lightblue;
}

/* Border Box */
.border-box {
  box-sizing: border-box;
  background-color: lightgreen;
}

Input: Two boxes with width 200px, padding 20px and border 5px.

Output: The content-box element is wider than the border-box element.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What are the four parts of the box model?
•	2. How does content-box calculate width?
•	3. What does border-box change?
