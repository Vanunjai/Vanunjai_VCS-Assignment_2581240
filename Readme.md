\# GIT-05 - Merge a Feature Branch \& Track Multiple Files



\## Objective



The objective of this practical is to demonstrate Git branch management, tracking multiple files, creating meaningful commits, merging a feature branch into the main branch, and verifying Git history.



\## Tools Used



\- Git

\- Git Bash

\- GitHub



\## Step-by-Step Procedure



\### 1. Repository Initialization



A project folder named GIT-05 was created and Git was initialized using:



git init



The repository status was checked using:



git status



The default branch was renamed to main using:



git branch -M main



\### 2. Initial Project Setup



A README.md file was created containing information about the practical.



The file was tracked using:



git add README.md



The initial commit was created using:



git commit -m "Initial project setup"



\### 3. Feature Branch



A separate feature branch was created using:



git checkout -b feature-branch



The available branches were verified using:



git branch



\### 4. Track Multiple Files



Three files were created:



\- feature.txt

\- index.html

\- style.css



The files were added to Git using:



git add feature.txt index.html style.css



Git status was used to verify that all three files were staged.



\### 5. Feature Commit



The three feature files were committed using:



git commit -m "Add feature files"



The Git history was then checked using:



git log --oneline



\### 6. Merge Feature Branch



The main branch was selected using:



git checkout main



The feature branch was merged using:



git merge feature-branch



The merged files were verified using:



ls



\### 7. Verification



The final repository was verified using:



git status



git branch



git log --oneline --graph --decorate --all



The working tree was checked to make sure that there were no uncommitted changes.



\## Git Commands Used



git init



git status



git branch



git branch -M main



git checkout -b feature-branch



git add



git commit



git checkout main



git merge



git log



git branch -d



\## Track Multiple Files



Multiple files were created on the feature branch and tracked together using the git add command.



The files were:



\- feature.txt

\- index.html

\- style.css



Git status was used to verify that all three files were staged before committing them.



\## Merge Feature Branch



The feature-branch was created to contain the new project files. After committing the changes, the main branch was checked out and the feature branch was merged into main.



This demonstrated how changes developed on a separate branch can be integrated into the main branch.



\## Verification



The repository was verified using git status, git branch and git log.



The final status confirmed that the working tree was clean.



The branch information confirmed that main contained the merged feature.



The Git log displayed the meaningful commits created during the practical.



\## Screenshots



1\. Initial setup

2\. Feature branch

3\. Multiple files tracked

4\. Feature commit

5\. Feature branch merge

6\. Final Git history

7\. GitHub repository

8\. GitHub commits



\## Result



The feature branch was successfully created and merged into main. Multiple files were successfully tracked and committed. The Git history was verified and the repository was prepared for GitHub submission.

