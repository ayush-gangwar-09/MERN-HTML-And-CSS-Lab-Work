Task 3: Add a second heading and view history

Aim: Add an h2 heading below the h1, commit the change and display the one-line history.

Software / Tools Required: HTML file and Git commands.

Theory: Git commits provide a history of project changes. git log --oneline displays a compact list of commits.

Algorithm / Procedure:
1. Add an h2 to index.html.
2. Save the file.
3. Stage and commit the change with the requested message.
4. Run git log --oneline.

Program / Queries / Commands:

index.html
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Home Page</title>
</head>
<body>
    <h1>Welcome to My Home Page</h1>
    <h2>Next Meeting</h2>
    <p>This is my first HTML page using Git.</p>
</body>
</html>

Run:
git add index.html
git commit -m "Add next meeting heading"
git log --oneline

Input: Second heading: Next Meeting.

Output: Terminal output listing both commits, newest first.
 
Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does git log show?
•	2. What does --oneline mean?
•	3. Can a commit be amended?

