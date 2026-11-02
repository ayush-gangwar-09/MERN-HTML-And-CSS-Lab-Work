Task 13.3: Create wrapping-cards.html

Aim: Create Stationery Shop with four cards in a flex-wrap row: Notebook 60, Pen 15, Bag 350 and Book 120.

Software / Tools Required: HTML editor and web browser.

Theory: flex-wrap allows flex items to move onto additional rows when they no longer fit in the container's available width.

Algorithm / Procedure:
1. Create wrapping-cards.html.
2. Add the Stationery Shop heading.
3. Add four cards with product names and prices.
4. Set display:flex and flex-wrap:wrap, then narrow the browser window.

Program / Queries / Commands:
wrapping-cards.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Stationery Shop</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>Stationery Shop</h1>

    <div class="card-container">
      <div class="card">
        <h2>Notebook</h2>
        <p>Price: ₹60</p>
      </div>

      <div class="card">
        <h2>Pen</h2>
        <p>Price: ₹15</p>
      </div>

      <div class="card">
        <h2>Bag</h2>
        <p>Price: ₹350</p>
      </div>

      <div class="card">
        <h2>Book</h2>
        <p>Price: ₹120</p>
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

/* Heading */
h1 {
  text-align: center;
  color: darkblue;
  margin-bottom: 30px;
}

/* Flexbox Container */
.card-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

/* Product Cards */
.card {
  width: 200px;
  padding: 20px;
  background-color: white;
  border: 1px solid #ddd;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Card Heading */
.card h2 {
  color: #2563eb;
  font-size: 22px;
}

/* Card Price */
.card p {
  color: #333;
  font-size: 18px;
  font-weight: bold;
}

Input: Notebook 60, Pen 15, Bag 350, Book 120.

Expected Output: Cards wrap onto new rows when the browser window is narrow.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does flex-wrap do?
•	2. How can you add spacing between cards?
•	3. What is a responsive layout?
