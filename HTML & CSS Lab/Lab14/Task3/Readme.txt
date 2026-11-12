Task 14.3: Create dashboard-areas.html

Aim: Create a two-column grid with columns 200px and 1fr; use grid-template-areas for header, sidebar, main and footer.

Software / Tools Required: HTML editor and web browser.

Theory: Named grid areas provide readable placement of grid items. 
A dot in the template represents an empty cell, while repeated names can span multiple cells.

Algorithm / Procedure:
1. Create dashboard-areas.html.
2. Add header, sidebar, main and footer elements.
3. Define two columns: 200px and 1fr.
4. Use grid-template-areas so header and footer span both columns.

Program / Queries / Commands:
dashboard-areas.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Dashboard Layout</title>

    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="dashboard">
      <header class="header">
        <h1>Dashboard Header</h1>
      </header>

      <aside class="sidebar">
        <h2>Sidebar</h2>
        <p>Home</p>
        <p>About</p>
        <p>Services</p>
        <p>Contact</p>
      </aside>

      <main class="main-content">
        <h2>Main Content</h2>
        <p>
          Welcome to the dashboard layout example using CSS Grid named areas.
          This section contains the main content of the webpage.
        </p>
      </main>

      <footer class="footer">
        <p>Dashboard Footer &copy; 2026</p>
      </footer>
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

/* Dashboard Grid Layout */
.dashboard {
  display: grid;
  grid-template-columns: 200px 1fr;
  grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";
  gap: 12px;
  min-height: 90vh;
}

/* Header */
.header {
  grid-area: header;
  background-color: #1e3a8a;
  color: white;
  padding: 20px;
  text-align: center;
}

/* Sidebar */
.sidebar {
  grid-area: sidebar;
  background-color: #dbeafe;
  padding: 20px;
}

/* Main Content */
.main-content {
  grid-area: main;
  background-color: white;
  padding: 20px;
}

/* Footer */
.footer {
  grid-area: footer;
  background-color: #1e3a8a;
  color: white;
  padding: 15px;
  text-align: center;
}

/* Heading Styles */
h1,
h2 {
  margin-top: 0;
}

Input: Header, sidebar, main and footer content.

Output: Header spans the top; sidebar is left, main is right and footer spans the bottom.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is grid-template-areas?
•	2. How can an area span columns?
•	3. What does 1fr mean?
