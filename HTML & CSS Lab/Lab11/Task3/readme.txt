Task 11.3: Create tokens.css

Aim: Create tokens.css with primary, accent, heading-size and spacing variables and use them for body and h1 styles.

Software / Tools Required: Text editor and CSS file.

Theory: Design tokens are reusable values that help keep styling consistent. A linked CSS file can define and apply these values to any page that imports it.

Algorithm / Procedure:
1. Create tokens.css.
2. Define the four requested variables in :root.
3. Use variables for body colour and padding.
4. Use accent colour and heading size for h1.

Program / Queries / Commands:

tokens.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Design Tokens</title>

    <link rel="stylesheet" href="tokens.css" />
  </head>
  <body>
    <h1>CSS Design Tokens</h1>

    <p>
      CSS variables help us store and reuse colours, font sizes, and spacing
      values throughout a webpage. They make the design consistent and easy to
      maintain.
    </p>

    <div class="card">
      <h2>Welcome to My Website</h2>
      <p>
        This card demonstrates the use of CSS variables for colours, heading
        sizes, and spacing.
      </p>
    </div>
  </body>
</html>

tokens.css
/* CSS Variables */
:root {
  --primary-color: #1d3557;
  --accent-color: #e63946;
  --heading-size: 2rem;
  --spacing: 16px;
}

/* Body Styles */
body {
  font-family: Arial, sans-serif;
  background-color: var(--primary-color);
  color: white;
  padding: var(--spacing);
  margin: 0;
}

/* Main Heading */
h1 {
  color: var(--accent-color);
  font-size: var(--heading-size);
  text-align: center;
}

/* Card Styles */
.card {
  background-color: white;
  color: var(--primary-color);
  padding: var(--spacing);
  margin-top: var(--spacing);
  border-radius: 8px;
}

/* Card Heading */
.card h2 {
  color: var(--accent-color);
  font-size: var(--heading-size);
}

/* Paragraph */
p {
  line-height: 1.6;
}


Input: Primary #1d3557, accent #e63946, heading size 2rem, spacing 16px.

Expected Output: When linked to a page, body colour, padding, h1 colour and size use the token values.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What are design tokens?
•	2. Why are CSS variables useful?
•	3. How do you link a CSS file to HTML?
