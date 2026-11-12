Task 1.2: Create and commit index.html

Aim: Create index.html with one h1 heading, check status, stage the file and commit it.

Software / Tools Required: HTML file and Git commands.

Theory: Git tracks changes through the working tree, staging area, and commits. git add stages a file and git commit records the staged snapshot.

Algorithm / Procedure:
1. Create index.html with an h1.
2. Run git status.
3. Run git add index.html.
4. Commit with message Add home page.

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
    <p>This is my first HTML page using Git.</p>
</body>
</html>

After creating index.html, run:
git status
git add index.html
git commit -m "Add home page"

Input: Sample heading: Welcome to My Home Page.
                       This is my first HTML page using Git.

Output: Terminal output showing a successful commit and one file changed.
 
Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
1. What is a commit?
2. What does git add do?
3. How does git status help?

