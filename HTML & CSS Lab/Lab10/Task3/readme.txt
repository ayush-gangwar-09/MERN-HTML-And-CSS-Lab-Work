Task 10.3: Create linked.html

Aim: Link style.css and create an h1 with id title plus two paragraphs with class note.

Software / Tools Required: HTML editor, CSS file and web browser.

Theory: An external stylesheet is linked with a link element whose rel is stylesheet and href points to the CSS file.

Algorithm / Procedure:
1. Create linked.html and style.css in the same folder.
2. Link style.css in head.
3. Add h1 id="title".
4. Add two paragraphs with class="note" and open the page.


Program / Queries / Commands:
linked.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Linked CSS Example</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1 id="title">Welcome to CSS Fundamentals</h1>

    <p class="note">
      External CSS allows us to style HTML elements using a separate CSS file.
    </p>

    <p class="note">
      We can reuse the same CSS styles for multiple elements on a webpage.
    </p>
  </body>
</html>

style.css
/* Heading Styles */
h1 {
  color: navy;
}

/* Class Selector */
.note {
  font-style: italic;
}

/* ID Selector */
#title {
  text-decoration: underline;
}

/* Paragraph Styles */
p {
  font-size: 18px;
  color: grey;
}

Input: Any heading and two paragraphs.

Expected Output: The page is styled when style.css is correctly linked.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does rel="stylesheet" mean?
•	2. Why must the CSS path be correct?
•	3. Can one CSS file style multiple HTML pages?

 