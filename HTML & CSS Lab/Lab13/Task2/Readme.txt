Task 2: Create centred-cards.html

Aim: Create a row div holding Starter, Standard and Premium cards with prices 199, 349 and 499. Center them using justify-content and align-items.

Software / Tools Required: HTML editor and web browser.

Theory: justify-content aligns flex items along the main axis; align-items aligns them along the cross axis.

Algorithm / Procedure:
1. Create centred-cards.html.
2. Add a row container and three cards.
3. Add the requested headings and prices.
4. Use display:flex, justify-content and align-items.

Program / Queries / Commands:

centred-cards.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Centred Cards</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Pricing Plans</h1>

    <div class="row">
      <div class="card">
        <h3>Starter</h3>
        <p>Price: ₹199</p>
      </div>

      <div class="card">
        <h3>Standard</h3>
        <p>Price: ₹349</p>
      </div>

      <div class="card">
        <h3>Premium</h3>
        <p>Price: ₹499</p>
      </div>
    </div>
  </body>
</html>

style.css
/* Base Styles */
body {
  margin: 0;
  padding: 20px;
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
}

h1 {
  text-align: center;
  color: #222;
  margin-bottom: 30px;
}

/* Flexbox Row */
.row {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}

/* Pricing Cards */
.card {
  width: 200px;
  padding: 25px;
  background-color: white;
  border: 1px solid #ddd;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.card h3 {
  color: darkblue;
  font-size: 22px;
}

.card p {
  color: #333;
  font-size: 18px;
  font-weight: bold;
}

Input: Starter 199, Standard 349, Premium 499.

Output: Three cards appear in one centered row.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does justify-content control?
•	2. What does align-items control?
•	3. What is the main axis?
