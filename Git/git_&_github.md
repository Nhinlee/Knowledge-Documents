# Git
- Git is a software that allows you to keep track of changes made to a project over time. Git works by recording the changes you make to a project, storing those changes, then allowing you to reference them as needed.
- [Git cheatsheet](./resources/git-cheat-sheet-education.pdf)

## Git Basic Workflow
- [cheatsheet](./resources/basic_git_workflow.pdf)

![](./resources/basic_git_workflow.png)

- **git init** creates a new Git repository
- **git status** inspects the contents of the working directory and staging area
- **git add** adds files from the working directory to the staging area
- **git diff** shows the difference between the working directory and the staging area
- **git commit** permanently stores file changes from the staging area in the repository
- **git log** shows a list of all previous commits

## Important Git Operations
- `git checkout HEAD filename`: Discards changes in the working directory.
- `git reset HEAD filename`: Unstages file changes in the staging area.
- `git reset commit_SHA`: Resets to a previous commit in your commit history.