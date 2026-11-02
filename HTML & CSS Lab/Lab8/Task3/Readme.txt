Task 8.3: Create signup-required.html

Aim: Create full name and email fields, make both required, add a placeholder to the name field and a submit button.

Software / Tools Required: HTML editor and web browser.

Theory: The required attribute enables browser-side validation that prevents form submission when a required field is empty. Placeholder text gives a brief input hint.

Algorithm / Procedure:

1. Create signup-required.html.
2. Add name and email fields.
3. Add required to both inputs.
4. Add a name placeholder and Submit button.
5. Test submitting with empty fields.

Program / Queries / Commands:

signup-required.html
<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Required Sign-Up Form</title>
  </head>
  <body>
    <h1>Sign-Up Form</h1><form action="thanks.html" method="post">
  <label for="fullname">Full Name:</label>
  <input
    type="text"
    id="fullname"
    name="fullname"
    placeholder="Enter your full name"
    required
  />

  <br /><br />

  <label for="email">Email:</label>
  <input
    type="email"
    id="email"
    name="email"
    placeholder="Enter your email address"
    required
  />

  <br /><br />

  <button type="submit">Submit</button>
</form>

  </body>
</html>

Input: Leave fields blank to test validation, then enter valid values.

Expected Output: The browser displays a validation message when a required field is empty.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does required do?
•	2. What is a placeholder?
•	3. Is client-side validation a replacement for server-side validation?