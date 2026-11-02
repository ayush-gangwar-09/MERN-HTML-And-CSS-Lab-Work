Task 7.2: Add About section

Aim: Add a section with id about inside main, with an h2 heading and a paragraph about yourself.

Software / Tools Required: HTML editor and web browser.

Theory: A section groups related content. An id can be targeted by a fragment link from the navigation.

Algorithm / Procedure:
1. Open about-me.html.
2. Inside main, add section id="about".
3. Add an h2 and a short paragraph.
4. Save and test the About link.

Program / Queries / Commands:

about-me.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Me</title>
</head>
<body>
  <header>
    <h1>Ayush Kumar</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <main>
    <section id="about">
      <h2>About me</h2>
      <p>I am a student interested in web development and programming.</p>
    </section>
  </main>
  <footer></footer>
</body>
</html>



Input: A short paragraph describing your interests or studies.

Expected Output: The About me heading and paragraph appear under the navigation.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is section used for?
•	2. Why must the id match the link fragment?
•	3. Can multiple elements share the same id?
