# Git Pull and Push Branches

In this activity, you will practise pushing to and pulling from branches on GitHub.

## Instructions

* Elect a team leader for this activity. This leader will **create** and **push** changes to a repository that other members will **pull** from.

1. **First, make sure to complete the following steps:**

  >* The team leader should create a new GitHub repo.

  >* Each member of the team should `clone` this repo to their computer. 🚨`git clone <HTTPS link>`

2. Next, on the `main` branch of the project, the team leader should add and commit a file called `data_exploration.py` and then push their changes to GitHub. 🚨`git add .` ➡️ `git commit -m '<description of the commit>'` ➡️ `git push`

  >* Team members should then pull these changes to their local machines. 🚨 `git pull`

3. After pulling, each team member should **create a new branch** whose name follows the `<name>/branching_exercise` formula, where `<name>` is a placeholder for your name. 🚨 `git checkout -b <name>/branching_exercise`

  >* Next, each team member should add and commit a file named `<name>.txt`. Add a message to the file so that it can be committed. 🚨`git add .` ➡️ `git commit -m '<description of the commit>'`

  >* After saving the file, each team member should push their respective branches to GitHub. 🚨`git push origin <name>/branching_exercise`

3. Next, each team member should checkout the `main` branch. 🚨 `git checkout main`

4. While on `main`, everyone should pull changes from GitHub.
🚨 `git pull`

5. After pulling from GitHub, explore what's new (what teammates have added, etc.).

6. Try checking out a team member's branch: 🚨`git checkout <team_member_name>/branching_exercise`. 
⚠️ **Remember that branches from other people will not always show up in vscode after pulling**

- - -

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
