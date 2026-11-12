Task 9.2: Create marks-average.html

Aim: Create the same caption and headers, include Asha and Rohan only, and show their average Maths and Science marks in tfoot.

Software / Tools Required: HTML editor and web browser.

Theory: The tfoot element groups summary rows. Average is calculated by adding the values and dividing by the number of students: Maths (78+64)/2 = 71; Science (85+70)/2 = 77.5.

Algorithm / Procedure:
1. Create marks-average.html.
2. Add caption and thead.
3. Add Asha and Rohan to tbody.
4. Add a tfoot row with Class average, 71 and 77.5.

Program / Queries / Commands:

marks-average.html
<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Marks Average</title>
  </head>
  <body>
    <h1>Student Marks and Average</h1><table border="1">
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
  </tbody>

  <tfoot>
    <tr>
      <th>Class Average</th>
      <td>71</td>
      <td>77.5</td>
    </tr>
  </tfoot>
</table>

  </body>
</html>

Input: Asha 78/85 and Rohan 64/70.

Output: The footer row shows Maths average 71 and Science average 77.5.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is tfoot used for?
•	2. How is an average calculated?
•	3. Can a table contain thead, tbody and tfoot?
