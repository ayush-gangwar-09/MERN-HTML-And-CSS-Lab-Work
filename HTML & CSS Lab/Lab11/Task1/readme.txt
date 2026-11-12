Task 11.1: Create units.html

Aim: Create a 200px-wide box, a 50%-wide box, both 40px high, and a paragraph with font size 1.5rem.

Software / Tools Required: HTML editor and web browser.

Theory: CSS units include absolute units such as px and relative units such as %, em and rem. Percentages are relative to a containing block; rem is relative to the root font size.

Algorithm / Procedure:
1. Create units.html.
2. Add two div boxes and a paragraph.
3. Style the boxes with required dimensions and background colours.
4. Set paragraph font-size to 1.5rem.

Program / Queries / Commands:

units.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Units Example</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Units Example</h1>

    <div class="pixel-box">200px Wide Box</div>

    <div class="percentage-box">50% Wide Box</div>

    <p>
      This paragraph demonstrates the use of the rem unit for font sizing in
      CSS. The text is larger than the default browser font size.
    </p>
  </body>
</html>

style.css
/* Base Styles */
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  background-color: #f4f4f4;
}

/* Heading */
h1 {
  color: darkblue;
}

/* Fixed Width Box */
.pixel-box {
  width: 200px;
  height: 40px;
  background-color: lightblue;
  margin-bottom: 20px;
  text-align: center;
  line-height: 40px;
}

/* Percentage Width Box */
.percentage-box {
  width: 50%;
  height: 40px;
  background-color: lightgreen;
  margin-bottom: 20px;
  text-align: center;
  line-height: 40px;
}

/* Paragraph with rem Unit */
p {
  font-size: 1.5rem;
  color: #333;
}

Input: Viewport width determines the 50% box width.

Output: A 200px box, a half-width box and larger text appear.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is px?
•	2. What does % width depend on?
•	3. What is the difference between em and rem?
