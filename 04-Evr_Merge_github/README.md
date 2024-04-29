# A Basic PR Workflow

In this activity, you will practise pushing local branches to GitHub, opening pull requests for those branches, and reviewing submitted code.This activity must be completed **after** the `pull` activity; it cannot stand alone. 
**⚠️ It is imperative that before doing a merge locally, you do a pull, so you are actually merging on the updated main branch.⚠️**

## Instructions

1. After pulling the updated `main` branch, each team member should create a new branch, named according to the `<name>/<name of feature>` formula. 🚨 `git checkout -b <name>/<name of feature>`

2. Add or change anything you'd like on this branch.Dont forget to add changes and commit. 🚨`git add .` ➡️ `git commit -m '<description of the commit>'`

3. Once you're done making changes, push the branch to GitHub.🚨 `git push origin <name>/<name of features>`

4. Next, navigate to your repository in your browser.

5. Find the dropdown menu on the top left of your repository's file display, which should be labelled `main` while you are on the `main` branch. **⚠️ You might also find a new pop-up message saying that there is a new pull request available. You can click on this and proceed with the next step (step 6).**

  >* Click the dropdown, and select the new branch you just pushed.

  >* Find and click the dropdown labeled **contribute** above the file list.

  >* Click the “Open pull request” button, which will open a new page for the pull request.

  >* When creating pull requests for your projects, you will want to add comments in the text box to track changes made. But, for the purpose of this activity, you can click the "Create a pull request" button to create a pull request forthis branch.

  >* Next, find and click the menu tab labeled **Pull Requests** near the top of the repository.

7. Click one of your teammates' pull requests.

  >* Explore the pull request. In particular, explore the **Files Changed** tab.

  >* Leave a comment on the pull request.

  >* Then, approve and merge it, using the GUI provided in the browser.

8. Make sure you are on the main branch, and do a final pull, so you have the most updated file. `git checkout main` ➡️ `git pull`

**⚠️ Now that ther merge has been done, you can delete those extras branches in your local repository and in github**
* Discuss the advantages and disadvantages of this PR workflow; will your team use this approach to manage projects?

- - -

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
