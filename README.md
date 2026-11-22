What is git pull?
git pull is used to download the latest changes from GitHub and update your local project with those changes.



1. Understand with an example
Initially, your local project and GitHub project have the same files.
Local computer
- index.html
- app.js


GitHub
- index.html
- app.js



Both are in sync

Now imagine your teammate adds a new file called login.html to GitHub.
GitHub repository
- index.html
- app.js
- login.html New file

Your local repository
- index.html
- app.js

Local project is behind

You don't have login.html on your computer yet.









Scenario 1: You modify code in your local repository
You add some new code to server.js on your computer.

Now you want to send those changes to GitHub.

You should use:
git add .
git commit -m "Updated server code"
git push origin main






Scenario 2: Someone modifies code in GitHub
Your teammate adds some code to server.js directly on GitHub.

Now you want those changes on your computer.

You should use:
git pull origin main