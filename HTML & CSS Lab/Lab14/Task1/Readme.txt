Task 14.1: Create grid-first.html

Aim: Create six numbered boxes in a grid of three equal columns with a 12px gap.

Software / Tools Required: HTML editor and web browser.

Theory: CSS Grid is a two-dimensional layout system. grid-template-columns defines column tracks and fr distributes available space proportionally.

Algorithm / Procedure:
1. Create grid-first.html.
2. Add six div boxes numbered 1 to 6.
3. Set display:grid and three equal 1fr columns.
4. Set gap to 12px.

Program / Queries / Commands:

grid-first.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Grid Layout</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Grid Layout</h1>

    <div class="grid-container">
      <div class="box">1</div>
      <div class="box">2</div>
      <div class="box">3</div>
      <div class="box">4</div>
      <div class="box">5</div>
      <div class="box">6</div>
    </div>
  </body>
</html>

style.css
/* Base Styles */
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  background-color: #f4f4f4;
}

h1 {
  text-align: center;
  color: #222;
  margin-bottom: 20px;
}

/* Grid Container */
.grid-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
}

/* Grid Boxes */
.box {
  background-color: steelblue;
  color: white;
  padding: 40px 20px;
  text-align: center;
  font-size: 24px;
  font-weight: bold;
  border-radius: 8px;
}

Input: Numbers 1 to 6.

Output: Six boxes appear in two rows of three with small gaps.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is CSS Grid?
•	2. What does 1fr mean?
•	3. What does gap control?
