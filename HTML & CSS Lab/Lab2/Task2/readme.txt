Task 2.2: Push commits to origin

Aim: Push the current branch and its commits to origin.

Software / Tools Required: Git terminal.

Theory: git push sends local commits to a remote repository. The branch name may be main or master depending on repository configuration.

Algorithm / Procedure:
1. Check the current branch with git branch --show-current.
2. Push using git push origin main, or use master if that is the current branch.

Program / Queries / Commands:

Check branch:
git branch --show-current
 
If branch is main:
git push origin main
 
If branch is master:
git push origin master

Input: Existing commits and origin remote.

Output: Terminal output confirming the branch was pushed.
 
Result: The task was performed and the expected output can be verified after running the supplied code/commands.

Viva-Voce Questions:
•	1. What does git push do?
•	2. What is a branch?
•	3. Why might a repository use master instead of main?

