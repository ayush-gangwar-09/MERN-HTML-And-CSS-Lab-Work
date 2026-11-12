Task 1.1: Initialize Git repository and configure identity

Aim: Create a folder named html-lab, initialize Git, set local user name/email, and display the configured values.

Software / Tools Required: Terminal commands.

Theory: Git stores project history in a repository. git init creates a repository; git config --local sets repository-specific identity.

Algorithm / Procedure:
1. Create and open the html-lab folder.
2. Run git init.
3. Set user.name and user.email with --local.
4. Display both values.

Program / Queries / Commands:

mkdir html-lab
cd html-lab
git init
git config --local user.name "Ayush-gangwar-09"
git config --local user.email "gangwarayush032@gmail.com"
git config user.name
git config user.email

Input: No browser input.

Output: Terminal output showing repository initialization and configured name/email.

Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
1. What is Git?
2. What does git init do?
3. Why use git config --local?

