## 🧩Git Commands — Definitions and Examples


 ### 1. git init:

Definition: Creates a new Git repository in the current folder. It allows Git to track changes in your project.
<br>
*Example:*
<br>
`git init`
<br>
Use: To start tracking a new project with Git.
<br></br>

### 2. git clone:
<br>
Definition: Copies an existing remote repository to your computer.
<br>
*Example:*
<br>
`git clone https://github.com/username/project.git`
<br>
Use: To download a project from GitHub.
<br></br>

### 3. git status:
<br>
Definition: Shows the current state of your repository, including changed and untracked files.
<br>
*Example:*
<br>
`git status`
<br>
Use: To check which files have been changed or are ready to commit.
<br></br>

### 4. git add:
<br>
Definition: Adds changes to the staging area so they can be included in the next commit.
<br>
*Example:*
<br>
`git add README.md`
<br>
Use: To prepare a file for committing.
<br>
To stage all changes, you can use git add ..
<br></br>

### 5. git commit:
<br>
Definition: Saves staged changes as a new commit in the local repository.
<br>
*Example:*
<br>
`git commit -m "Add README file"`
<br>
Use: To save a checkpoint of your work with a meaningful message.
<br></br>

### 6. git log:
<br>
Definition: Displays the history of commits made in the repository.
<br>
*Example:*
<br>
`git log`
<br>
For a shorter view:
<br>
`git log --oneline`
<br>
Use: To check previous commits and their messages.
<br></br>

### 7. git diff:
<br>
Definition: Shows the differences between file versions or changes that have not yet been staged.
<br>
*Example:*
<br>
`git diff`
<br>
Use: To review your changes before adding and committing them.
<br></br>

### 8. git push:
<br>
Definition: Uploads your local commits to a remote repository, such as GitHub.
<br>
*Example:*
<br>
`git push origin main`
<br>
Use: To share your committed changes on GitHub.
<br></br>

### 9. git pull:
<br>
Definition: Downloads changes from a remote repository and integrates them into your current branch.
<br>
*Example:*
<br>
`git pull origin main`
<br>
Use: To update your local branch with the latest changes from GitHub.
<br></br>

### 10. git fetch:
<br>
Definition: Downloads new commits and branch information from a remote repository without integrating those changes into your current branch.
<br>
*Example:*
<br>
`git fetch origin`
<br>
Use: To check for updates from GitHub before deciding how to integrate them.
