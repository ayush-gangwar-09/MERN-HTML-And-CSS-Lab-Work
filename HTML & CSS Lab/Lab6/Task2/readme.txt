Task 6.2: Create canteen-menu.html

Aim: Create a numbered list of Samosa and Sandwich, with a nested numbered list Cheese and Vegetable under Sandwich.

Software / Tools Required: HTML editor and web browser.

Theory: An ordered list uses ol and list items use li. Lists can be nested by placing another list inside an li element.

Algorithm / Procedure:
1. Create canteen-menu.html.
2. Add an h1 heading.
3. Create an ol with Samosa and Sandwich.
4. Nest a second ol under Sandwich with Cheese and Vegetable.

Program / Queries / Commands:

canteen-menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Canteen Menu</title>
</head>
<body>
  <h1>Canteen Menu</h1>
  <ol>
    <li>Samosa</li>
    <li>Sandwich
      <ol>
        <li>Cheese</li>
        <li>Vegetable</li>
      </ol>
    </li>
  </ol>
</body>
</html>

Input: Samosa, Sandwich; nested items Cheese and Vegetable.

Expected Output: Two main numbered items appear, with a smaller numbered list under Sandwich.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. Which tag creates an ordered list?
•	2. How do you nest a list?
•	3. What is the difference between ol and ul?
