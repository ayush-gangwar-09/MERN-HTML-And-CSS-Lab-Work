Task 8.2: Create choices.html

Aim: Create a gender question with Female and Male radio buttons and a course dropdown with BCA and B.Tech.

Software / Tools Required: HTML editor and web browser.

Theory: Radio buttons sharing a name allow one selection within a group. A select element provides a dropdown list of options.

Algorithm / Procedure:
1. Create choices.html.
2. Add two radio buttons with the same name.
3. Add a select element with BCA and B.Tech options.
4. Open the page and test the choices.

Program / Queries / Commands:

choices.html
<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Choices Form</title>
  </head>
  <body>
    <h1>Student Registration Form</h1><form>
  <fieldset>
    <legend>Select Your Gender</legend>

    <input
      type="radio"
      id="female"
      name="gender"
      value="Female"
    />
    <label for="female">Female</label>

    <br />

    <input
      type="radio"
      id="male"
      name="gender"
      value="Male"
    />
    <label for="male">Male</label>
  </fieldset>

  <br />

  <label for="course">Select Your Course:</label>

  <select id="course" name="course">
    <option value="BCA">BCA</option>
    <option value="B.Tech">B.Tech</option>
  </select>

  <br /><br />

  <button type="submit">Submit</button>
</form>

  </body>
</html>

Input: Select one gender option and one course.

Output: Only one radio option can be selected; the dropdown contains BCA and B.Tech.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. Why do radio buttons in a group share a name?
•	2. What does select do?
•	3. What is an option element?
