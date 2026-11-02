Task 10.1: Create inline-internal.html

Aim: Add internal CSS to make h1 navy and .highlight yellow; add a red inline-styled paragraph and a highlight paragraph.

Software / Tools Required: HTML editor and web browser.

Theory: CSS controls the presentation of HTML. Internal styles are placed in style within head, while inline styles use the style attribute on an element.

Algorithm / Procedure:

1. Create inline-internal.html.
2. Add internal rules for h1 and .highlight.
3. Add one paragraph with inline red text.
4. Add a paragraph with class highlight.

Program / Queries / Commands:

inline-internal.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inline and Internal CSS</title>

    <style>
      h1 {
        color: navy;
      }

      .highlight {
        background-color: yellow;
      }
    </style>
  </head>
  <body>
    <h1>CSS Fundamentals</h1>

    <p style="color: red">
      This paragraph uses inline CSS to display red text.
    </p>

    <p class="highlight">
      This paragraph uses internal CSS to display a yellow background.
    </p>
  </body>
</html>

Input: Any heading and two paragraph texts.

Expected Output: A navy heading, red paragraph and yellow-highlighted paragraph appear.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.


Viva-Voce Questions:
•	1. What is inline CSS?
•	2. Where is internal CSS written?
•	3. What does a class selector look like?
