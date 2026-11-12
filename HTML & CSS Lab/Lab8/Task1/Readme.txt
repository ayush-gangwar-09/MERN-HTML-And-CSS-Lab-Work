Task 8.1: Create signup.html

Aim: Create a form with method post, action thanks.html, labelled full name, email and password fields.

Software / Tools Required: HTML editor and web browser.

Theory: Forms collect user input. Labels improve accessibility when their for attribute matches the input id. Password inputs conceal typed characters.

Algorithm / Procedure:
1. Create signup.html.
2. Add a form with method post and action thanks.html.
3. Add labels and matching input ids for name, email and password.
4. Add a submit button.


Program / Queries / Commands:

signup.html
<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sign-Up Form</title>
  </head>
  <body>
    <h1>Sign-Up Form</h1><form action="thanks.html" method="post">
  <label for="fullname">Full Name:</label>
  <input
    type="text"
    id="fullname"
    name="fullname"
    required/>
  <br/><br />

  <label for="email">Email:</label>
  <input
    type="email"
    id="email"
    name="email"
    required/>
  <br/><br />

  <label for="password">Password:</label>
  <input
    type="password"
    id="password"
    name="password"
    required/>
  <br/><br />

  <button type="submit">Sign Up</button>
</form>

  </body>
</html>

Input: Name, email and password entered by the user.

Output: Three labelled fields appear; password characters are hidden when typed.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is the purpose of form?
•	2. Why should labels be associated with inputs?
•	3. What is the difference between email and password input types?

