Task 9.3: Create marks-accessible.html

Aim: Create the same caption, header and Asha/Rohan rows, adding scope="col" to headers and scope="row" to name cells.

Software / Tools Required: HTML editor and web browser.

Theory: Scope attributes help assistive technologies associate table headers with the cells they describe.

Algorithm / Procedure:
1. Create marks-accessible.html.
2. Add the caption and header cells with scope="col".
3. Add Asha and Rohan rows.
4. Add scope="row" to each name cell.

Program / Queries / Commands:

marks-accessible.html
<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Accessible Marks Table</title>
  </head>
  <body>
    <h1>Student Marks</h1><table border="1">
  <caption>
    Marks of Class A
  </caption>

  <thead>
    <tr>
      <th scope="col">Name</th>
      <th scope="col">Maths</th>
      <th scope="col">Science</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <th scope="row">Asha</th>
      <td>78</td>
      <td>85</td>
    </tr>

    <tr>
      <th scope="row">Rohan</th>
      <td>64</td>
      <td>70</td>
    </tr>
  </tbody>
</table>

  </body>
</html>

Input: Asha and Rohan marks.

Expected Output: The table looks similar to marks.html; header and name cells carry scope attributes.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does scope="col" mean?
•	2. What does scope="row" mean?
•	3. How do scope attributes improve accessibility?
