Task 12.3: Create scroll.html

Aim: Create a fixed-height 120px div with overflow auto and five paragraph lines.

Software / Tools Required: HTML editor and web browser.

Theory: The overflow property controls content that exceeds an element's box. Setting overflow: auto displays scrollbars when needed.

Algorithm / Procedure:
1. Create scroll.html.
2. Add a div with class scroll-box.
3. Set height to 120px and overflow to auto.
4. Add five paragraphs and test scrolling.

Program / Queries / Commands:

scroll.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Scrolling Box</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Scrolling Box</h1>

    <div class="scroll-box">
      <p>Line 1: Welcome to CSS scrolling example.</p>
      <p>Line 2: This box has a fixed height of 120px.</p>
      <p>Line 3: The overflow property is set to auto.</p>
      <p>Line 4: Scroll down to see more content.</p>
      <p>Line 5: You have reached the last line.</p>
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

/* Main Heading */
h1 {
  color: darkblue;
  text-align: center;
  margin-bottom: 25px;
}

/* Scrollable Box */
.scroll-box {
  height: 120px;
  overflow: auto;
  padding: 15px;
  border: 2px solid steelblue;
  background-color: white;
  border-radius: 8px;
}

/* Paragraph Styles */
.scroll-box p {
  font-size: 16px;
  margin: 10px 0;
  color: #333;
}

Input: Line 1 through Line 5.

Output: The lines do not all fit in the box at once; the box can be scrolled.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does overflow: auto do?
•	2. What is fixed height?
•	3. How does overflow: hidden differ from auto?
