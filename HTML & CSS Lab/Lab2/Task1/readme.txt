Task 2.1: Create a bare repository and add origin

Aim: Create a bare repository next to html-lab, add it as origin and list remotes.

Software / Tools Required: Git terminal.

Theory: A bare repository stores Git data without a working checkout. A remote is a named location where commits can be pushed or fetched.

Algorithm / Procedure:
1. From inside html-lab, create ../html-remote with git init --bare.
2. Add it as origin.
3. Run git remote -v.

Program / Queries / Commands:
Run inside html-lab:
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v

Input: Existing html-lab repository from Assignment 1.

Output: Terminal output showing origin for fetch and push.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What is a bare repository?
•	2. What is a remote?
•	3. What does origin usually represent?

