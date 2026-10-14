##🧩Git Commands — Definitions and Examples


 ### 1. git init:

Definition: Creates a new Git repository in the current folder. It allows Git to track changes in your project.
*Example:*
`git init`
Use: To start tracking a new project with Git.


### 2. git clone:

Definition: Copies an existing remote repository to your computer.
*Example:*
`git clone https://github.com/username/project.git`
Use: To download a project from GitHub.


### 3. git status:

Definition: Shows the current state of your repository, including changed and untracked files.
*Example:*
`git status`
Use: To check which files have been changed or are ready to commit.


### 4. git add:

Definition: Adds changes to the staging area so they can be included in the next commit.
*Example:*
`git add README.md`
Use: To prepare a file for committing.
To stage all changes, you can use git add ..


### 5. git commit:

Definition: Saves staged changes as a new commit in the local repository.
*Example:*
`git commit -m "Add README file"`
Use: To save a checkpoint of your work with a meaningful message.


### 6. git log:

Definition: Displays the history of commits made in the repository.
*Example:*
`git log`
For a shorter view:
`git log --oneline`
Use: To check previous commits and their messages.


### 7. git diff:

Definition: Shows the differences between file versions or changes that have not yet been staged.
*Example:*
`git diff`
Use: To review your changes before adding and committing them.


### 8. git push:

Definition: Uploads your local commits to a remote repository, such as GitHub.
*Example:*
`git push origin main`
Use: To share your committed changes on GitHub.


### 9. git pull:

Definition: Downloads changes from a remote repository and integrates them into your current branch.
*Example:*
`git pull origin main`
Use: To update your local branch with the latest changes from GitHub.


### 10. git fetch:

Definition: Downloads new commits and branch information from a remote repository without integrating those changes into your current branch.
*Example:*
`git fetch origin`
Use: To check for updates from GitHub before deciding how to integrate them.
