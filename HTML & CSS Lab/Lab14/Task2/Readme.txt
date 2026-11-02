Task 14.2: Create gallery.html

Aim: Create a Club Photo Gallery heading and six labelled boxes using repeat(auto-fill, minmax(150px, 1fr)) with 10px gap.

Software / Tools Required: HTML editor and web browser.

Theory: auto-fill creates as many grid tracks as fit in the container. minmax sets minimum and maximum track sizes, supporting responsive layouts.

Algorithm / Procedure:
1. Create gallery.html.
2. Add the heading and six photo boxes.
3. Set grid-template-columns to repeat(auto-fill, minmax(150px, 1fr)).
4. Set gap to 10px and resize the browser.

Program / Queries / Commands:

gallery.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Club Photo Gallery</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Club Photo Gallery</h1>

    <div class="gallery">
      <div class="photo">Photo 1</div>
      <div class="photo">Photo 2</div>
      <div class="photo">Photo 3</div>
      <div class="photo">Photo 4</div>
      <div class="photo">Photo 5</div>
      <div class="photo">Photo 6</div>
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
  color: darkblue;
  margin-bottom: 25px;
}

/* Responsive Photo Gallery */
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
  gap: 10px;
}

/* Gallery Photos */
.photo {
  background-color: steelblue;
  color: white;
  min-height: 150px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  font-weight: bold;
  border-radius: 8px;
}

Input: Photo 1 through Photo 6.

Expected Output: As the window gets wider, more boxes fit in each row.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does minmax do?
•	2. What is auto-fill?
•	3. How does Grid differ from Flexbox?
