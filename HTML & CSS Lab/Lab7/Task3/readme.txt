Task 7.3: Add contact link in footer

Aim: Add a paragraph in the footer with an email link using mailto: and give the footer id contact.

Software / Tools Required: HTML editor and web browser.

Theory: The mailto scheme creates a link that can open a configured email application. The footer can be targeted by #contact.

Algorithm / Procedure:
1. Give footer the id contact.
2. Add a paragraph containing an anchor with a mailto: href.
3. Save the file.
4. Test the Contact navigation link.

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
  <footer id="contact">
    <p>Email: <a href="mailto:gangwarayush032@gmail.com">gangwarayush032@gmail.com</a></p>
  </footer>
</body>
</html>

Input: Use a valid email address you control or a sample address.

Output: The footer shows a clickable email address and Contact jumps to it.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does mailto: do?
•	2. What is a footer element?
•	3. How does an in-page navigation link work?