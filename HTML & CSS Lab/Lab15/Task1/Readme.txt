Task 15.1: Create mobile-first.html

Aim: Create a viewport meta tag and two cards that stack on phones and sit side by side at 600px and wider.

Software / Tools Required: HTML editor and web browser.

Theory: Mobile-first design starts with styles for smaller screens and adds enhancements at larger breakpoints using media queries.

Algorithm / Procedure:
1. Create mobile-first.html with the viewport meta tag.
2. Add a cards container with two cards.
3. Style the cards to stack by default.
4. Add a min-width: 600px media query to display them side by side.

Program / Queries / Commands:

mobile-first.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mobile First Cards</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Responsive Cards</h1>
  <div class="cards">
    <div class="card"><h2>Card One</h2><p>This is the first card.</p></div>
    <div class="card"><h2>Card Two</h2><p>This is the second card.</p></div>
  </div>
</body>
</html>

style.css

.cards { 
    display: flex; 
    flex-direction: column; 
    gap: 16px; }

.card { 
    border: 1px solid #1d3557; 
    padding: 16px; 
    border-radius: 8px; 
    background: #f1faee; 
}

@media (min-width: 600px) {
    .cards { 
    flex-direction: row; 
    }

    .card { 
    flex: 1; 
    }
}

Input: Two cards with headings and paragraphs.

Expected Output: On a phone the cards stack; at 600px and above they sit side by side.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is a media query?
•	2. What is mobile-first design?
•	3. What does min-width: 600px mean?
