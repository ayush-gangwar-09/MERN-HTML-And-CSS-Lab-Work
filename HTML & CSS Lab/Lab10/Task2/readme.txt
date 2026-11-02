Task 10.2: Create style.css

Aim: Create CSS rules for all h1 elements, .note, #title and all p elements.

Software / Tools Required: Text editor and CSS file.

Theory: An external stylesheet stores reusable styles in a .css file. Type selectors target element names, class selectors use a dot and id selectors use a hash.

Algorithm / Procedure:
1. Create style.css.
2. Set h1 to navy.
3. Set .note to italic and #title to underlined.
4. Set p font size to 18px and text colour to grey.

Program / Queries / Commands:

index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Selectors</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>CSS Fundamentals</h1>

    <h2 id="title">Understanding CSS Selectors</h2>

    <p class="note">
      This paragraph demonstrates the use of a class selector in CSS.
    </p>

    <p>
      CSS helps us style HTML elements using selectors and properties.
    </p>

    <p>
      External CSS keeps the styling separate from the HTML structure.
    </p>
  </body>
</html>

style.css
/* Heading Selector */
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

/* Paragraph Selector */
p {
  font-size: 18px;
  color: grey;
}


Input: No input values required.

Expected Output: Once linked, headings, notes and paragraphs use the specified styles.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. How do class and id selectors differ?
•	2. What is an external stylesheet?
•	3. What does text-decoration: underline do?
