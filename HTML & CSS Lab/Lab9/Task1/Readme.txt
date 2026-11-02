Task 9.1: Create marks.html

Aim: Create a table captioned Marks of Class A, with Name, Maths and Science headers and three student rows.

Software / Tools Required: HTML editor and web browser.

Theory: Tables organize tabular data. caption names the table; thead groups header rows; tbody groups the main data rows.

Algorithm / Procedure:
1. Create marks.html.
2. Add a table and caption.
3. Add a thead row with three headers.
4. Add tbody rows for Asha, Rohan and Neha.

Program / Queries / Commands:

marks.html
<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Marks of Class A</title>
  </head>
  <body>
    <h1>Student Marks</h1><table border="1">
  <caption>
    Marks of Class A
  </caption>

  <thead>
    <tr>
      <th>Name</th>
      <th>Maths</th>
      <th>Science</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Asha</td>
      <td>78</td>
      <td>85</td>
    </tr>

    <tr>
      <td>Rohan</td>
      <td>64</td>
      <td>70</td>
    </tr>

    <tr>
      <td>Neha</td>
      <td>91</td>
      <td>88</td>
    </tr>
  </tbody>
</table>

  </body>
</html>


Input: Asha 78 85; Rohan 64 70; Neha 91 88.

Expected Output: A table displays the caption, header row and three student rows.


Result: The task was performed and the expected output can be verified after running the supplied code/commands.


Viva-Voce Questions:
•	1. What is the purpose of caption?
•	2. What does thead represent?
•	3. What is the difference between th and td?
