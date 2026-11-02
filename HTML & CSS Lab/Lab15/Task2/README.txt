Task 15.2: Create responsive-image.html

Aim: Create a heading and an image from the images folder with max-width:100% and height:auto.

Software / Tools Required: HTML editor, browser and instructor-provided image.

Theory: max-width: 100% prevents an image from exceeding its container width. height:auto preserves its aspect ratio as its width changes.

Algorithm / Procedure:

1. Create responsive-image.html.
2. Add the instructor-provided image inside images.
3. Set max-width:100% and height:auto.
4. Resize the browser to check the image.

Program / Queries / Commands:

responsive-image.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Image</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Responsive Image Example</h1>

    <p>
      This image automatically adjusts its size according to the screen width.
    </p>

    <img src="images\WhatsApp Image 2026-08-02 at 7.54.01 PM.jpeg" alt="ayush" />
  </body>
</html>


style.css
/* Base Styles */
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  text-align: center;
}

h1 {
  color: darkblue;
  font-size: 2rem;
}

p {
  color: #333;
  font-size: 1rem;
}

/* Responsive Image */
img {
  max-width: 100%;
  height: auto;
  display: block;
  margin: 20px auto;
}

Input: Image file placed in an images folder.

Expected Output: The image shrinks to fit a narrow window and keeps its aspect ratio.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does max-width:100% do?
•	2. Why use height:auto?
•	3. What is an image's aspect ratio?
