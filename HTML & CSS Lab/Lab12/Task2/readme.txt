Task 12.2: Create card.html

Aim: Create a card div with a background, 2px border, 12px rounded corners and 16px padding; include h3 and paragraph.

Software / Tools Required: HTML editor and web browser.

Theory: A card is a common interface component. CSS background, border, border-radius and padding control its appearance and internal spacing.

Algorithm / Procedure:
1. Create card.html.
2. Add a div with class card.
3. Add h3 and paragraph.
4. Apply the specified background, border, radius and padding.

Program / Queries / Commands:
card.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Styled Card</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Card Example</h1>

    <div class="card">
      <h3>Welcome to My Card</h3>

      <p>
        This is a simple card created using HTML and external CSS. It has a
        coloured background, a border, rounded corners, and padding.
      </p>
    </div>
  </body>
</html>

style.css
/* Base Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
  background-color: #f4f4f4;
}

/* Main Heading */
h1 {
  text-align: center;
  color: darkblue;
  margin-bottom: 30px;
}

/* Card Styling */
.card {
  max-width: 350px;
  margin: 0 auto;
  padding: 16px;
  background-color: lightblue;
  border: 2px solid steelblue;
  border-radius: 12px;
}

/* Card Heading */
.card h3 {
  color: darkblue;
  margin-top: 0;
}

/* Card Paragraph */
.card p {
  color: #333;
  font-size: 16px;
  line-height: 1.6;
}

Input: Card heading and description.

Expected Output: A coloured card with rounded corners, border and padding appears.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does border-radius do?
•	2. What is padding?
•	3. How is border different from margin?
